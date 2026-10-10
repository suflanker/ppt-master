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
page_count: 7
placeholders:
  01_cover: ["{{TITLE}}", "{{DATE}}", "{{AUTHOR}}"]
  02_toc:
    - "{{TOC_ITEM_1_TITLE}}"
    - "{{TOC_ITEM_2_TITLE}}"
    - "{{TOC_ITEM_3_TITLE}}"
    - "{{TOC_ITEM_4_TITLE}}"
    - "{{TOC_ITEM_5_TITLE}}"
  03_chapter_section_list: ["{{CHAPTER_TITLE}}", "{{CHAPTER_ITEMS}}"]
  04a_content_simple: ["{{PAGE_TITLE}}", "{{CONTENT_AREA}}"]
  04b_content_photo_cards:
    - "{{PAGE_TITLE}}"
    - "{{CAPTION}}"
    - "{{BLOCK_1_TITLE}}"
    - "{{BLOCK_1_BODY}}"
    - "{{BLOCK_2_TITLE}}"
    - "{{BLOCK_2_BODY}}"
    - "{{BLOCK_3_TITLE}}"
    - "{{BLOCK_3_BODY}}"
  05_ending: ["{{DATE}}"]
  06_expert_welcome: ["{{DATE}}", "{{AUTHOR}}"]
---

# 中国能建 v2 — Design Specification

## I. Template Overview

| Application context | Definition |
| --- | --- |
| Recurring presentation family | 集团与项目部的工作汇报、方案评审、专项治理与专题汇报 |
| Intended audiences and outcomes | 面向集团管理层、项目部与外部评审方；帮助受众理解背景、结论与实施安排，并推进评审或下一步决策 |
| Delivery and reading assumptions | 以现场讲解为主，同时需要会后流转与复核；页面保留关键结论与必要上下文 |
| Representative narrative/page roles | 当前原型覆盖封面、目录、章节页、通用内容页、照片卡片内容页、感谢页和专家指导欢迎页；具体选页、重复、顺序与内容处理由当前项目的 Strategist 根据材料决定 |

- 视觉基调为企业蓝标题与编号、浅色底图（页脚红蓝条）、银色横幅和编号卡片，强调稳重、清晰与工程秩序。
- 结构上分为两个可复用 Master：CEEC v2 Page 承载章节与内容页的浅色底图，CEEC v2 Plain 承载封面、目录、感谢页和专家指导页的白底；页面类型背景由各自Layout提供。
- 封面、感谢页和专家指导页参考《中国能建ppt模板.pptx》第1、4、5页重建；源画布960×540按4/3比例适配1280×720，源示例日期、地点和单位设为可替换内容。

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
| Closing contact | `"思源黑体 CN Regular", "微软雅黑", sans-serif` | 感谢页联系信息 |
| Closing date | `"思源黑体 CN Medium", Calibri, "微软雅黑", sans-serif` | 感谢页日期 |

字形按源文件保留思源黑体 CN Bold / Normal（用户确认）；本机未安装该字族时回退微软雅黑，不自动嵌入字体。

## IV. Signature Design Elements

- 封面采用新源PPT第1页的整幅蓝底与红蓝分隔；白色顶板上放置标识与「守正｜创新｜实干｜担当」组合图像，白色标题居中，日期地点置于标题下，单位名称居中置于底部。
- 目录页为白底：左上「目录/CONTENTS」深蓝标题配天蓝分隔线，右侧 3+2 两列条目，条条由蓝色序号牌、蓝色底板与白色条目文字组成。
- 内容页使用浅色底图（含页脚红蓝条）；章节页在浅色底图上压整幅银色横幅承托白色大标题，横幅下方左对齐排布本章章节列表。
- 通用内容页承载没有固定图文结构的自由论述：沿用照片卡片页的页眉与标题样式（左上企业箭头标识、右上口号、左对齐蓝色加粗页标题），标题下方整幅留白作为自由内容区，不预设卡片、图片框或装饰线。
- 照片卡片页：左上企业箭头标识、右上口号；左侧为带柔和外阴影的照片框与下方蓝色说明，右侧为三段编号卡片（圆角编号牌 + 蓝色标题 + 正文）。
- 感谢页采用新源PPT第4页：白底、左上企业标识和红蓝横线，左侧大号蓝色固定文字「谢谢 Thanks！」，下方日期可替换，左下企业字标与源联系信息保留。
- 专家指导页采用新源PPT第5页：白色品牌顶板与大面积红底，中央白色固定文案「热烈欢迎专家莅临检查指导」，下方日期地点与底部单位名称可替换。
- 图片说明、卡片正文与通用内容页内容区均从槽位左上角开始排布；封面标题与结束语属于短焦点内容，在完整边界内居中。

