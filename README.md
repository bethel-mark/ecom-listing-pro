# 🛒 Ecom Listing Pro — 跨境电商图片与标题智能优化 Skill

> **一款 Codex Skill，专为跨境电商/国内电商的商品标题优化和轮播图设计而生。上传商品图即自动诊断、优化、生成，一站式交付可上架素材。**

---

## ✨ 核心功能

| 功能 | 说明 |
|------|------|
| 🔍 **智能主体识别** | 自动分析商品图片识别品类/材质/风格，无法确定时主动询问用户 |
| 🏷️ **标题优化** | 基于成熟电商标题公式重写爆款标题，跨境模式自动去除中文和促销字眼 |
| 🖼️ **轮播图设计** | 按标准6图结构（主图/规格/材质/卖点/场景/情感）输出设计+prompt |
| 🎨 **统一风格规范** | 玻璃拟态/等距3D/软3D 风格拉齐，色板/字体/布局全规范 |
| 💧 **水印自动检测** | 识别图片水印类型，自动调用去水印方案 |
| ✅ **Self-Check** | 生成后自动检查文字正确、风格一致、逻辑无错、合规无汉 |
| 🌐 **双模式感知** | 自动判断国内模式（可中文）vs 跨境模式（禁中文/人脸/促销） |

## 📦 安装

```bash
# 通过 skill-installer 安装
codex skills install ecom-listing-pro
```

## 🚀 使用流程

1. **上传商品图片** — 提供至少1张商品图（轮播图越多诊断越准）
2. **提供标题**（可选）— 提供现有标题有助于分析
3. **等待分析** — 系统自动完成：主体识别 → 模式判定 → 方案搜索 → 原图诊断 → 水印处理
4. **确认主体** — 无法确定时会主动询问
5. **接收优化结果** — 优化标题 + 6张轮播图 prompt + 可选生图

## 🧠 技术亮点

- **标题 Formula**: 情感钩子 + 核心材质/特征 + 品类关键词 + 规格 + 场景/用途 + 信任锚点
- **6图叙事结构**: Hero → Size → Material → Features → Use Cases → Gift/Heritage
- **风格规范**: 玻璃拟态(backdrop-filter blur) + 等距3D(isometric) + 软3D(soft volumetric)

## 🗂️ 项目结构

```
ecom-listing-pro/
├── SKILL.md                    # 主技能文件（入口）
├── README.md                   # 本文件
├── agents/
│   └── openai.yaml            # UI元数据
├── scripts/                   # 工具脚本（WIP）
├── references/                # 参考文档
│   ├── amazon-listing-best-practices.md
│   ├── carousel-design-spec.md
│   └── prompt-templates.md
└── assets/                    # 模板资源（WIP）
```

## 🔗 相关项目

- [gpt-image2-ecommerce](https://github.com/buluslan/gpt-image2-ecommerce) (229⭐) — GPT-Image-2 电商素材生成
- [Ozon-Profit-Skills](https://github.com/coral870921-source/Ozon-Profit-Skills) (12⭐) — 跨境电商自动化
- [gemini-watermark-remover](https://github.com/GargantuaX/gemini-watermark-remover) (4.9k⭐) — AI水印去除
- [ecom-title-optimizer](https://github.com/haichen88188-blip/ecom-title-optimizer) — 标题优化工具

## 📄 许可证

MIT License

---

**Made for Codex — 让每一个商品 listing 都成为爆款。**
