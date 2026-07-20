---
name: ecom-listing-pro
description: AI-driven optimization of e-commerce product images and titles. Use when users upload product photos, screenshots, or provide product titles/descriptions for optimization, including but not limited to: (1) Optimizing product carousel images and writing image generation prompts, (2) Rewriting product titles for maximum conversion, (3) Auto-detecting and removing watermarks from product images, (4) Generating complete 5-6 piece carousel visual packages, (5) Applying consistent design styles (glassmorphism, isometric 3D, soft 3D). Triggers: user says "优化商品图"、"优化标题"、"优化首图"、"做轮播图"、"优化listing"、"optimize listing"、"optimize product image"、"carousel images"、"product title optimization". Supports both domestic e-commerce (Chinese content allowed) and cross-border e-commerce (strictly no Chinese characters, no faces, no promotional pricing).
metadata:
  short-description: E-commerce listing optimization — titles, images, carousels, watermark removal
---

# Ecom Listing Pro — 跨境电商图片与标题智能优化系统

## 核心原则

### 1. 智能主体识别
- 接收用户上传的商品图片后，自动分析图片识别商品主体
- 使用视觉分析判断：这是什么产品？材质？风格？目标市场？
- 若无法明确判断商品主体（多个物体、抽象产品等），**必须主动询问用户确认**
- 确认主体后，标记该产品的关键属性（品类、材质、风格、规格、目标市场）

### 2. 跨境 vs 国内模式感知
**跨境模式**（用户提及 "跨境"、"export"、"global"、"international"、"amazon"、"shopify"、"独立站" 或产品图无中文字样时自动触发）：
- ❌ 严禁中文汉字出现在标题和图片中
- ❌ 严禁华人面孔/写实人像特写
- ❌ 严禁直接显示价格、SALE、Free Shipping 等促销文字
- ❌ 严禁过曝炫光、写实摄影贴片
- ✅ 促销信息通过情感隐喻传达（礼物绑带、礼盒包装、场景氛围）

**国内模式**（无以上触发词时）：
- 可以使用中文
- 可以使用常规促销文字
- 可以使用模特实拍
- 仍然需要专业优化

### 3. 搜索成熟方案
- 对于确认的商品主体，搜索该品类在电商平台上的成熟优化方案
- 参考 Amazon Best Seller、跨境大卖的同类产品 listing 结构
- 提炼关键词策略、卖点排列、图片叙事逻辑
- 将搜索到的成熟方案结构化为输出

### 4. 原图诊断
对用户提供的每张图片进行系统性诊断：
- **水印检测**：识别图片中的水印位置和类型，自动调用去水印方案
- **逻辑错误**：尺寸标注是否正确（如5A/7A长度对应）、文字是否倒置、型号是否错位
- **设计缺失**：首图是否有钩子、是否缺少规格说明、是否缺少卖点可视化
- **风格一致性**：各图风格是否统一、是否混用不同设计语言
- **合规检查**：跨境模式下是否有中文字样

### 5. 标题优化 Formula
采用跨境电商标题结构化公式：
```
[情感钩子/品质词] + [核心材质/特征] + [品类关键词] + [规格/配置] + [场景/用途] + [信任锚点]
```
- 标题长度控制在 80-150 字符（亚马逊标准 200 字符以内）
- 埋入 5-7 个搜索关键词
- 情感词在前，规格词在后
- 大写关键词突出，介词小写

### 6. 6张轮播图标准结构
标准电商轮播图 5-6 张，每张聚焦一个信息层：
1. **Hero 主图**（首图）—— 产品悬浮展示，大标题情感钩子，双型号/多规格并列出镜
2. **尺寸/规格对比** —— 多型号对比，精确尺寸标注，信息卡可视化
3. **材质故事** —— 微距/细节展示，材质情感文案，工艺品质背书
4. **卖点网格** —— 2×2 或 3 列卖点卡片，图标 + 标题 + 一句话说明
5. **使用场景** —— 三场景联排，展示产品的多功能适用性
6. **情感礼物/传承** —— 礼盒包装隐喻，情感文案收尾

### 7. 设计风格智能匹配系统

