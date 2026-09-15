---
deck_id: 中国能建
kind: deck
category: brand
summary: 中国能建集团企业汇报、战略规划与项目总结，用于说明方案并对齐决策和下一步；采用深蓝稳重、结构清晰的央企视觉。
keywords: [中国能建, 能源建设, 集团汇报, 战略规划]
primary_color: "#0068B7"
canvas_format: ppt169
canvas_width: 1280
canvas_height: 720
canvas_viewbox: "0 0 1280 720"
source_canvas_width: 1280
source_canvas_height: 720
source_viewbox: "0 0 1280 720"
replication_mode: standard
native_structure_mode: structured
page_count: 5
placeholders:
  05_ending: []
---

# 中国能建 — Design Specification

## I. Template Overview

| Application context | Definition |
| --- | --- |
| Recurring presentation family | 集团年度汇报、战略规划、项目总结与专题方案 |
| Intended audiences and outcomes | 面向集团管理层、项目干系人与外部合作方；帮助受众理解方案背景与结论，并推进评审或下一步决策 |
| Delivery and reading assumptions | 以现场汇报为主，同时需要会后流转与复核；页面保留关键结论与必要上下文，不依赖口头说明才能辨认主题 |
| Representative narrative/page roles | 当前原型覆盖封面、目录、章节、开放内容和结束语；具体选页、重复、顺序与内容处理由当前项目的 Strategist 根据材料决定 |

- 视觉基调为深蓝品牌底、白色内容承载区和浅灰信息卡片，强调稳重、专业与层级清晰。
- 结构上使用单一 CEEC Master 承载白底页面；封面照片、章节页深蓝覆盖、目录卡片与内容页承载区等品牌色面均属于各页 Layout，不按页面拆分重复 Master。

## II. Color Scheme

| Role | Color | Application |
| --- | --- | --- |
| CEEC blue | #0068B7 | 深色页面底、编号标签、结构线、标题文字 |
| Panel blue | #005DA2 | 内容页章节标题栏 |
| Accent blue | #0070C0 | 章节页大号编号 |
| Deep blue rule | #002F7B | 目录页顶部细线 |
| Content gray | #F2F2F2 | 内容页承载区 |
| Divider gray | #808080 | 目录页双竖线 |
| Text black | #000000 | 正文文字 |
| White | #FFFFFF | 浅色页面底、反白文字 |

## III. Typography

| Role | Font stack | Application |
| --- | --- | --- |
| Chinese title and body | `Microsoft YaHei, PingFang SC, sans-serif` | 标题、正文、目录项与章节文字 |
| Latin title and folio | `Arial, Microsoft YaHei, PingFang SC, sans-serif` | 内容页标题与页码 |
| Latin body | `Times New Roman, Microsoft YaHei, PingFang SC, sans-serif` | 内容页章节标题与正文 |

字体栈仅使用常见系统字体；Windows 优先微软雅黑，macOS 可回退苹方，不依赖额外字体安装。

## IV. Signature Design Elements

- 封面保留半幅浅色品牌底图与居中大号标识，标题簇居中排布；底图以图片裁切方式铺满下部区域。
- 章节页使用左半幅品牌蓝覆盖、右向箭头切口、白色编号圆盘与虚线外环，编号与章节标题分列圆盘内外。
- 内容页使用“左上页面标题 + 深蓝章节标题栏 + 浅灰承载区”的固定页眉结构，右上角保留小号品牌标识，页脚承载日期与页码。
- 目录页为白底三行卡片导航，左侧大号图形标题，右侧卡片带蓝色编号铭牌与斜角装饰。
- 结束页复用居中品牌标识与整幅蓝色色带，结束语以固定文案居中排布。

## V. Page Roster

| File | Master | Layout key | PowerPoint picker name | Visual character | Reusable slots |
| --- | --- | --- | --- | --- | --- |
| `01_cover.svg` | CEEC | cover | Cover | 深蓝底、下部品牌底图、居中标题簇 | 标题、副标题、日期 |
| `02_toc.svg` | CEEC | agenda | Agenda | 白底三行卡片目录、左侧图形标题 | 三个目录项 |
| `03_chapter.svg` | CEEC | section | Section Header | 左半幅深蓝、编号圆盘与右侧章节标题 | 章节号、章节标题 |
| `04_content.svg` | CEEC | content | Title and Content | 页眉标题与章节栏、浅灰开放承载区 | 页面标题、章节标题、内容对象、日期、页码 |
| `05_ending.svg` | CEEC | closing | Closing | 居中标识与整幅蓝色色带的结束语 | 无（固定结束语） |

## VI. Assets

| File | Intended usage |
| --- | --- |
| brand_logo.png | 封面、目录页与结束页的品牌标识 |
| cover_bg.png | 封面下部品牌底图 |
| chapter_bg.jpeg | 章节页背景照片 |
| logo_top_right.png | 内容页右上角小号标识 |
| content_watermark.png | 内容页承载区水印 |
| toc.png | 目录页左侧图形标题 |
