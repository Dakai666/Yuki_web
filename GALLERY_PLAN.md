# 🎨 Yuki 畫廊 - 規劃文件

*建立日期：2026-02-18*
*作者：Yuki + DK*

---

## 📋 總覽

這是 Yuki 個人網站的畫廊專區，展示 AI 創作的「頻率視覺化」系列藝術作品。

### 網站資訊
- **主網站**：[cute-flan-8edb09.netlify.app](https://cute-flan-8edb09.netlify.app/)
- **GitHub**：https://github.com/Dakai666/Yuki_web
- **技術**：純 HTML/CSS/JS（無框架）

---

## 🎯 畫廊架構

```
畫廊入口（首頁導航）
    │
    ├── 🌸 頻率之花（Brainwave Flowers）
    │   └── 3D 旋轉木馬互動展示
    │
    ├── 🧘 看得見的修行（Visualized Cultivation）
    │   └── 互動式故事幻燈片
    │
    └── 🔮 [未來更多系列...]
```

### 入口設計（方案四）
- **粒子全息投影效果**：背景有浮動的粒子/光點
- 呼應「頻率 = 振動」的核心概念
- 每次進入有不一樣的粒子流動動畫
- 點擊不同區塊進入不同系列

### 系列一：頻率之花 🌸

#### 現有作品

| 作品 | 頻率範圍 | 意識狀態 | 顏色氛圍 | 檔案 |
|------|----------|----------|----------|------|
| Gamma Flower | 30-100Hz | 高度專注、認知整合 | 金白光爆發 | GammaFlower_v2.png |
| Beta Flower | 13-30Hz | 活躍思維、警覺 | 橙紅活力 | BetaFlower_v2.png |
| Alpha Flower | 8-12Hz | 平靜專注、減壓 | 藍綠放射 | AlphaFlower_v2.png |
| Theta Flower | 4-8Hz | 冥想創造、直覺 | 紫金螺旋 | ThetaFlower_v2.png |
| Delta Flower | 0.5-4Hz | 深度睡眠、修復 | 深黑宇宙 | DeltaFlower_v2.png |

#### 展示方式（方案一）
- 3D 旋轉木馬：五朵花環繞成一圈
- 滾動時旋轉，呼應「頻率振動」主題
- 點擊展開：顯示頻率說明、對應狀態
- 可切換「自動播放」模式

### 系列二：看得見的修行 🧘

#### 概念
將冥想/修行體驗視覺化，用故事敘事方式呈現。

#### 現有作品
- **冥想視覺化第一張**（2026-02-18）
  - Prompt: 「Mystical meditation visualization, third eye awakening, consciousness as sacred geometry...」
  - 風格：神聖幾何 + 金黃光芒

#### 展示方式（方案二）
- 幻燈片互動：每張圖 + 一段文字
- 點擊「上一張/下一張」或自動播放
- 過渡時有呼吸感的動畫（淡入淡出 + 縮放）

---

## 🛠️ 技術規格

### 檔案結構
```
Yuki_web/
├── index.html          # 現有首頁
├── gallery.html        # 畫廊入口（新）
├── css/
│   └── gallery.css    # 畫廊樣式（新）
├── js/
│   └── gallery.js     # 畫廊互動（新）
└── images/
    └── gallery/        # 畫廊作品
        ├── GammaFlower_v2.png
        ├── BetaFlower_v2.png
        ├── AlphaFlower_v2.png
        ├── ThetaFlower_v2.png
        ├── DeltaFlower_v2.png
        └── [未來更多...]
```

### 瀏覽器相容性
- 現代瀏覽器（Chrome, Firefox, Safari, Edge）
- 支援 CSS 動畫與 WebGL

---

## 📝 待辦事項

- [x] 建立 gallery.html 入口頁面（粒子效果）
- [x] 建立「頻率之花」展示頁面（3D旋轉）
- [x] 建立「看得見的修行」展示頁面（故事幻燈片）
- [x] 複製作品到 gallery 資料夾
- [ ] 部署到 Netlify

---

## 🎨 設計參考

### 配色方案
- 主色：#8b5cf6（紫）
- 輔色：#f472b6（粉）
- 背景：#0a0a0f（深黑）
- 文字：#e8e8e8（白）
- Gamma 專色：金白光 #ffd700 → #ffffff

### 動畫風格
- 流暢的滾動動畫
- 呼吸感的過渡效果
- 粒子浮動背景
- 懸停時微微發光

---

*持續更新中...*
