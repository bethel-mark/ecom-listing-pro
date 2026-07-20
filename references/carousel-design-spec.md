# 轮播图设计规范 v2 — 流行设计方案库 + 智能匹配决策系统

---

## 第一部分：设计风格决策树

选择设计风格时，**禁止硬套单一风格**。必须按以下决策树逐步判定：

```
Step 1: 确认商品主体品类 / 材质 / 目标人群
Step 2: 检查玻璃拟态+等距3D方案是否匹配大众审美
Step 3: 若不匹配 → 从风格库中选用与商品主体最匹配的流行方案
Step 4: 确定后，风格规范必须贯穿全部6张轮播图（禁止混搭）
```

### 决策流程图

```
[商品主体识别]
     ↓
┌──────────────────────────────────────────┐
│ 品类判定:                                │
│ 天然材质(木/竹/石/麻) → 推荐玻璃拟态+3D  │
│ 电子产品/科技 → 推荐极简/Futuristic      │
│ 食品/美妆 → 推荐拟真摄影/自然风格        │
│ 潮玩/游戏 → 推荐赛博/Clay/插画           │
│ 传统工艺/复古 → 推荐手绘/Vintage          │
│ 时尚/配饰 → 推荐极简/Cinematic            │
│ 母婴/儿童 → 推荐软3D Clay/柔和插画       │
└──────────────────────────────────────────┘
     ↓
[参考该品类 Amazon Best Seller 主流风格]
     ↓
[参考该品类 Temu/Shein/TikTok 热卖风格]
     ↓
[综合判断 → 输出选定方案]
     ↓
[统一风格规范贯穿 6 图]
```

---

## 第二部分：流行电商设计风格库

### Style A — 玻璃拟态 + 等距3D + 软3D（主推风格）
**适用场景：天然材质、手工制品、乐器、精品厨房用具、饰品**

| 属性 | 规范 |
|------|------|
| 视觉语言 | Frosted glass panels, backdrop-filter blur(20px), isometric 30°/15° angle |
| 产品呈现 | 悬浮玻璃台上，2层柔影+1层地面反光，产品占55-60% |
| 色板 | 暖木色系 #F4E3C8 / #D6A972 / #7A4A24（材质自适配） |
| 玻璃层 | rgba(255,255,255,0.18) + 1px 高光 rgba(255,255,255,0.6) |
| 背景 | 暖灰→深炭 #1A1A22 渐变 |
| 圆角 | 16/24/32px 三档 |
| 投影 | 近层 0 8px 24px rgba(0,0,0,0.18) + 远层 0 24px 48px rgba(0,0,0,0.10) |
| 字体 | Bold Sans 标题 / Light Condensed 规格 / Tabular 数字 |
| 适合品类 | 枫木鼓棒(已验证)、竹制品、手工陶瓷、胡桃木家具、单板乐器、天然皂 |

