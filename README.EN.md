# 🍎 Rhapsody · Typora Theme (Fully Modular)

[TOC]
> 🇨🇳 中文版请见：[README.md](./README.md)

> “Color is the extension of thought,
>  and writing is the symphony of order and inspiration.”

## Contents
- [📸 Theme Preview](#-theme-preview)
- [🌈 Design Philosophy](#-design-philosophy)
- [🧩 Technical Highlights](#-technical-highlights)
- [✨ Theme Features](#-theme-features)
  - [🎨 1. Vibrant Visual Language](#-1-vibrant-visual-language)
  - [🌌 2. Light–Shadow & Energy Flow](#-2-lightshadow--energy-flow)
  - [🧩 3. Modular Structure & Custom Hooks](#-3-modular-structure--custom-hooks)
  - [💫 4. Cultural Easter Eggs & Symbol System](#-4-cultural-easter-eggs--symbol-system)
  - [🧠 5. Philosophy Meets Aesthetics](#-5-philosophy-meets-aesthetics)
- [📁 Project Structure](#-project-structure)
- [❓ FAQ](#-faq)
  - [🧾 Q1. How to get the best PDF export?](#-q1-how-to-get-the-best-pdf-export)
  - [⚙️ Q2. Why does it lag on very long documents?](#-q2-why-does-it-lag-on-very-long-documents)
- [🎨 Style Modules Overview](#-style-modules-overview)
  - [🧩 A. Main Visual Layer](#-a-main-visual-layer)
  - [🪞 B. Syntax Highlight Layer](#-b-syntax-highlight-layer)
  - [⚙️ C. System & Menu Layer](#-c-system--menu-layer)
  - [💾 D. Assets / Fonts / Logo](#-d-assets--fonts--logo)
  - [🧱 E. Structure & Fix Layer](#-e-structure--fix-layer)
  - [💡 Extra: Experimental Features](#-extra-experimental-features)
- [⚙️ Installation](#️-installation)
  - [🧭 Step 1 – Open Typora Theme Folder](#-step-1--open-typora-theme-folder)
  - [📂 Step 2 – Put Entry File & Resource Folder](#-step-2--put-entry-file--resource-folder)
  - [🧩 Step 3 – Entry File Provided](#-step-3--entry-file-provided)
  - [🎨 Step 4 – Enable in Typora](#-step-4--enable-in-typora)
- [📜 License & Credits](#-license--credits)
  - [🧾 License Statement](#-license-statement)
  - [✒️ Author & Project Info](#️-author--project-info)
  - [🪶 To Users](#-to-users)
- [🕓 Changelog](#-changelog)
  - [v1.0.0 – Initial Release – 2025-10-29](#v100--initial-release--2025-10-29)
- [🥚 Easter Eggs](#-easter-eggs)
- [💖 Support & Sponsor](#-support--sponsor)

------

**Rhapsody** is a Typora theme built around **“colorful · dreamy · kinetic”** aesthetics.
 It is not just a single CSS file, but a **visual experiment** that lets Markdown writing grow in light and motion.

 ## 📸 Theme Preview

> “Let color flow. Let text shine.”

Below are some snapshots of **🍎 Rhapsody Typora Theme**,  
showing how light, gradients and layered visuals interact with Markdown.

<p align="center">
  <img src="./Rhapsody/Assets/Preview/Preview1.png" width="320" alt="Rhapsody Preview 1" style="margin:6px;">
  <img src="./Rhapsody/Assets/Preview/Preview2.png" width="320" alt="Rhapsody Preview 2" style="margin:6px;">
  <img src="./Rhapsody/Assets/Preview/Preview3.png" width="320" alt="Rhapsody Preview 3" style="margin:6px;">
</p>

> ✨ *Rhapsody* is a small visual experiment about “color × motion × cognition.”  
> It tries to make Typora a place where writing grows in light instead of on a plain sheet.

---

## 🌈 Design Philosophy

Rhapsody is inspired by **Mirror’s Edge–style high-saturation color clashes** and **symbolic / philosophical aesthetics**.

Each animation, glow band and particle is mapped to a tiny piece of narrative:

- 🍵 **Tea Mist** – mild Eastern tenderness
- 🌌 **Galaxy Flow** – floating cognition and sparks of insight
- 🌅 **Sunset Glow** – time, memory and warmth
- 🌀 **Yin–Yang Badge** – balance of rationality and emotion

These are **not decorations** but a **visual grammar** of the theme.
 Rhapsody wants every piece of text to **“grow in light.”**

## 🧩 Technical Highlights

- Fully modular CSS: `layout.css`, `typography.css`, `math.css`, `table.css`, … separated
- Export-friendly: tuned for **Typora’s PDF / HTML export** (no DOM hacks)
- Responsive: separate rules for screen vs. print
- Easter-egg system: gradients, icon layers, animated badges

------

## ✨ Theme Features

### 🎨 1. Vibrant Visual Language

Rhapsody uses a high-contrast, high-saturation palette with soft gradients.
 Colors are bound to emotions and symbols – from calm blues to burning reds, from dreamy violets to golden energy bands – so that **color itself becomes part of the story.**

> 🧠 Design motto: **Color is thought, rendered.**

------

### 🌌 2. Light–Shadow & Energy Flow

Multi-layer animations are built in:

- dynamic glowing titles (h1 “Appleron style”)
- breathing background energy bands
- floating bubbles & hover-triggered brightness

So editing in Typora gains a sense of **space** and **rhythm**.

------

### 🧩 3. Modular Structure & Custom Hooks

Rhapsody’s CSS is organized into clearly separated modules:

- `layout.css` – writing area & global light system
- `typography.css` – headings, hero titles, “Appleron” look
- `math.css` – math blocks, MathJax SVG fixes
- `table.css` – table styling & print patches
- `selection.css` – selection glow
- `export_patch.css` – PDF / HTML fixes

> You can swap / remove / extend modules without touching Typora’s HTML structure.

------

### 💫 4. Cultural Easter Eggs & Symbol System

Rhapsody ships with a set of **symbolic micro-stories** hidden in icons, colors and animations:

| Element              | Meaning                | Where                   |
| -------------------- | ---------------------- | ----------------------- |
| 🍎 Appleron glowband  | creation & rationality | h1 heading              |
| 🐰 Pocket-watch bunny | time & reflection      | h4 heading              |
| 🌀 Yin–yang badge     | balance & harmony      | corner / footer         |
| 🌈 Spectrum drift     | cognitive flow         | background energy layer |
| 🕯️ Bubble glow        | sudden inspiration     | hover layers            |

------

### 🧠 5. Philosophy Meets Aesthetics

Rhapsody is a **visual philosophy practice**:
 abstract ideas like **existence, order, insight** are projected into gradients, layers and symbols.

> Every writing session becomes a small journey of “recognition.”

------

## 📁 Project Structure

（This mirrors your Chinese tree – keep it as-is, just change file descriptions if you want. Since repo users often scan folder names first, keeping Chinese artwork names is totally fine.）

```
Rhapsody/
├── Assets/
│   ├── Menu/ ...
│   ├── Mermaid/ ...
│   ├── Preference/ ...
│   ├── Siderbar/ ...
│   ├── TOC/ ...
│   ├── Table/ ...
│   └── UI/ ...
├── Auxiliary/ ...
├── Fix/
├── Fonts/ ...
├── Logo/ ...
├── Main_Visual/ ...
├── Menu/ ...
├── Syntax/ ...
├── prerequisite.css
├── tree.md
└── tree.txt
```

------

## ❓ FAQ

### 🧾 Q1. How to get the best PDF export?

To keep the exported PDF visually close to what you see in Typora:

| Option                              | Suggested value | Notes                            |
| ----------------------------------- | --------------- | -------------------------------- |
| **Paper Size**                      | Custom          | use larger canvas for background |
| **Margins**                         | 1mm / 15mm / …  | fine-tune for your monitor DPI   |
| **Width × Height**                  | 287mm × 393mm   | A4+ style high-res layout        |
| **Theme**                           | Current Theme   | export with Rhapsody             |
| **Page break between top headings** | ✅ On            | one chapter per page             |
| **Header / Footer**                 | Off             | keep it clean                    |

> Different displays may need a little margin adjustment.

------

### ⚙️ Q2. Why does it lag on very long documents?

Because Rhapsody **really** uses animations and layered backgrounds 😅
 So when your doc is 10k+ words, Typora’s rendering cost goes up.

| Mode                  | What to do                                    | Effect                                      |
| --------------------- | --------------------------------------------- | ------------------------------------------- |
| **Performance first** | move `Rhapsody/Assets/Menu` → `Rhapsody/Fix/` | disable top animated menu, faster           |
| **Visual first**      | keep `Menu`                                   | full motion, slightly heavier on large docs |

> As a rule of thumb:
>
> - with menu: keep docs ≤ **10,000 words**
> - without menu: **50,000–100,000 words** is still ok

------

## 🎨 Style Modules Overview

> “Every visual change is a small rebuild of Typora’s soul.”

Rhapsody already supports Typora’s common **admonition-like extended syntax** such as `[!tip]`, `[!warning]`, task lists, footnotes, Mermaid, etc., with theme-aligned colors.

### 🧩 A. Main Visual Layer

| File / Folder           | Description                            |
| ----------------------- | -------------------------------------- |
| `background.css`        | global background & energy bands       |
| `sidebar_file_list.css` | left sidebar card layout               |
| `sidebar_file_tree.css` | file tree lines & icons                |
| `sidebar_outline.css`   | outline view, heading indent animation |
| `write.css`             | writing card, glow frame               |
| `备份/`                 | legacy visual variations               |

------

### 🪞 B. Syntax Highlight Layer

Covers all Markdown visual components.

| File                                        | Description                                   |
| ------------------------------------------- | --------------------------------------------- |
| `headings.css`                              | h1–h6 “Appleron” headings + icons + glow      |
| `list.css`                                  | nested list cards, ordered / unordered / todo |
| `table.css`                                 | rounded tables + export patches               |
| `mathblock.css`                             | MathJax SVG alignment, fraction line fix      |
| `blockquote.css`                            | semantic quote with colored bar               |
| `link.css` / `mark.css` / `inline_code.css` | inline emphasis                               |
| `toc.css`                                   | gradient TOC block                            |
| other files                                 | footnotes, mermaid, yaml frontmatter          |

------

### ⚙️ C. System & Menu Layer

| Area                            | What it does                           |
| ------------------------------- | -------------------------------------- |
| `Menu/Preferences_area`         | restyles Typora settings panels        |
| `Auxiliary/focusmode.css`       | soft focus mode                        |
| `Auxiliary/focus-spotlight.css` | spotlight focus mode                   |
| `Auxiliary/html_export.css`     | HTML export background + UA margin fix |
| `Auxiliary/pdf_export.css`      | PDF-only patches                       |
| `Auxiliary/selection.css`       | pink selection glow                    |
| `Auxiliary/word_count_ui.css`   | nicer word-count widget                |
| `Auxiliary/menu_ui.css`         | top menu energy bar                    |

------

### 💾 D. Assets / Fonts / Logo

| Folder               | Content                                      |
| -------------------- | -------------------------------------------- |
| `Assets/*`           | themed images, UI decorations                |
| `Fonts/`             | bundled CN/EN fonts (Alibaba, Source Han, …) |
| `Logo/Headings_Icon` | icons for each heading level                 |
| `Logo/Write_Icon`    | corner badges / prince icon                  |

------

### 🧱 E. Structure & Fix Layer

| File / Folder        | Description                                    |
| -------------------- | ---------------------------------------------- |
| `prerequisite.css`   | global variables, colors, spacing, transitions |
| `Fix/`               | performance / export fallback modules          |
| `tree.md / tree.txt` | project structure doc                          |

------

### 💡 Extra: Experimental Features

| File                            | Description                      |
| ------------------------------- | -------------------------------- |
| `Auxiliary/focus-spotlight.css` | spotlight focus mode             |
| `Auxiliary/html_export.css`     | force background for HTML export |
| `Auxiliary/spell_check_ui.css`  | spell-check highlight tuning     |
| `Auxiliary/menu_ui.css`         | animated top menu                |

> All modules follow Typora’s constraint: **no HTML structure change, CSS-only.**

------

## ⚙️ Installation

### 🧭 Step 1 – Open Typora Theme Folder

Typora → Preferences → Appearance → **Open Theme Folder**

- Windows: `C:\Users\<you>\AppData\Roaming\Typora\themes`
- macOS: `~/Library/Application Support/abnerworks.Typora/themes`
- Linux: `~/.config/Typora/themes`

------

### 📂 Step 2 – Put **entry file** + **resource folder**

Copy **`rhapsody.css`** (entry) and **`Rhapsody/`** (resources) to `themes/` **at the same level**:

```
themes/
├── rhapsody.css          ← entry (must be here)
├── Rhapsody/             ← resource folder
├── Github.css
└── Night.css
```

> Don’t put `rhapsody.css` **inside** `Rhapsody/`.
>  Entry + resources must be siblings so relative paths like `./Rhapsody/...` work.

------

### 🧩 Step 3 – Entry File Provided

`rhapsody.css` already imports modules in the correct order.
 If you customize, keep this order:

1. `Rhapsody/prerequisite.css`
2. `Rhapsody/Main_Visual/...`
3. `Rhapsody/Syntax/...`
4. `Rhapsody/Auxiliary/...` / `Rhapsody/Menu/...` (optional)

------

### 🎨 Step 4 – Enable in Typora

Restart Typora → Themes → **rhapsody**.
 (The theme list shows the entry file name.)

------

## 📜 License & Credits

**License:** Creative Commons BY-NC-SA 4.0

- ✅ Free to download / study / modify
- ✅ Free to share for **non-commercial** use
- ⚠️ Please keep the attribution:
   **“Rhapsody Typora Theme — Designed by 帅气大王子 CGM (The Radiant Prince)”**
- 🚫 No commercial resell / paid redistribution
- 🔁 Derivative themes should keep the same license

------

### ✒️ Author & Project Info

| Role              | Name / Link                                 | Notes                             |
| ----------------- | ------------------------------------------- | --------------------------------- |
| **Design & Dev**  | 🫅 **CGM – The Radiant Prince**              | author of Rhapsody                |
| **Repo**          | **CGMgit** on GitHub                        | official releases & updates       |
| **Fonts & Icons** | Alibaba PuHui, Source Han, ZCOOL, JetBrains | follow original font licenses     |
| **Compatibility** | Typora v1.7+ / Electron v22+                | older versions fall back to basic |

------

### 🪶 To Users

Rhapsody is not only a skin – it’s a **writing experiment about order, light and thought**.
 If you localize / port / extend it, please keep the credit line so the story continues.

------

## 🕓 Changelog

### v1.0.0 — Initial Release 

- full heading system (h1–h6) with icons & glow
- energy-band writing area
- colorful syntax suite
- export compatibility patches
- performance/fix mode
- bundled fonts

------

## 🥚 Easter Eggs

Easter eggs are triggered by **checklist + anchor** pattern:

```
- [x] I want to trigger the prince egg! [Toggle here](#egg-prince)
<span id="egg-prince"></span>
```

When checked + anchor exists → colored corner badge & animation.
 For environments that can’t auto-trigger (some HTML/PDF exports), add:

```
<style>#write::after { --corner-img: var(--corner-img-colored); }</style>

```
------
## 💖 Support & Sponsor

If you like Rhapsody Typora Theme,
and want me to keep polishing it, adding variants, or releasing “dark / festival / lecture” editions,
you can support the project here 🌈

🌍 International	🇨🇳 Mainland China
☕ Ko-fi — gongmingcao
	💎 爱发电 — 帅气大王子66

Every bit of support
becomes a new color, a new animation, a new idea —
and keeps Rhapsody glowing in Typora’s world.
------




