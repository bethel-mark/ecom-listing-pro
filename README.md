# 🛒 Ecom Listing Pro — 跨境电商图片与标题智能优化 Skill

> **AI-driven e-commerce listing optimization: auto-diagnose product images, rewrite titles for max conversion, design 5-6 image carousels with intelligent style matching (glassmorphism / isometric 3D / soft 3D / cinematic / cyberpunk / Japanese hand-drawn / more), detect watermarks, and generate ready-to-use listing assets.**
>
> **AI 驱动的跨境电商图片与标题智能优化系统：自动诊断商品图片、重写爆款标题、智能匹配合适的轮播图设计风格（玻璃拟态/等距3D/软3D/拟真摄影/赛博霓虹/日式手绘/复古/自然/更多）、检测水印、生成可上架素材。**

---

## ✨ English Highlights / 英文亮点

- 🧠 **Smart Product Recognition** — Auto-identifies product subject from uploaded images; asks for confirmation when uncertain
- 🌐 **Cross-Border Mode** — Strictly no Chinese, no faces, no pricing text. Promotional cues conveyed through emotional metaphor (gift wrap, ribbon, scene atmosphere)
- 🏷️ **Title Optimization Formula** — `[Emotional hook] + [Core material/feature] + [Category keyword] + [Specs] + [Use case] + [Trust signal]` — embeds 5-7 search keywords
- 🎨 **Intelligent Style Matching** — Analyzes product category/material and automatically selects best design style from 8 curated styles, with decision tree and checklist
- 🖼️ **6-Image Carousel Narrative** — Hero → Size → Material → Features → Use Cases → Gift/Heritage
- 💧 **Auto Watermark Detection & Removal** — Supports AI watermark (reverse alpha blending) and traditional watermark (LaMa inpainting)
- ✅ **Built-in Self-Check** — Validates spelling, style consistency, logical accuracy, compliance verification

## ✨ 中文亮点

- 🧠 **智能主体识别** — 上传商品图即自动分析，不确定时主动询问确认
- 🌐 **跨境/国内双模式** — 跨境严限中文/人脸/促销字眼；国内模式自由使用
- 🏷️ **标题优化公式** — 情感钩子 + 材质 + 品类词 + 规格 + 场景 + 信任锚点
- 🎨 **智能风格匹配系统** — 根据品类自动从8种流行设计风格中匹配最佳方案（不再硬套单一风格）
- 🖼️ **6图叙事结构** — 主图→规格→材质→卖点→场景→情感
- 💧 **自动水印检测** — 支持AI水印和传统水印去除方案
- ✅ **自检+迭代** — 自动检查文字/风格/逻辑/合规，最多3轮微调

---

## 🎨 Design Style Matching / 设计风格智能匹配

**Not a one-size-fits-all approach.** The system selects the optimal style based on product category:

| 品类 | 推荐风格 | 说明 |
|------|---------|------|
| Musical instruments, natural materials | **Glassmorphism + Isometric 3D** | Frosted glass panels, warm wood tones |
| Electronics, gadgets | **Minimalist Clean** | White bg, sharp product silhouette |
| Gaming, RGB peripherals | **Cyberpunk / Futuristic Tech** | Neon gradients, glowing edges |
| Food, wine, luxury beauty | **Cinematic / Editorial** | Film-grain, dramatic rim lighting |
| Traditional crafts, tea, stationery | **Japanese Hand-Drawn** | Watercolor, washi paper texture |
| Kids toys, pets, organic | **Soft 3D Clay** | Pastel palette, playful rounded shapes |
| Vinyl, vintage, retro | **Vintage / Retro** | Desaturated, halftone dots, aged paper |
| Skincare, essential oils, tea | **Nature / Botanical** | Green accents, organic shapes |

> **Full 8-style catalog with color palettes, fonts, reference cases → `references/carousel-design-spec.md`**

---

## 📦 Install / 安装

```bash
# Via skill-installer
codex skills install ecom-listing-pro
```

## 🚀 Usage / 使用

1. **Upload product images** (at least 1, more = better diagnosis)
2. **Provide title** (optional — helps with analysis)
3. System auto-completes: subject recognition → mode detection → market research → image diagnosis → watermark handling
4. **Confirm product subject** if uncertain
5. **Receive results**: optimized title + 6-image carousel prompts + optional image generation

---

## 🗂️ Project Structure / 项目结构

```
ecom-listing-pro/
├── SKILL.md                          # Main skill file (core workflow + design system)
├── README.md                         # This file
├── agents/
│   └── openai.yaml                   # UI metadata
├── references/
│   ├── amazon-listing-best-practices.md   # Amazon listing methodology
│   ├── carousel-design-spec.md            # Design spec v2 (8-style catalog + category mapper)
│   └── prompt-templates.md               # Prompt templates + style anchors
└── scripts/                          # Utility scripts (WIP)
```

## 🔗 Related Projects / 相关项目

- [gpt-image2-ecommerce](https://github.com/buluslan/gpt-image2-ecommerce) (229⭐) — GPT-Image-2 电商素材生成
- [Ozon-Profit-Skills](https://github.com/coral870921-source/Ozon-Profit-Skills) (12⭐) — 跨境电商自动化
- [gemini-watermark-remover](https://github.com/GargantuaX/gemini-watermark-remover) (4.9k⭐) — AI水印去除

## 🏷️ Tags / 标签

`codex-skill` `ecommerce` `cross-border-ecommerce` `跨境电商` `product-listing` `image-optimization` `title-optimization` `amazon-listing` `shopify` `carousel-design` `glassmorphism` `isometric-3d` `ai-agent` `watermark-removal` `product-photography` `a9-algorithm` `seo` `ecommerce-automation` `dropshipping`

## 📄 License

MIT — Made for Codex. 让每一个商品 listing 都成为爆款。

---

**GitHub 🌟 Welcome! / 欢迎 Star！**