## V. Page Roster

| File | Master | Layout key | PowerPoint picker name | Visual character | Reusable slots |
| --- | --- | --- | --- | --- | --- |
| `01_cover.svg` | CEEC v2 Plain | cover | Cover | 新蓝底、白色顶板标识与口号、居中白色标题 | 标题、日期地点、单位名称 |
| `02_toc.svg` | CEEC v2 Plain | agenda | Agenda | 白底、深蓝目录标题、两列编号条目 | 五个目录条目 |
| `03_chapter_section_list.svg` | CEEC v2 Page | chapter | Chapter | 银色横幅承托白色大标题、横幅下方章节列表 | 章节标题、章节列表 |
| `04a_content_simple.svg` | CEEC v2 Page | content | Content | 页眉标识与口号、左对齐蓝色页标题、标题下整幅自由内容区 | 页面标题、内容区 |
| `04b_content_photo_cards.svg` | CEEC v2 Page | photo_cards | Photo and Numbered Cards | 左照片与说明、右三张编号卡片 | 页面标题、图片、图片说明、三组卡片标题与正文 |
| `05_ending.svg` | CEEC v2 Plain | closing | Closing | 白底、左侧「谢谢 Thanks！」、日期与联系栏 | 日期（感谢语固定） |
| `06_expert_welcome.svg` | CEEC v2 Plain | expert_welcome | Expert Welcome | 白顶板品牌标识、红底白色专家欢迎语 | 日期地点、单位名称（欢迎语固定） |

## VI. Assets

| File | Intended usage |
| --- | --- |
| cover_updated.png | 新源PPT第1页的蓝底、白顶带及红蓝分隔 |
| brand_motto_updated.png | 新源PPT提供的企业标识与「守正｜创新｜实干｜担当」组合图像，封面和专家指导页使用 |
| ending_updated.png | 新源PPT第4页的透明底企业标识及红蓝横线，合成在白底上 |
| ending_wordmark_updated.png | 新源PPT第4页左下企业字标 |
| expert_red_background.png | 新源PPT第5页的红底、白顶带及红蓝分隔 |
| page_background.png | 章节与内容页的浅色底图（含页脚红蓝条） |
| banner_strip.png | 章节页蓝调横幅色带：源图片的双色调效果（黑→`#0A86FC`）与 `#2683C6` 底填充、左侧 9.36% 裁切一并烘焙为成品位图 |
| ceec_mark.png | 内容页（通用内容页、照片卡片页）左上企业箭头标识 |

感谢页联系文字按用户指定的源文件保留；这些地址、电话、网址属于源稿内容，未作现行信息核验。历史封面与联系栏资产保留在备份及现有图片目录中，不再由当前原型引用。

## VII. Placeholder Overrides

| Placeholder | Meaning |
| --- | --- |
| `{{CHAPTER_TITLE}}` | 章节页横幅内的章节名 |
| `{{CHAPTER_ITEMS}}` | 章节页横幅下方的章节列表；多行承载于同一文本框中，序号写在文本内 |
| `{{CONTENT_AREA}}` | 通用内容页标题下方的自由内容区 |
| `{{CAPTION}}` | 照片下方的蓝色图片说明 |
| `{{DATE}}` | 封面、专家页的日期地点，感谢页的日期；不固定源2015年示例 |
| `{{AUTHOR}}` | 封面和专家页的当前单位名称 |
| `{{BLOCK_1_TITLE}}` / `{{BLOCK_1_BODY}}` | 第一张编号卡片的标题与正文；编号牌 01/02/03 为固定装饰 |
| `{{BLOCK_2_TITLE}}` / `{{BLOCK_2_BODY}}` | 第二张编号卡片的标题与正文 |
| `{{BLOCK_3_TITLE}}` / `{{BLOCK_3_BODY}}` | 第三张编号卡片的标题与正文 |
