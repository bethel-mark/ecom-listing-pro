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

### 7. 统一设计风格规范

#### 色板
- 暖木色系（枫木/橡木/胡桃木通用）：`#F4E3C8 / #D6A972 / #7A4A24`
- 冷科技色系（电子产品）：`#E8F0FE / #4A90D9 / #1A2332`
- 通用玻璃层：`rgba(255,255,255,0.18)` + 1px 高光 `rgba(255,255,255,0.6)`
- 背景渐变：暖灰→深炭 `#1A1A22` 或 白→浅灰 `#F5F5F7`
- 强调色：`#3FA9F5`（≤5%面积）
- 字体色：`#FFFFFF`（深底）/ `#1A1A22`（浅底），规格文 `#5A5A66`

#### 玻璃拟态规范
- 圆角：16/24/32px 三档，根据信息层级选择
- backdrop-filter: blur(20px)
- 投影：近层 `0 8px 24px rgba(0,0,0,0.18)` + 远层 `0 24px 48px rgba(0,0,0,0.10)`

#### 3D 规范
- 主图视角 30°/15° 等距，产品占画面 55-60%
- 棒身/产品保留材质纹理 + 柔光（无硬反射）
- 悬浮感：2层柔影 + 1层地面反光
- 字体：Bold Sans（标题）/ Light Condensed（规格）/ Tabular（数字）

#### 禁止项（跨境模式）
- ❌ 任何中文
- ❌ 价格 / SALE / Free Shipping
- ❌ 写实人脸/手部特写
- ❌ 过曝炫光、写实摄影贴片

### 8. 水印自动检测与处理
- 读取图片 EXIF/元数据，检测 AI 生成水印
- 视觉分析图片中是否有可见水印（半透明文字/Logo）
- 发现水印时自动调用去水印工具
- 传统水印推荐：基于 LaMa 的修复方案
- AI水印推荐：反向 Alpha 混合算法
- 去水印后检查质量，如有残留则手动修复

### 9. 图片 Prompt 工程化

每张图的 prompt 必须包含以下结构：
1. **场景描述**（产品位置、视角、环境）
2. **材质/光照**（纹理、光源方向、氛围）
3. **文字层**（标题、副标题、规格信息的位置和内容）
4. **风格锚点**（玻璃拟态 / 等距3D / 软3D 统一风格）
5. **禁止项**（跨境模式附加）

### 10. 自检与迭代
- 生成图片后必须 self-check
  - 文字是否正确（拼写、大小写）
  - 风格是否一致
  - 是否有中文字样（跨境模式）
  - 是否有逻辑错误（尺寸/型号对应）
  - 卖点是否清晰传达
- 发现问题后自动微调生成
- 迭代次数不超过 3 次

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

### Step 4: 搜索成熟方案
- 搜索该品类在 Amazon/Shopify/跨境平台的标题和图片优化方案
- 整理关键词策略
- 搜索网络上该品类大卖的 listing 分析

### Step 5: 原图诊断
- 检测水印
- 检查逻辑错误
- 评估设计质量和风格一致性

### Step 6: 水印处理（如需）
- 调用去水印工具
- 验证去水印质量

### Step 7: 标题优化
- 按跨境/国内模式输出优化后的标题
- 确保嵌入 5-7 个搜索关键词
- 标题结构符合公式

### Step 8: 轮播图方案设计
- 按标准 6 图结构设计每张图的视觉方案
- 每张图写完整 prompt
- 统一风格规范

### Step 9: 输出 / 生图
- 输出优化后标题（中/英文双版本）
- 输出 6 张图 prompt
- 如有 image_gen/imagegen 能力 → 按顺序生成图片
- 每生成一张后 self-check
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
- `references/carousel-design-spec.md` — 轮播图设计规范

## 代理元数据

对应的 agents/openai.yaml 文件提供了 UI 层面的技能描述和触发提示。