**核心原则：不硬套单一风格。** 每次必须按品类智能匹配合适的设计风格。

#### 7.1 决策流程

```
Step 1: 确认商品主体 → 品类 / 材质 / 风格 / 目标人群
Step 2: 参考该品类 Top 100 大卖主流风格
Step 3: 从流行风格库中选用最匹配的方案
Step 4: 风格规范贯穿全部 6 张轮播图（禁止混搭）
Step 5: 自检 → 该风格是否有 ≥3 个同类对标案例？符合大众审美？
```

#### 7.2 品类→风格快速映射

| 品类示例 | 首选风格 | 备选风格 |
|---------|---------|---------|
| 乐器（鼓棒/吉他） | **玻璃拟态+等距3D** | Futuristic 科技 |
| 数码配件/消费电子 | **极简白底科技风** | 赛博霓虹 |
| 游戏外设/电竞 | **赛博霓虹/未来科技** | 极简+发光 |
| 食品/酒类/高端美妆 | **拟真杂志/电影级** | 自然植物系 |
| 手工/传统工艺/茶道 | **日式手绘插画** | 玻璃拟态 |
| 儿童/玩具/宠物 | **软3D黏土风** | 手绘插画 |
| 护肤品/精油/天然 | **自然植物系** | 拟真摄影 |
| 黑胶/古着/复刻 | **复古做旧风** | 日式插画 |
| 木制家具/家居 | **玻璃拟态+等距3D** | 复古风 |
| 时尚/配饰 | **极简白底** | 杂志风 |
| 健身/运动器材 | **极简白底** | 赛博科技 |
| 文具/办公用品 | **日式手绘** | 软3D黏土 |

> **详细 8 种流行风格完整规范、色板、字体、参考案例 → 见 `references/carousel-design-spec.md`**

#### 7.3 默认首推：玻璃拟态 + 等距3D + 软3D（Style A）

当品类符合下列任一条件时，优先使用此方案：

- ✅ 商品主体为**天然材质**（木、竹、石、麻、棉、陶）
- ✅ 商品强调**手工工艺/匠人精神**
- ✅ 商品具有**自然纹理/独特材质感**
- ✅ 乐器类产品（鼓棒、吉他拨片、琴弦）
- ✅ 品类 Top 100 卖家中使用 ≥3 个对标案例

**色板（以温感材质为例，按实际适配）：**
- 暖木色：`#F4E3C8 / #D6A972 / #7A4A24`
- 玻璃层：`rgba(255,255,255,0.18)` + 1px 高光 `rgba(255,255,255,0.6)`
- 背景：暖灰→深炭 `#1A1A22` 渐变
- 强调色：`#3FA9F5`（≤5%面积）
- 字体色：`#FFFFFF`（深底）/ `#1A1A22`（浅底），规格文 `#5A5A66`

**玻璃拟态规范：**
- 圆角：16/24/32px 三档，根据信息层级选择
- backdrop-filter: blur(20px)
- 投影：近层 `0 8px 24px rgba(0,0,0,0.18)` + 远层 `0 24px 48px rgba(0,0,0,0.10)`

**3D 规范：**
- 主图视角 30°/15° 等距，产品占画面 55-60%
- 产品保留材质纹理 + 柔光（无硬反射）
- 悬浮感：2层柔影 + 1层地面反光
- 字体：Bold Sans（标题）/ Light Condensed（规格）/ Tabular（数字）

#### 7.4 禁止项（跨境模式，所有风格通用）
- ❌ 任何中文
- ❌ 价格 / SALE / Free Shipping
- ❌ 写实人脸/手部特写
- ❌ 过曝炫光、写实摄影贴片

#### 7.5 选择检查清单

每次选择风格前逐项确认：
- [ ] 该风格在品类 Top 100 中有 ≥3 个对标案例？
- [ ] 符合大众审美而非个人偏好？
- [ ] 与商品材质/气质一致？
- [ ] 跨境模式下无中文/人像/价格问题？
- [ ] 能在一套 6 张图中保持风格一致性？
- [ ] 参考了 ≥2 个同类大卖的实际 listing？
- [ ] 最终方案比原图有明显提升？

