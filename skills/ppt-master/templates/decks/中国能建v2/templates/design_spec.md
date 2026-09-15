---
deck_id: 中国能建v2
kind: deck
category: brand
summary: 中国能建集团与项目部的工作汇报、方案评审与专题汇报，用于说明方案并对齐决策和下一步；采用企业蓝配银色横幅与编号卡片的央企视觉。
keywords: [中国能建, 集团汇报, 方案评审, 分包监管]
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
  01_cover: ["{{TITLE}}", "{{DATE}}"]
  02_toc:
    - "{{TOC_ITEM_1_TITLE}}"
    - "{{TOC_ITEM_2_TITLE}}"
    - "{{TOC_ITEM_3_TITLE}}"
    - "{{TOC_ITEM_4_TITLE}}"
    - "{{TOC_ITEM_5_TITLE}}"
  03a_content_section_list: ["{{PAGE_TITLE}}", "{{CONTENT_AREA}}"]
  03b_content_photo_cards:
    - "{{PAGE_TITLE}}"
    - "{{CAPTION}}"
    - "{{BLOCK_1_TITLE}}"
    - "{{BLOCK_1_BODY}}"
    - "{{BLOCK_2_TITLE}}"
    - "{{BLOCK_2_BODY}}"
    - "{{BLOCK_3_TITLE}}"
    - "{{BLOCK_3_BODY}}"
  04_ending: []
---

# 中国能建 v2 — Design Specification

## I. Template Overview

| Application context | Definition |
| --- | --- |
| Recurring presentation family | 集团与项目部的工作汇报、方案评审、专项治理与专题汇报 |
| Intended audiences and outcomes | 面向集团管理层、项目部与外部评审方；帮助受众理解背景、结论与实施安排，并推进评审或下一步决策 |
| Delivery and reading assumptions | 以现场讲解为主，同时需要会后流转与复核；页面保留关键结论与必要上下文 |
| Representative narrative/page roles | 当前原型覆盖封面、目录、章节概览、三点论述内容页与结束语；具体选页、重复、顺序与内容处理由当前项目的 Strategist 根据材料决定 |

- 视觉基调为企业蓝标题与编号、浅色底图（页脚红蓝条）、银色横幅和编号卡片，强调稳重、清晰与工程秩序。
- 结构上分为两个可复用 Master：CEEC v2 Page 承载内容页与结束页的浅色底图，CEEC v2 Plain 承载封面与目录的白底；两个家族按底图分工，不是按单个版式拆分出的重复 Master。

## II. Color Scheme

| Role | Color | Application |
| --- | --- | --- |
| CEEC blue | #0068B7 | 页面标题、编号牌、卡片标题、结束语 |
| Motto blue | #0070C0 | 页眉口号 |
| TOC deep blue | #2F5597 | 目录页主标题 |
| Rule blue | #5B9BD5 | 目录页分隔线 |
| Item blue | #558ED5 | 目录条目底板与序号牌 |
| Caption blue | #4472C4 | 图片说明文字 |
| Body gray | #404040 | 次级正文 |
| White | #FFFFFF | 封面与目录底色、口号底板、条目文字 |

## III. Typography

| Role | Font stack | Application |
| --- | --- | --- |
| Chinese display | `"思源黑体 CN Bold", "微软雅黑", sans-serif` | 封面标题与日期、内容页大标题、结束语 |
| Chinese body | `"微软雅黑", "PingFang SC", sans-serif` | 目录、内容页页面标题、卡片标题与正文 |
| Motto | `"思源黑体 CN Normal", "微软雅黑", sans-serif` | 页眉口号「守正｜创新｜实干｜担当」 |

字形按源文件保留思源黑体 CN Bold / Normal（用户确认）；本机未安装该字族时回退微软雅黑，不自动嵌入字体。

## IV. Signature Design Elements

- 封面用整幅企业底图承载白顶带、标识与红蓝斜切分隔；白色底板承托页眉口号，标题与日期沿中轴居中排布。
- 目录页为白底：左上「目录/CONTENTS」深蓝标题配天蓝分隔线，右侧 3+2 两列条目，条条由蓝色序号牌、蓝色底板与白色条目文字组成。
- 内容页与结束页共用浅色底图（含页脚红蓝条）作为页面底色；章节页在浅色底图上压整幅银色横幅承托白色大标题，正文列表左对齐。
- 三点卡片页：左上企业箭头标识、右上口号；左侧为带柔和外阴影的照片框与下方蓝色说明，右侧为三段编号卡片（圆角编号牌 + 蓝色标题 + 正文）。
- 结束页保持大留白：居中大号蓝色结束语（固定文案「感谢聆听，敬请指正」）、左下透明底企业联系栏、右上口号。
- 图片说明与卡片正文均从槽位左上角开始排布；封面标题与结束语属于短焦点内容，在完整边界内居中。

## V. Page Roster

| File | Master | Layout key | PowerPoint picker name | Visual character | Reusable slots |
| --- | --- | --- | --- | --- | --- |
| `01_cover.svg` | CEEC v2 Plain | cover | Cover | 整幅企业底图、白底口号板、居中标题簇 | 标题、日期 |
| `02_toc.svg` | CEEC v2 Plain | agenda | Agenda | 白底、深蓝目录标题、两列编号条目 | 五个目录条目 |
| `03a_content_section_list.svg` | CEEC v2 Page | section_list | Section List | 银色横幅承托白色大标题、左对齐章节列表 | 页面标题、章节列表 |
| `03b_content_photo_cards.svg` | CEEC v2 Page | photo_cards | Photo and Numbered Cards | 左照片与说明、右三张编号卡片 | 页面标题、图片、图片说明、三组卡片标题与正文 |
| `04_ending.svg` | CEEC v2 Page | closing | Closing | 居中大号固定结束语、左下透明底联系栏 | 无（固定结束语） |

## VI. Assets

| File | Intended usage |
| --- | --- |
| cover_artwork.png | 封面整幅企业底图（含白顶带、标识与红蓝斜切分隔） |
| page_background.png | 内容页与结束页的浅色底图（含页脚红蓝条） |
| banner_strip.png | 章节页蓝调横幅色带：源图片的双色调效果（黑→`#0A86FC`）与 `#2683C6` 底填充、左侧 9.36% 裁切一并烘焙为成品位图 |
| ceec_mark.png | 三点卡片页左上企业箭头标识 |
| contact_block.png | 结束页左下企业联系栏；白底已抠除，按透明背景合成在页面底图上 |

## VII. Placeholder Overrides

| Placeholder | Meaning |
| --- | --- |
| `{{CONTENT_AREA}}` | 章节页的章节列表；两行章节名承载于同一文本框中，序号写在文本内 |
| `{{CAPTION}}` | 照片下方的蓝色图片说明 |
| `{{BLOCK_1_TITLE}}` / `{{BLOCK_1_BODY}}` | 第一张编号卡片的标题与正文；编号牌 01/02/03 为固定装饰 |
| `{{BLOCK_2_TITLE}}` / `{{BLOCK_2_BODY}}` | 第二张编号卡片的标题与正文 |
| `{{BLOCK_3_TITLE}}` / `{{BLOCK_3_BODY}}` | 第三张编号卡片的标题与正文 |