**参考案例：** [Amazon: Vic Firth drumsticks](https://www.amazon.com/Vic-Firth-American-Classic-Drumsticks/dp/B0002F73X0), [Etsy: Handmade wooden kitchen utensils](https://www.etsy.com/market/wooden_kitchen_utensils)

---

### Style B — 极简白底/干净科技风（Amazon 标准）
**适用场景：电子产品、数码配件、化妆品、时尚配饰、3C 产品**

| 属性 | 规范 |
|------|------|
| 视觉语言 | Pure white or light gray background, sharp product silhouette, clean sans-serif |
| 产品呈现 | 居中独立，产品占80-85%，底部极简阴影，无多余装饰 |
| 色板 | 白 #FFFFFF / 浅灰 #F5F5F7 / 品牌色点缀 |
| 阴影 | 微投影 rgba(0,0,0,0.06) 或 无投影纯白 |
| 字体 | 极细无衬线 30-40pt，字重 Light/Regular |
| 背景 | 纯白或 #F5F5F7 纯色 |
| 适合品类 | iPhone壳、蓝牙耳机、充电器、智能手表、鼠标、键盘、数据线 |

**参考案例：** [Amazon: Anker charging cable](https://www.amazon.com/Anker-Charging-Cable-PowerLine-MacBook/dp/B0BXN3QKP5), [Shopify: Standard product pages](https://www.shopify.com/)

---

### Style C — 赛博霓虹 / 未来科技（Futuristic Tech Editorial）
**适用场景：游戏外设、RGB 灯效产品、电竞设备、智能家居、穿戴设备**

| 属性 | 规范 |
|------|------|
| 视觉语言 | Neon gradients, dark mode, glowing edges, cyberpunk/tech editorial aesthetic |
| 产品呈现 | 倾斜 15°，浮在发光网格/粒子背景上，RGB 光效反射 |
| 色板 | 暗黑 #0A0A14 / 赛博蓝 #00D4FF / 霓虹紫 #FF00FF / 电光绿 #00FF88 |
| 字体 | Heavy Gothic 60-100pt，多用全大写 |
| 光效 | 边缘发光 2px #00D4FF，体积光从产品底部向上 |
| 适合品类 | 游戏鼠标/键盘、RGB耳机、电竞椅、智能音箱、VR设备 |

**参考案例：** [Amazon: Razer gaming mouse](https://www.amazon.com/Razer-Basilisk-Ultimate-Wireless-Gaming/dp/B07Y6L1PJB), [Alienware laptops](https://www.dell.com/en-us/gaming/alienware)

---

### Style D — 日式手绘/水彩插画风（Japanese Hand-Drawn）
**适用场景：传统工艺品、茶具、文房具、天然护肤品、禅意生活方式**

| 属性 | 规范 |
|------|------|
| 视觉语言 | Hand-drawn brush strokes, watercolor textures, washi paper background, asymmetrical composition |
| 产品呈现 | 融入插画场景中，非完全居中，留有大量留白 |
| 色板 | 和纸白 #F5F0E8 / 墨黑 #2A2520 / 朱红 #C43A31 / 抹茶绿 #7B9E6D |
| 字体 | 手写感衬线/毛笔体 40-60pt |
| 纹理 | 水彩晕染、铅笔素描纹理、宣纸底纹 |
| 适合品类 | 抹茶碗、香道、书法用品、和风包装、玉石首饰 |

**参考案例：** [Etsy: Japanese ceramics](https://www.etsy.com/market/japanese_ceramics), [Muji packaging](https://www.muji.com/)

---

### Style E — 软3D 黏土/玩偶风（Soft 3D Clay）
**适用场景：儿童产品、玩具、宠物用品、有机食品、可爱风生活用品**

| 属性 | 规范 |
|------|------|
| 视觉语言 | Soft rounded shapes, clay-like texture, pastel palette, playful lighting |
| 产品呈现 | 像黏土模型一样圆润可爱，无锋利棱角 |
| 色板 | 马卡龙色系 #FFD1DC / #B5EAD7 / #C7CEEA / #FFDAC1 |
| 字体 | 圆体/手写风 40-80pt |
| 光照 | 全局漫射柔光，无硬阴影 |
| 适合品类 | 儿童水杯、毛绒玩具、婴儿围兜、有机零食、可爱文具 |

**参考案例：** [Temu: Kids products](https://www.temu.com/), [Shein: Cute stationery](https://www.shein.com/)

---

### Style F — 杂志风/拟真摄影（Editorial / Cinematic）
**适用场景：食品饮料、高端酒类、香水、奢侈手表、美妆**

| 属性 | 规范 |
|------|------|
| 视觉语言 | Film-grain, shallow depth of field, dramatic rim lighting, editorial layout |
| 产品呈现 | 搭配道具场景（食物配食材/香水配花），45° 俯拍或平视 |
| 色板 | 深暖调 #2A1F1A / 金色 #C9A96E / 奶油 #FFF8E7 |
| 字体 | Serif 衬线 50-70pt，优雅字距 |
| 光照 | 侧逆光，暖调，暗角效果 |
| 适合品类 | 葡萄酒、巧克力、高端面霜、古董表、手工皮革包 |

**参考案例：** [Shopify: Luxury brands](https://www.shopify.com/enterprise/luxury-ecommerce), [Amazon: Premium beauty](https://www.amazon.com/beauty)

---

### Style G — 复古/做旧风（Vintage / Retro）
**适用场景：黑胶唱片、古着、复刻眼镜、工业风家具、怀旧食品包装**

| 属性 | 规范 |
|------|------|
| 视觉语言 | Desaturated tones, grain texture, halftone dots, retro typography, aged paper |
| 产品呈现 | 放置在复古场景中（旧木桌/铁皮柜），暖调灯光 |
| 色板 | 旧纸黄 #E8D5B7 / 铜锈绿 #4A6B5D / 铁锈红 #8B3A2F |
| 字体 | 衬线/复古手写 50-80pt |
| 纹理 | 颗粒感、划痕纹理、褪色效果 |
| 适合品类 | 黑胶唱机、复古墨镜、老式收音机、做旧皮靴、古着 |

**参考案例：** [Etsy: Vintage](https://www.etsy.com/c/vintage), [Urban Outfitters: Retro collection](https://www.urbanoutfitters.com/)

---

### Style H — 自然/植物系（Nature / Botanical）
**适用场景：护肤品、精油、茶叶、有机食品、植物盆器、户外用品**

| 属性 | 规范 |
|------|------|
| 视觉语言 | Botanical motifs, organic shapes, diffused natural light, green accents |
| 产品呈现 | 与植物/自然元素组合，平铺或俯拍 |
| 色板 | 薄荷绿 #A8D5BA / 大地棕 #8B7355 / 米白 #F5F0E1 |
| 字体 | 细衬线/手写 30-50pt，柔和字距 |
| 光照 | 自然漫射光，柔和温暖 |
| 适合品类 | 精油、手工皂、花草茶、竹纤维毛巾、帆布包 |

**参考案例：** [Etsy: Natural soap](https://www.etsy.com/market/natural_soap), [Lush packaging](https://www.lush.com/)

---

## 第三部分：品类→风格快速映射表

| 品类 | 首选风格 | 备选风格 | 特别限制 |
|------|---------|---------|---------|
| 🥁 乐器（鼓棒/吉他拨片） | **Style A 玻璃+等距3D** | Style C Futuristic | 保留天然木纹，禁写实手指 |
| 🎧 耳机/音响 | **Style B 极简白底** | Style C 赛博霓虹 | 无线产品注意角度 |
| ⌚ 手表/配饰 | **Style F Cinematic** | Style B 极简 | 表盘细节必须清晰 |
| 📱 手机配件 | **Style B 极简白底** | Style C 科技 | 符合 Amazon 纯白底要求 |
| 🎮 游戏外设 | **Style C 赛博霓虹** | Style B + 发光 | RGB 效果可做卖点 |
| 🍵 茶具/陶瓷 | **Style D 日式手绘** | Style A 玻璃拟态 | 保留手作质感 |
| 🧴 护肤品/精油 | **Style H 自然植物** | Style F Cinematic | 天然成分视觉化 |
| 🧸 儿童产品/玩具 | **Style E 软3D Clay** | Style G 复古 | 色彩鲜艳，形状圆润 |
| 🍷 酒类/食品 | **Style F Cinematic** | Style H 自然 | 强调食材原料，暖调光 |
| 👗 时尚/衣物 | **Style B 极简** | Style F 杂志 | 无模特特写（跨境） |
| 🪵 木制家具/家居 | **Style A 玻璃+等距3D** | Style G 复古 | 突出木纹和工艺 |
| 🏋️ 健身/运动器材 | **Style B 极简白底** | Style C 科技 | 强调人体工学 |
| 🖋️ 文具/办公 | **Style D 日式手绘** | Style E 软3D | 北欧 vs 和风选择 |
| 💄 美妆/彩妆 | **Style F Cinematic** | Style B 极简 | 禁止写实嘴唇特写（跨境） |

---

## 第四部分：行业 Top 100 电商设计趋势（2025-2026）

参考自：Amazon Best Sellers, Etsy Trending, Pinterest Business, TikTok Shop

| 排名 | 趋势 | 占比 | 适用品类 |
|------|------|------|---------|
| 1 | 纯白背景质感阴影 | 28% | 全品类（Amazon 标准） |
| 2 | 玻璃拟态信息卡 | 18% | 乐器、家居、天然制品 |
| 3 | 渐变科技背景 + 发光 | 15% | 数码、游戏、智能 |
| 4 | 自然光俯拍平铺 | 12% | 美妆、食品、有机 |
| 5 | 极简衬线杂志风 | 10% | 奢侈品、高端个护 |
| 6 | 等距3D悬浮布局 | 8% | 工具箱、套装产品 |
| 7 | 手绘插画包装风 | 5% | 手工、食品、母婴 |
| 8 | 复古胶片颗粒 | 3% | 服饰、生活方式 |
| 9 | 赛博霓虹线条 | 1% | 电竞、科技新品 |

---

## 第五部分：信息层级（通用）

### 视觉注意力分配（6张轮播图标准）
- 图1 主图：产品 55-60% + 情感大标题 20% + 品牌/标签 10%
- 图2 规格：产品 40% + 信息卡 35% + 尺寸标注 15%
- 图3 材质：材质特写 60% + 文字介绍 25%
- 图4 卖点：图标卡片 70% + 标题 15%
- 图5 场景：场景 50% + 产品 25% + 标签 10%
- 图6 情感：产品+包装 45% + 情感文案 30%

### 安全区域（全部风格通用）
- 1:1 方图，核心内容保持在 90% 居中区域
- 边距保留 5% 呼吸空间
- 文字不要紧贴边缘

### 网格系统
- 信息卡标准尺寸：宽占画面 70-80%，高按内容调整
- 多图对比时使用 50/50 或 60/40 分割
- 卖点网格使用 2×2 或 3 列等宽
- 场景三联使用 33/33/33 等宽分割

## 第六部分：字体系统（通用）

### 跨境模式
| 层级 | 字体 | 字号 |
|------|------|------|
| 主标题 | Bold Sans | 80-120pt |
| 副标题 | SemiBold Sans | 40-60pt |
| 规格文字 | Light Condensed | 20-30pt |
| 数字 | Tabular | 同规格字号 |
| 小标签 | Regular | 16-20pt |

### 国内模式
| 层级 | 字体 | 字号 |
|------|------|------|
| 主标题 | 粗体无衬线 | 60-80pt |
| 副标题 | 中等线体 | 30-40pt |
| 规格 | 细体 | 16-24pt |

---

## 第七部分：风格选择检查清单

每次选择风格前，逐项确认：

- [ ] 1. 这个风格在该品类的 Top 100 卖家中存在 ≥3 个对标案例？
- [ ] 2. 选择此风格是否符合大众审美（而非个人偏好）？
- [ ] 3. 此风格是否与商品材质/气质一致？
- [ ] 4. 跨境模式下，此风格是否无中文/人像/价格问题？
- [ ] 5. 选定后能否在 6 张图中保持一致？
- [ ] 6. 是否参考了至少 2 个同类大卖的实际 listing？
- [ ] 7. 最终方案是否比原图有明显提升？

> ✅ 全部通过 → 执行
> ❌ 任一不通过 → 退回重新选择