### 8. 图片 Prompt 生成模式

根据用户输入的不同场景，支持三种 Prompt 生成模式（参考自 Ozon-Profit-Skills 的设计）：

#### 模式 A — 自定义模版（用户提供模版）
用户提供自己的 Prompt 模版 → 填入商品标题/规格/卖点 → 生成最终 Prompt
```
适用场景：用户有成熟的视觉风格偏好，希望复用固定模版
模版由用户在 prompt_template 参数中提供
技能负责将标题/规格/卖点填入模版对应位置
```

#### 模式 B — 参考图反推（用户提供参考图）
用户提供参考图/参考风格 → 分析视觉风格 → 结合商品信息生成 Prompt
```
分析内容：
1. 图片结构：商品位置、标题位置、卖点标签位置、整体构图
2. 文字内容与样式：标题/副标题/卖点标签的具体内容，文字颜色/大小/样式
3. 背景：颜色和质感描述
4. 风格：整体视觉风格定位（极简/奢华/自然/科技等）
5. 视觉效果：光影方向、立体感、投影等
6. 商品信息：规格和卖点的目标语言翻译
```

#### 模式 C — 竞品首图模仿（用户提供竞品链接）
用户提供竞品链接 → 抓取竞品首图 → 分析其视觉风格 → 生成类似风格的 Prompt
```
适用场景：对标竞品，快速出同级别视觉素材
需配合 Web Reader 能力抓取竞品商品页首图
生成的 Prompt 与原竞品风格一致但商品信息不同
避免直接抄袭，保持视觉层级相似但内容独创
```

### 9. 随机刷新灵感（Anti-AI Countermeasure）

当生成以下类型图片时，必须应用反 AI 感处理，使图片更真实（参考自 gpt-image2-ecommerce）：

#### 9.1 触发场景
- **UGC 买家秀** — 用户自拍/生活场景
- **直播间场景** — 真人直播背景
- **社交媒体** — 小红书/Instagram/TikTok 帖
- **使用场景** — 真实使用环境

#### 9.2 反 AI 处理规则

```
规则 1：指定具体型号
   ❌ 不要: "a smartphone"
   ✅ 要用: "iPhone 14 Pro, slightly dusty camera module"

规则 2：增加可见瑕疵
   ❌ 不要: "perfect, smooth, flawless"
   ✅ 要用: "visible pores, slight noise, warm color cast, imperfect framing"

规则 3：真实环境描述
   ❌ 不要: "minimal white studio"
   ✅ 要用: "real environment, slightly messy, water stains, used towel on counter"

规则 4：胶片质感参考
   ❌ 不要: "hyper-realistic, professional photography"
   ✅ 要用: "Kodak Portra 400 color feel, natural grain, NOT retouched"

规则 5：避免 AI 签名词
   ❌ 不要: perfect, flawless, stunning, hyper-realistic, ethereal
   ✅ 要用: real, natural, candid, everyday, lived-in, unposed

规则 6：不完美构图
   ❌ 不要: perfectly centered, symmetrical
   ✅ 要用: slightly off-center, taken in a hurry, casual framing
```

### 10. 水印自动检测与处理（增强版）

#### 10.1 水印检测策略
1. **EXIF/元数据检测** — 读取图片 EXIF 元数据，检测 Gemini / AI 生成水印标记
2. **视觉锚点检测** — 基于已知水印目录（Gemini 右下角半透明LOGO、Midjourney 左下角文字等）进行位置搜索
3. **本地锚点搜索** — 在图片已知区域（右下/左下/中心）检测半透明叠加层

#### 10.2 水印去除算法选择

| 水印类型 | 推荐方案 | 原理 |
|---------|---------|------|
| AI 生成水印（Gemini等） | **Reverse Alpha Blending** | 数学精确的 Alpha 反向混合，无损还原原始像素，参考 GargantuaX/gemini-watermark-remover |
| 传统高频水印 | **LaMa Inpainting + OpenCV** | 基于深度学习的修复方案，参考 D-Ogi/WatermarkRemover-AI |
| 半透明叠加文字 | **LaMa** | 图像补全，基于周围像素推算 |
| 视频水印 | **帧级 Reverse Alpha Blending** | 逐帧处理，利用时间冗余做跨帧修复 |

