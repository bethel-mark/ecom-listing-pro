# 外部项目吸收分析报告

> 对三个相关开源项目的深度分析，提取可吸收的能力，完善 ecom-listing-pro 技能

---

## 项目 1：GargantuaX/gemini-watermark-remover ⭐4953

**项目地址：** https://github.com/GargantuaX/gemini-watermark-remover

### 可吸收的核心能力

| 能力 | 说明 | 吸收方式 |
|------|------|---------|
| **Reverse Alpha Blending** | 数学精确的去水印公式，非 AI inpainting | 在 skill 水印章节增加算法选择建议 |
| **自动水印检测机制** | Gemini 已知输出目录 + 本地锚点搜索 | 作为参考方案加入文档 |
| **SDK 化封装** | createWatermarkEngine() 重用 alpha 缓存，批量处理性能优化 | 在设计 API 时参考 |
| **多形态交付** | Online / Chrome Ext / Userscript / CLI / Skill / SDK | 参考扩展模式 |
| **视频水印去除** | 支持视频帧级去除 | 作为扩展方向 |
| **防指纹干扰提示** | Canvas Fingerprint Defender 兼容性检查 | 加入处理环境检查清单 |
| **CLI 批处理** | gwr.mjs remove <input> --output <file> | 参考设计脚本化工作流 |

### 对我 skill 的价值 ★★★★☆

核心价值在于**水印去除的精确算法策略**，可直接引用作为技术方案备选。

---

## 项目 2：coral870921-source/Ozon-Profit-Skills ⭐12

**项目地址：** https://github.com/coral870921-source/Ozon-Profit-Skills

### 可吸收的核心能力

| 能力 | 说明 | 吸收方式 |
|------|------|---------|
| **Excel 驱动工作流** | 填中文→AI自动翻译/生成/回写，增量处理不重复覆盖 | 新增 Excel 驱动模式 |
| **三种图片 Prompt 模式** | 自定义模版 / 参考图反推 / 竞品首图模仿 | 加入 prompt 模式章节 |
| **多平台适配** | Ozon / TikTok Shop / Amazon / AliExpress / Shopee | 加入平台适配章节 |
| **增量处理机制** | 只处理新增或修改的行，已生成不重复覆盖 | 加入工作流处理原则 |
| **SEO Tag 生成规则** | 按平台规则生成合规标签，禁止营销词 | 作为标题优化补充 |
| **三列输出结构** | 上目标语言下中文对照 | 对比原有双语方案 |
| **用户可配置模版** | 图片 Prompt 模版完全由用户自定义 | 新增"用户模版"模式 |
| **Claude Code Command** | 以 /command 触发 | 参考设计 CLI 触发方式 |

### 对我 skill 的价值 ★★★★★

核心价值在于**Excel 驱动的跨境电商自动化工作流**，这是非常实用的模式，用户只需填中文 Excel 即可。

---

## 项目 3：buluslan/gpt-image2-ecommerce ⭐229

**项目地址：** https://github.com/buluslan/gpt-image2-ecommerce

### 可吸收的核心能力

| 能力 | 说明 | 吸收方式 |
|------|------|---------|
| **25 个电商场景模板** | 白底/场景/平铺/微距/海报/社交媒体/UGC/模特/对比/包装/信息图等 | 新增场景模板分类 |
| **智能模板匹配** | 自然语言→自动匹配最佳模板 | 改善 prompt 组合逻辑 |
| **参考图一致性** | --image 传入产品图保持一致性 | 加入参考图章节 |
| **反 AI 感处理** | CCD 胶片质感/可见瑕疵/不完美构图 | 新增反AI感处理章节 |
| **4 种风格变体** | 每场景 4 种 style variant | 加入风格变体系统 |
| **HTTP 服务模式** | curl POST 调用替代 CLI | 增加可选调用模式 |
| **Prompt 编写原则** | 简洁为王/自然语言优先/材质描述 | 整合到 Prompt 工程化章节 |
| **模板 JSON 结构化** | 每模板含 keywords/trigger_phrases/variants | 参考设计 JSON 结构 |
| **结果清理机制** | 自动清理临时文件 | 加入工作流清理步骤 |
| **多 Agent 兼容** | Claude Code / OpenClaw / Cursor / Windsurf | 扩展兼容说明 |

### 对我 skill 的价值 ★★★★★

核心价值在于**25 个电商场景的模板分类 + 风格变体 + 反 AI 感处理**，直接提升图片生成的多样性和真实感。

---

## 综合吸收清单

### 立即吸收到 SKILL.md 的内容

- [ ] **1. 新增「Prompt 生成模式」章节** — 自定义模版 / 参考图反推 / 竞品首图模仿
- [ ] **2. 新增「25 场景模板触发词」映射表** — 白底/场景/微距/社交媒体/UGC/等
- [ ] **3. 新增「反 AI 感处理」章节** — UGC/直播间/社媒场景 CCD 质感
- [ ] **4. 新增「水印去除算法策略」** — Reverse Alpha Blending / LaMa / 自动检测
- [ ] **5. 新增「Excel 驱动模式」选项** — 填中文→自动多列生成
- [ ] **6. 新增「平台适配」章节** — Amazon / Shopee / Lazada / Ozon / TikTok Shop
- [ ] **7. 新增「风格变体系统」** — 每场景多种变体可选
- [ ] **8. 新增「增量处理原则」** — 避免重复工作
- [ ] **9. 新增「参考图一致性」方案** — 传入白底图保品牌一致
- [ ] **10. 新增「HTTP 服务模式」** — 可选 CLI 或 HTTP 调用

### 储备到 references/ 目录

- [ ] **external-insights.md** — 本文件（已完成）
- [ ] **scene-templates/目录** — 25 场景 JSON 模板（借鉴 gpt-image2-ecommerce）
- [ ] **platform-rules/目录** — 多平台标题/Tag 规则（借鉴 Ozon-Profit-Skills）
