# 🍎 Rhapsody · Typora 专属皮肤主题
[TOC]
> 🌐 English version: [README.EN.md](./README.EN.md)

> “色彩，是思想的延伸；  
> 写作，是秩序与灵感的交响。”

## 目录
- [📸 主题预览](#-主题预览)
- [🌈 设计理念](#-设计理念)
- [🧩 技术特征](#-技术特征)
- [✨ 主题特色](#-主题特色)
  - [🎨 一、五彩缤纷的视觉语言](#-一五彩缤纷的视觉语言)
  - [🌌 二、光影与能量流动系统](#-二光影与能量流动系统)
  - [🧩 三、模块化结构与自定义接口](#-三模块化结构与自定义接口)
  - [💫 四、文化彩蛋与符号体系](#-四文化彩蛋与符号体系)
  - [🧠 五、哲学与审美的融合](#-五哲学与审美的融合)
- [📁 文件结构](#-文件结构)
- [❓ 常见问题](#-常见问题)
  - [🧾 Q1. 如何获得最佳的 PDF 导出效果？](#-q1-如何获得最佳的-pdf-导出效果)
  - [⚙️ Q2. 为什么文字较多时会出现卡顿？](#-q2-为什么文字较多时会出现卡顿)
- [🎨 修改样式清单汇总](#-修改样式清单汇总)
  - [🧩 一、核心视觉层（Main_Visual）](#-一核心视觉层main_visual)
  - [🪞 二、语法高亮层（Syntax）](#-二语法高亮层syntax)
  - [⚙️ 三、系统与菜单层（menu--auxiliary）](#-三系统与菜单层menu--auxiliary)
  - [💾 四、素材与字体层（assets--fonts--logo）](#-四素材与字体层assets--fonts--logo)
  - [🧱 五、结构与逻辑层（prerequisitecss--fix）](#-五结构与逻辑层prerequisitecss--fix)
  - [💡 附：扩展模块（Experimental Features）](#-附扩展模块experimental-features)
- [⚙️ 安装与启用方法](#️-安装与启用方法)
  - [🧭 step-1-打开主题目录](#-step-1-打开主题目录)
  - [📂 step-2-放置入口文件与资源目录](#-step-2-放置入口文件与资源目录)
  - [🧩 step-3-入口文件已提供](#-step-3-入口文件已提供)
  - [🎨 step-4-在-typora-中启用](#-step-4-在-typora-中启用)
- [📜 许可证与署名](#-许可证与署名)
  - [🧾 授权声明](#-授权声明)
  - [✒️ 作者与项目信息](#️-作者与项目信息)
  - [🪶 致使用者](#-致使用者)
- [🕓 更新日志](#-更新日志)
  - [v100--initial-release--20251029](#v100--initial-release--20251029)
- [🥚 小彩蛋](#-小彩蛋)
- [💖 支持与赞助](#-支持与赞助)


> “色彩，是思想的延伸；
> 写作，是秩序与灵感的交响。”

**Rhapsody** 是一款以「多彩、梦幻、灵动」为核心设计理念的 Typora 个性化主题皮肤。
 它不仅是一份 CSS 文件，更是一场视觉实验 ——
 让 Markdown 写作在光影与色彩中重新焕发生命。

 ## 📸 主题预览

> “让色彩流动，让文字发光。”

下列截图展示了 **🍎 Rhapsody Typora Theme** 的部分视觉界面，  
每一束光带、每一个渐变，都记录着它对 **秩序与灵感** 的理解。

<p align="center">
  <img src="./Rhapsody/Assets/Preview/Preview1.png" width="320" alt="Rhapsody 预览图 1" style="margin:6px;">
  <img src="./Rhapsody/Assets/Preview/Preview2.png" width="320" alt="Rhapsody 预览图 2" style="margin:6px;">
  <img src="./Rhapsody/Assets/Preview/Preview3.png" width="320" alt="Rhapsody 预览图 3" style="margin:6px;">
</p>

> ✨ *Rhapsody* 是一场“色彩与思维的实验”，  
> 让 Markdown 写作在光影与哲学之间生长出新的秩序。

---

## 🌈 设计理念

Rhapsody 的灵感来自 **《镜之边缘》式高饱和撞色** 与 **哲学符号美学**。
 每一种动画、色带与阴影都对应着一个小小的“文化彩蛋”：

- 🍵 **茶香氤氲** —— 代表东方的温柔与克制；
- 🌌 **星河流彩** —— 象征思想的流动与认知的闪光；
- 🌅 **落日余晖** —— 致敬时光与记忆的温度；
- 🌀 **阴阳鱼徽章** —— 映射出理性与感性的平衡。

这些元素并非单纯装饰，而是构成主题精神的视觉语法。
 Rhapsody 希望让 **每一篇文字，都在光影之间生长**。

## 🧩 技术特征

- 全局模块化结构：`layout.css`, `typography.css`, `math.css`, `table.css` 等独立管理
- 导出友好：适配 **Typora 的 PDF / HTML 输出**，不破坏编辑结构
- 响应式设计：针对屏幕与打印布局分别优化
- 彩蛋系统：通过 CSS 动画、渐变与符号隐藏多个文化小机关

---

## ✨ 主题特色

### 🎨 一、五彩缤纷的视觉语言

Rhapsody 采用高饱和撞色与柔光渐变的色彩体系，
 每种色彩都拥有特定的情绪与象征意义——
 从宁静的天蓝到炽热的赤红，从梦幻的紫光到金色能量带，
 在 Typora 的白纸上，色彩本身成为了叙事的一部分。

> 🧠 设计哲学：**色彩即思想的具象化。**

------

### 🌌 二、光影与能量流动系统

主题内置多层级光影动画：

- 动态流光标题（如 h1 “Appleron 风格”）
- 柔性能量带背景与悬浮粒子效果
- 交互触发的亮度渐变与泡泡漂浮
  这些效果在 Typora 编辑环境中呈现出一种“呼吸感”与“空间层次感”，
  让写作过程充满节奏与灵动。

------

### 🧩 三、模块化结构与自定义接口

Rhapsody 的 CSS 架构分为多个独立模块，结构清晰：

- `layout.css` —— 写作区布局与全局光影系统
- `typography.css` —— 字体与标题排版（Appleron 风格）
- `math.css` —— 数学公式与符号高亮体系
- `table.css` —— 表格样式（含打印友好设计）
- `selection.css` —— 文本选区与交互反馈
- `export_patch.css` —— PDF / HTML 导出修正补丁

> 每个模块都可单独替换或组合扩展，方便后期主题的个性化升级。

------

### 💫 四、文化彩蛋与符号体系

Rhapsody 内嵌多个“文化彩蛋（Easter Eggs）”，
 它们隐藏在动画细节、图标与配色逻辑中，
 构成一套**符号化叙事体系**：

| 彩蛋元素        | 含义象征       | 出现位置       |
| --------------- | -------------- | -------------- |
| 🍎 Appleron 光带 | 创造与理性之光 | 一级标题（h1） |
| 🐰 怀表兔影      | 时间与思辨     | 四级标题（h4） |
| 🌀 阴阳鱼图案    | 平衡与和谐     | 页脚角标       |
| 🌈 光谱漂流动画  | 认知流动       | 背景能量层     |
| 🕯️ 渐隐泡泡光    | 灵感闪现       | 编辑态悬浮层   |

------

### 🧠 五、哲学与审美的融合

Rhapsody 并非单纯的美化，而是一种**“视觉哲学的实践”**。
 它将“存在、秩序与灵感”的抽象思想，
 通过层叠、渐变、符号与光影映射在文字世界之中。

> 让每一次书写，都成为一次关于“认识”的旅程。

---

## 📁 文件结构

```bash
Rhapsody/
├── Assets
│   ├── Menu
│   │   ├── 南屏晚风.png
│   │   └── 纯净都市.png
│   ├── Mermaid
│   │   └── 欣欣向荣.png
│   ├── Preference
│   │   ├── 惊涛拍岸.png
│   │   ├── 星河流彩.png
│   │   ├── 月河童梦.png
│   │   ├── 玫瑰暗影.png
│   │   ├── 茶香氤氲.png
│   │   ├── 落日余晖.png
│   │   └── 风吹麦浪.png
│   ├── Siderbar
│   │   └── 阴阳鱼.png
│   ├── TOC
│   │   └── 扬帆起航.png
│   ├── Table
│   │   ├── datauri_bundle.css
│   │   ├── 千里江山.png
│   │   ├── 天上人间.png
│   │   ├── 天上人间.png.datauri.txt
│   │   ├── 江山如故.png
│   │   └── 渔舟唱晚.png
│   └── UI
│       ├── 一口吃掉.png
│       ├── 冬-独钓寒江.png
│       ├── 夏-荷叶红花.png
│       ├── 昏-万籁俱寂.png
│       ├── 春-黄发垂髫.png
│       ├── 晨-一日之计.png
│       ├── 梦幻森林.jpg
│       ├── 秋-鸿雁南飞.png
│       └── 超级大肥橘.png
├── Auxiliary
│   ├── T
│   ├── desktop_ui.css
│   ├── focusmode.css
│   ├── html_export.css
│   ├── menu_ui.css
│   ├── pdf_export.css
│   ├── selection.css
│   ├── spell_check_ui.css
│   └── word_count_ui.css
├── Fix
├── Fonts
│   ├── AlibabaPuHuiTi-3-75-SemiBold
│   │   ├── AlibabaPuHuiTi-3-75-SemiBold.woff2
│   │   └── AlibabaPuHuiTi-License.txt.txt
│   ├── FontAwesome
│   │   ├── FontAwesome.otf
│   │   ├── LICENSE.txt
│   │   ├── fontawesome-webfont.ttf
│   │   ├── fontawesome-webfont.woff
│   │   └── fontawesome-webfont.woff2
│   ├── JetBrainsMono
│   │   ├── AUTHORS.txt
│   │   ├── JetBrainsMono-Italic[wght].ttf
│   │   ├── JetBrainsMono[wght].ttf
│   │   └── OFL.txt
│   ├── Latinmodernmath
│   │   ├── LICENSE-LatinModernMath.txt.txt
│   │   └── LatinmodernmathRegular.woff2
│   ├── LxgwWenKai-main
│   │   ├── LXGWWenKai-Regular.woff2
│   │   └── OFL.txt
│   ├── Playfair_Display
│   │   ├── OFL.txt
│   │   ├── PlayfairDisplay-Italic-VariableFont_wght.ttf
│   │   └── PlayfairDisplay-VariableFont_wght.ttf
│   ├── PressStart2P-Regular
│   │   ├── OFL.txt
│   │   └── PressStart2P-Regular.ttf
│   ├── ResourceHanRoundedCN
│   │   ├── LICENSE-SourceHanSansCN.txt.txt
│   │   └── ResourceHanRoundedCN-Regular.woff2
│   ├── Roboto_Mono
│   │   ├── OFL.txt
│   │   ├── RobotoMono-Italic-VariableFont_wght.ttf
│   │   └── RobotoMono-VariableFont_wght.ttf
│   ├── SourceHanSans-Pixel-main
│   │   ├── LICENSE
│   │   ├── LICENSE.SourceHanSans
│   │   └── SourceHanSansSC-VF.otf
│   ├── SourceHanSerifSC
│   │   ├── LICENSE.txt
│   │   └── SourceHanSansSC-VF.woff2
│   ├── ZCOOL - Addict Italic
│   │   ├── ZCOOL Addict Italic 01.ttf
│   │   ├── ZCOOL Addict Italic 02.ttf
│   │   └── ZCOOL-AddictItalic-License.txt.txt
│   ├── ZCoolGaoDuanHei
│   │   ├── ZCOOL-HiBlack-License.txt.txt
│   │   └── ZCoolGaoDuanHei.woff2
│   └── ZhanKuWenYiTi
│       ├── LICENSE.txt.txt
│       ├── ZhanKuWenYiTi-2.woff2
│       └── 字由客户端.url
├── Logo
│   ├── Background_Icon
│   │   ├── Typora作业培根.ico
│   │   ├── 冒险培根.ico
│   │   ├── 厨师培根.ico
│   │   └── 睡觉培根.ico
│   ├── Headings_Icon
│   │   ├── 兔子怀表.svg
│   │   ├── 帅气大王子.webp
│   │   ├── 狐狸面具.png
│   │   ├── 金箍棒.svg
│   │   ├── 雷神之锤.png
│   │   └── 魔法苹果.svg
│   └── Write_Icon
│       ├── 帅气大王子.png
│       └── 帅气大王子透明版.png
├── Main_Visual
│   ├── background.css
│   ├── sidebar_file_list.css
│   ├── sidebar_file_tree.css
│   ├── sidebar_outline.css
│   ├── write.css
│   └── 备份
│       ├── background.css
│       └── write.css
├── Menu
│   ├── Preferences_area
│   │   ├── appearance.css
│   │   ├── editor.css
│   │   ├── export.css
│   │   ├── files.css
│   │   ├── general.css
│   │   ├── image.css
│   │   └── markdown.css
│   ├── about_area.css
│   ├── export_area.css
│   ├── open_area.css
│   └── themes_area.css
├── Syntax
│   ├── blockquote.css
│   ├── bold_italic.css
│   ├── codeblock.css
│   ├── footnote.css
│   ├── headings.css
│   ├── horizontal_rule.css
│   ├── inline_code.css
│   ├── link.css
│   ├── list.css
│   ├── lnline_math.css
│   ├── mark.css
│   ├── mathblock.css
│   ├── mermaid.css
│   ├── paragraph.css
│   ├── table.css
│   ├── task.css
│   ├── toc.css
│   └── yaml.css
├── prerequisite.css
├── tree.md
└── tree.txt
```

## ❓ 常见问题

### 🧾 Q1. 如何获得最佳的 PDF 导出效果？

为了保证 **Rhapsody** 在导出 PDF 时保持与 Typora 编辑界面一致的视觉效果，
 建议在 **Typora > Preferences > Export > PDF** 中进行如下设置（如图所示）：

| 参数                                   | 建议值          | 说明                        |
| -------------------------------------- | --------------- | --------------------------- |
| **Paper Size**                         | Custom          | 使用自定义页面尺寸          |
| **Margin Top / Bottom / Left / Right** | 1 mm / 15 mm    | 根据屏幕比例微调            |
| **Width × Height**                     | 287 mm × 393 mm | 对应 A4+ 尺寸的高分辨率排版 |
| **Theme**                              | Current Theme   | 使用当前主题导出            |
| **Page Break Between Top Headings**    | ✅ 开启          | 在一级标题间分页            |
| **Header / Footer / Author**           | None            | 保持页面简洁                |
| **After Export**                       | 关闭            | 避免导出后重复打开文件      |

> 💡 *不同分辨率与屏幕 DPI 下，边距参数可略作调整，以保持页面对称与视觉均衡。*

------

### ⚙️ Q2. 为什么文字较多时会出现卡顿？

当文档字数超过一定规模（尤其启用动态动画模块时），
 Typora 渲染性能可能下降。为此提供两种优化方案：

| 方案                 | 操作                                                   | 效果说明                                     |
| -------------------- | ------------------------------------------------------ | -------------------------------------------- |
| **性能优先（推荐）** | 将 `Rhapsody/Assets/Menu` 文件夹移动至 `Rhapsody/Fix/` | 关闭顶部动态菜单样式，显著提升流畅度         |
| **视觉优先**         | 保留 `Menu` 文件夹                                     | 保留完整动效与彩蛋，但对长文档性能有一定影响 |

> 📖 建议：
>
> - 含有 `Menu` 部分的文档建议控制在 **1 万字以内**；
> - 不含 `Menu` 的文档可支持 **5–10 万字** 长篇写作。

##🎨 修改样式清单汇总

> “每一处视觉的改变，都是一次对 Typora 灵魂的重构。”

Rhapsody 主题的样式体系由多个功能域组成，采用 **分区管理 + 模块化导入** 的方式。
 下表与目录树对照展示了各功能区的作用与主要改动点。

**📎 备注：**
 Rhapsody 主题已适配 Typora 常见扩展语法（含 `[!tip]`、`[!warning]`、任务列表、脚注、mermaid 图表等），
 用户可直接使用，无需额外配置。

------

### 🧩 一、核心视觉层（Main_Visual）

| 文件 / 文件夹           | 功能说明                                       |
| ----------------------- | ---------------------------------------------- |
| `background.css`        | 全局背景与能量层系统（含昼夜光带、渐变、晕影） |
| `sidebar_file_list.css` | 左侧文件栏样式（卡片阴影、分组折叠效果）       |
| `sidebar_file_tree.css` | 文件树层级线条与文件夹图标设计                 |
| `sidebar_outline.css`   | 大纲视图结构线、标题缩进动画                   |
| `write.css`             | 写作区基础样式（卡片化主体、光影框架）         |
| `备份/`                 | 保存旧版本视觉方案（如经典写作区背景）         |

------

### 🪞 二、语法高亮层（Syntax）

覆盖 Markdown 语法的全部可视化组件。

| 文件                                      | 改动方向                                             |
| ----------------------------------------- | ---------------------------------------------------- |
| `headings.css`                            | 六级标题 Appleron 风格体系（光带动画 + 图标 + 字体） |
| `list.css`                                | 多层嵌套列表卡片化样式（含有序 / 无序 / Checklist）  |
| `table.css`                               | 表格阴影、圆角与导出补丁适配                         |
| `mathblock.css`                           | 行间公式与 MathJax SVG 样式统一（修复分数线显示）    |
| `blockquote.css`                          | 语义引用设计（左右色条 + 柔光背景）                  |
| `link.css`, `mark.css`, `inline_code.css` | 行内语法强调色与悬浮动画                             |
| `toc.css`                                 | 目录区域渐变分隔与悬浮高亮                           |
| 其余文件                                  | 包含脚注、任务列表、mermaid 图等结构模块             |

------

### ⚙️ 三、系统与菜单层（Menu / Auxiliary）

| 区域                            | 功能与改动说明                                               |
| ------------------------------- | ------------------------------------------------------------ |
| `Menu/Preferences_area`         | Typora 设置界面视觉重塑：每个标签页独立配色（如 Export / Markdown / Editor 等） |
| `Auxiliary/focusmode.css`       | 专注模式视觉（原始柔光版）                                   |
| `Auxiliary/focus-spotlight.css` | 聚光灯专注模式（独立文件版 · Spotlight Focus）               |
| `Auxiliary/html_export.css`     | 导出 HTML 修复白边与底色统一                                 |
| `Auxiliary/pdf_export.css`      | 导出 PDF 专用补丁（页边距 / 背景修正）                       |
| `Auxiliary/selection.css`       | 文本选区动画与高亮（玫瑰粉光带）                             |
| `Auxiliary/word_count_ui.css`   | 右下角字数统计界面美化                                       |
| `Auxiliary/menu_ui.css`         | 顶部菜单栏样式（能量光带 + 透明背景）                        |

------

### 💾 四、素材与字体层（Assets / Fonts / Logo）

| 文件夹                                   | 内容                                                         |
| ---------------------------------------- | ------------------------------------------------------------ |
| `Assets/Menu`、`Preference`、`TOC`、`UI` | 各区域配图与动画素材（如“南屏晚风”、“梦幻森林”等）           |
| `Fonts/`                                 | 字体资源包（含阿里普惠体、思源黑体、站酷文艺体、ZCOOL 意大利体等） |
| `Logo/Headings_Icon`                     | 六级标题对应图标（苹果、雷神之锤、金箍棒、狐狸面具等）       |
| `Logo/Write_Icon`                        | 写作页右上角角标（帅气大王子 / 透明版）                      |

------

### 🧱 五、结构与逻辑层（prerequisite.css / Fix）

| 文件 / 文件夹        | 功能说明                                                   |
| -------------------- | ---------------------------------------------------------- |
| `prerequisite.css`   | 全局变量定义与初始化（颜色、字体、间距、过渡）             |
| `Fix/`               | 导出与性能优化备用目录；将部分动态模块转移此处可提高流畅度 |
| `tree.md / tree.txt` | 工程结构文档（即本目录树与说明文件）                       |

------

### 💡 附：扩展模块（Experimental Features）

| 文件                            | 功能描述                                      |
| ------------------------------- | --------------------------------------------- |
| `Auxiliary/focus-spotlight.css` | 聚光灯专注模式（Spotlight Focus）             |
| `Auxiliary/html_export.css`     | HTML 导出模式修正（强制底色、去除 UA margin） |
| `Auxiliary/spell_check_ui.css`  | 拼写检查交互提示色优化                        |
| `Auxiliary/menu_ui.css`         | Typora 顶部菜单栏能量条动画                   |
| `Auxiliary/focusmode.css`       | 柔光版专注模式（旧版保留）                    |

------

> 🌈 **注：**
> 所有模块均遵循 Typora 的结构约束：**不改动 HTML DOM，仅通过 CSS 选择器与伪元素实现。**
> 每个分区文件均可独立启用、禁用或替换，形成完整的主题装配体系。

## ⚙️ 安装与启用方法

### 🧭 Step 1. 打开主题目录

Typora → 偏好设置（Preferences）→ 外观（Appearance）→ **打开主题文件夹（Open Theme Folder）**。

- Windows: `C:\Users\<你>\AppData\Roaming\Typora\themes`
- macOS: `~/Library/Application Support/abnerworks.Typora/themes`
- Linux: `~/.config/Typora/themes`

------

### 📂 Step 2. 放置**入口文件**与**资源目录**

将仓库中的 **`rhapsody.css`（入口文件）** 与 **`Rhapsody/`（资源目录）** 一起复制到 `themes/`，形成如下结构（关键是两者为**同级**）：

```
themes/
├── rhapsody.css            ← 入口文件（必须在根目录）
├── Rhapsody/               ← 主题资源目录（保持完整结构）
│   ├── Main_Visual/
│   ├── Syntax/
│   ├── Auxiliary/
│   ├── Assets/
│   ├── Fonts/
│   ├── Logo/
│   └── prerequisite.css
├── Github.css
└── Night.css
```

> ⚠️ **不要**把 `rhapsody.css` 放进 `Rhapsody/` 里面；
> 入口与资源目录为同级，确保 `rhapsody.css` 内的相对路径（如 `./Rhapsody/...`）能正确引用。

------

### 🧩 Step 3. 入口文件（已提供）

`rhapsody.css` 已写好按模块顺序的导入；若之后要自定义，请遵循**建议导入顺序**：

1. 基础变量与字体：`Rhapsody/prerequisite.css`
2. 核心视觉：`Rhapsody/Main_Visual/*.css`
3. 语法模块：`Rhapsody/Syntax/*.css`
4. 辅助与菜单：`Rhapsody/Auxiliary/*.css`、`Rhapsody/Menu/*.css`（按需）

示例（片段，仅说明相对路径用法）：

```
/* rhapsody.css — Entry */
@import url("./Rhapsody/prerequisite.css");
@import url("./Rhapsody/Main_Visual/background.css");
@import url("./Rhapsody/Main_Visual/write.css");
@import url("./Rhapsody/Syntax/headings.css");
@import url("./Rhapsody/Syntax/list.css");
@import url("./Rhapsody/Syntax/table.css");
@import url("./Rhapsody/Auxiliary/selection.css");
/* …其余模块已在仓库版本中按顺序列好 */
```

------

### 🎨 Step 4. 在 Typora 中启用

重启 Typora → **主题（Themes）** → 选择 **`rhapsody`**。
 （Typora 的主题列表会显示入口文件名；因此入口文件需命名为 **`rhapsody.css`**。）

## 📜 许可证与署名

> “每一份色彩与线条，皆属于自由的灵感；
> 但每一次创造，也值得被铭记。”

### 🧾 授权声明

**License:** Creative Commons BY-NC-SA 4.0 International
 （署名-非商业-相同方式共享）

这意味着：

- ✅ 你可以自由下载、学习、修改与再创作；
- ✅ 你可以在**非商业用途**下分享与传播；
- ⚠️ 转载或二次发布时请保留署名：
  **“Rhapsody Typora Theme — Designed by 帅气大王子 CGM（The Radiant Prince）”**；
- 🚫 禁止任何形式的商业销售、付费再分发或未经授权的衍生付费主题；
- 🔁 若进行衍生创作，请沿用相同协议（CC BY-NC-SA 4.0）。

------

### ✒️ 作者与项目信息

| 项目角色           | 名称 / 标识                                                  | 说明                                   |
| ------------------ | ------------------------------------------------------------ | -------------------------------------- |
| **主题设计与开发** | 🫅 **帅气大王子 CGM（The Radiant Prince）**                   | Rhapsody Typora Theme 作者、设计总监   |
| **仓库主页**       | [**CGMgit**](https://github.com/CGMgit)                      | 官方代码托管与更新发布点               |
| **字体与图标资源** | 阿里巴巴普惠体 / 思源黑体 / 站酷文艺体 / ZCOOL 系列 / JetBrains Mono 等 | 按原字体许可文件独立授权               |
| **图像与插画素材** | 主题 `Assets/` 与 `Logo/` 目录                               | 作者原创或基于 CC-BY-SA 协议的二次创作 |
| **兼容与测试**     | Typora v1.7+ / Electron v22+                                 | 已验证版本范围，旧版本回退为静态样式   |

> 🌸 致谢 Typora 团队的长期维护，
> 让这份主题得以在 **美学与功能** 之间持续进化。

------

### 🪶 致使用者

Rhapsody 并不仅是一份视觉皮肤，
 它是一场关于**秩序、光影与思想的写作实验**。
 若你在使用中进行了二次创作、翻译或拓展，
 请保留署名，让美与灵感在 Typora 的世界中延续。

## 🕓 更新日志

> “万象初开，光与秩序交织的第一章。”

### v1.0.0 — Initial Release · 2025.10.29

**Rhapsody Typora Theme** 正式发布 🎉

#### 🌈 版本概述

Rhapsody 是一款以「高饱和撞色 + 动态光影」为核心设计语言的 Typora 专属主题。
 初代版本确立了主题的完整美学架构与技术体系，为后续扩展模块奠定基础。

#### 🧩 核心功能模块

- **Appleron 标题体系**：h1–h6 全级标题风格定制（含图标与动画光带）。
- **能量光带写作区**：卡片化版心 + 外扩能量层 + 太阳角标。
- **五彩语法结构**：列表、表格、引用、公式、脚注全面美化。
- **文化彩蛋机制**：支持任务项 + 链接触发角标动画。
- **导出兼容系统**：PDF / HTML 输出完全适配 Typora 新版渲染逻辑。
- **性能优化模式**：支持 “Fix” 方案切换，兼顾长文档流畅度。
- **字体集成**：内置 10+ 高质量中英文字体（阿里普惠体、思源黑体、站酷文艺体、ZCOOL 等）。

#### 💡 美学与理念

- 将写作过程视觉化、节奏化，使 Markdown 成为沉浸式体验；
- 以“卡片”、“能量”、“聚焦”三大视觉语法诠释“文字的光”；
- 融合哲学象征与文化彩蛋，让每篇文稿都可生长出独特氛围。

------

> 🪞 *Rhapsody v1.0.0 是 Typora 主题史中的一段梦幻篇章，
> 她不是默认皮肤的替代，而是一种关于写作方式的重新想象。*

## 🥚 小彩蛋

> “这不是 Bug，而是命运的触发。”

在 Rhapsody 主题中，部分隐藏的视觉元素（如角标、光带强化等）由**彩蛋触发器（Easter Egg Trigger）**控制。
 触发机制遵循以下协议：

### 🍎 基本触发语法

在 Markdown 文档中插入如下内容即可触发：

```
- [x] 我准备好触发彩蛋啦！ [点这里开关](#egg-prince)

<!-- 任意位置放一个锚点 -->
<span id="egg-prince"></span>
```

- 当复选框被勾选 ✅ 且存在 `#egg-prince` 锚点时，彩蛋将被激活；
- 激活后，`#write` 区域右上角的角标将切换为**彩色版**，并在悬停/聚焦时启动动画；
- 若复选框未勾选或锚点缺失，则保持默认透明状态。

### ✨ 可选扩展语法

你也可以用以下任意元素触发“彩蛋提示区”高亮（仅提示，不激活）：

```
- [ ] [彩蛋触发器](#egg-prince)
- [ ] <span data-egg="trigger" data-text="帅气大王子">帅气大王子</span>
- [ ] ![](./Assets/Logo/帅气大王子.png "帅气大王子")
```

这些任务项将获得淡黄色背景，用于提示当前文档内存在可触发区域。

### ⚙️ 环境要求

- Typora ≥ 1.7.6
- Electron 或 Chromium 内核支持 `:has()` 选择器
- 未开启 “Reduce Motion（减少动态效果）”
- 支持 CSS 自定义属性与伪元素动画

> 💡 若在某些导出环境（例如 PDF 或旧内核 HTML）下无法自动触发，
> 可在文档头部添加内联样式：
>
> ```
> <style>#write::after{--corner-img:var(--corner-img-colored);}</style>
> ```


## 💖 支持与赞助

如果你喜欢 **Rhapsody Typora Theme**，  
并希望我能持续更新、扩展与完善，  
欢迎通过以下方式支持这份创作 🌈

| 🌍 国际支持 | 🇨🇳 中国大陆 |
|--------------|----------------|
| [☕ Ko-fi — The_Radiant_Prince](https://ko-fi.com/gongmingcao) | [💎 爱发电 — 帅气大王子66](https://afdian.com/a/shuaiqidawangzi66) |

> 你的每一份支持，  
> 都将化为新的色彩、新的想法，  
> 让 **Rhapsody** 在 Typora 的世界中持续发光。

---