#### 10.3 去水印流程
```
检测到水印
  ├─ → AI水印 → Reverse Alpha Blending → 校验质量 → 通过则完成
  ├─ → 传统水印 → LaMa Inpainting → 校验质量 → 通过则完成
  └─ → 处理失败 → 提示用户手动处理或更换工具
```

#### 10.4 参考开源工具
- **AI 水印**: [GargantuaX/gemini-watermark-remover](https://github.com/GargantuaX/gemini-watermark-remover) (4.9k⭐) — CLI + SDK + Chrome Ext
- **通用水印**: [D-Ogi/WatermarkRemover-AI](https://github.com/D-Ogi/WatermarkRemover-AI) (1.5k⭐) — 图片/视频
- **批处理**: [jferments/watermark_remover](https://github.com/jferments/watermark_remover) (46⭐) — 多 GPU 批量

### 11. 参考图一致性方案

为保持品牌和产品外观一致性，支持传入参考图（吸取自 gpt-image2-ecommerce 的模式）：

#### 11.1 参考图类型
- **产品白底图** — 传入产品白底/透明图，AI 在各场景中保持产品外观一致
- **风格参考图** — 传入想要的视觉风格参考，AI 模仿整体氛围
- **场景参考图** — 传入布局/构图参考

#### 11.2 调用方式
```bash
# Codex CLI 带参考图（参考 gpt-image2-ecommerce 的 --image 模式）
codex exec --ephemeral --image /path/to/product.png <<< "Use imagegen to create..."
```

### 12. Excel 驱动模式（可选增强工作流）

当用户提供商品 Excel 表格时，启用此模式（参考自 Ozon-Profit-Skills 的设计）：

#### 12.1 Excel 输入规范
| 列 | 内容 | 用户填写 |
|----|------|---------|
| A | 商品名称（中文） | ✅ 用户填 |
| B | 商品规格 | ✅ 用户填 |
| C | 商品卖点 | ✅ 用户填 |
| D | 商品图片URL | ✅ 用户填（可选） |
| E | Prompt 生成方式 | ✅ 用户选（1=自定义模版/2=参考图反推/3=竞品模仿） |

#### 12.2 输出列
| 列 | 内容 | AI 生成 |
|----|------|---------|
| F | 优化后标题（目标语言） | ✅ 自动生成 |
| G | 商品描述（目标语言） | ✅ 自动生成，上目标语言下中文对照 |
| H | SEO Tags | ✅ 按平台规则生成 |
| I | 图片生成 Prompt | ✅ 合并商品信息后生成 |

#### 12.3 增量处理原则
- 只处理新增或修改的行，已生成内容不重复覆盖
- 通过检测输入列是否更新来判断哪些行需重新处理
- 保留用户填写的内容不变，只覆盖生成区

### 13. 图片 Prompt 工程化

每张图的 prompt 必须包含以下结构：
1. **场景描述**（产品位置、视角、环境）
2. **材质/光照**（纹理、光源方向、氛围）
3. **文字层**（标题、副标题、规格信息的位置和内容）
4. **风格锚点**（所选风格的完整锚点字符串）
5. **反AI处理**（UGC/社媒场景应用第9节规则）
6. **参考图**（如有，标记传入）
7. **禁止项**（跨境模式附加）

#### Prompt 编写通用原则
- **简洁为王**：只传核心信息，不过度约束（gpt-image2-ecommerce 信条）
- **自然语言优先**：描述性句子优于关键词堆砌
- **材质描述**：明确写出纹理（磨砂玻璃、拉丝金属、哑光质感）
- **光照很重要**：始终包含光照方向和质感
- **善用参考图**：传入产品图可显著提升一致性

### 14. 风格变体系统

每个设计风格可提供多种变体选择（参考自 gpt-image2-ecommerce 的4变体设计）：

- **Variant 1** — 产品主视觉（标准版，产品占主导）
- **Variant 2** — 动态场景感（加入运动/使用元素）
- **Variant 3** — 三联画/信息分层（并列多个信息面）
- **Variant 4** — 氛围感/情绪版（偏重情绪和氛围）

在 Prompt 中通过 `variant` 字段指定。

### 15. 自检与迭代
- 生成图片后必须 self-check
  - 文字是否正确（拼写、大小写）
  - 风格是否一致
  - 是否有中文字样（跨境模式）
  - 是否有逻辑错误（尺寸/型号对应）
  - 卖点是否清晰传达
  - 所选风格是否与品类匹配
  - 水印是否完全清除
- 发现问题后自动微调生成
- 迭代次数不超过 3 次

### 16. 平台适配规则

| 平台 | 语言 | 标题限制 | Tags 规则 | 图片要求 |
|------|------|---------|----------|---------|
| Amazon | 英语/本地化 | ≤200字符 | 后端 Search Term | 纯白底主图 |
| Shopee | 英语/本地化 | ≤120字符 | #标签 15个以内 | 多角度展示 |
| Lazada | 英语/本地化 | ≤200字符 | 关键词标签 | 6-8张 |
| TikTok Shop | 英语/本地化 | ≤100字符 | #兴趣标签 | 竖版9:16 |
| Ozon | 俄语/本地化 | ≤1000字符 | #30个俄语标签 | 白底+场景 |
| AliExpress | 英语/本地化 | ≤128字符 | 后端关键词 | 纯白底主图 |

## 完整工作流程

### Step 1: 输入接收
接收用户输入：商品图片文件路径 + 商品标题/描述文字（如有）

### Step 2: 主体识别
- 分析所有输入图片，识别商品主体
- 判断品类、材质、风格、规格
- 如无法确定 → 请求用户确认商品主体是什么

### Step 3: 模式判断
- 检测是否触发跨境模式条件
- 锁定语言和视觉限制
- 判断是否启用 Excel 驱动模式

### Step 4: 搜索成熟方案
- 搜索该品类在 Amazon/Shopify/跨境平台的标题和图片优化方案
- 整理关键词策略
- 搜索网络上该品类大卖的 listing 分析

### Step 5: 原图诊断
- 检测水印（按第10节策略）
- 检查逻辑错误
- 评估设计质量和风格一致性

### Step 6: 水印处理（如需）
- 按水印类型选择合适算法
- 调用去水印工具
- 验证去水印质量（迭代≤3次）

### Step 7: 标题优化
- 按跨境/国内模式输出优化后的标题
- 确保嵌入 5-7 个搜索关键词
- 标题结构符合公式
- 按平台适配规则调整长度和风格

### Step 8: Prompt 模式选择
- 用户是否提供了自定义模版？（模式 A）
- 用户是否提供了参考图？（模式 B）
- 用户是否提供了竞品链接？（模式 C）
- 默认模式 → 按标准 6 图结构生成

### Step 9: 设计风格决策
- 按设计风格智能匹配系统选择最佳风格
- 参考品类→风格映射表
- 执行风格选择检查清单
- 选择风格变体

### Step 10: 轮播图方案设计
- 按标准 6 图结构设计每张图的视觉方案
- 每张图写完整 prompt（含所选风格锚点 + 反AI处理 + 参考图 + 风格变体）
- 统一风格规范贯穿全部图片

### Step 11: 自检
- 文字正确性/风格一致性/合规检查/水印检查
- 如有问题 → 微调后重新生成（≤3次）

### Step 12: 输出 / 生图
- 输出优化后标题（中/英文双版本）
- 输出 6 张图 prompt
- 如有 image_gen/imagegen 能力 → 按顺序生成图片
- 清理临时文件
- 交付最终结果

## 脚本

安装依赖脚本（Python 去水印等）：

```bash
# 传统水印去除基于 OpenCV
pip install opencv-python pillow numpy
```

## 参考资源

- `references/amazon-listing-best-practices.md` — Amazon Listing 优化最佳实践
- `references/prompt-templates.md` — Prompt 模板库
- `references/carousel-design-spec.md` — 轮播图设计规范（含流行方案库和品类映射决策系统）
- `references/external-insights.md` — 外部项目吸收分析报告

## 代理元数据

对应的 agents/openai.yaml 文件提供了 UI 层面的技能描述和触发提示。
