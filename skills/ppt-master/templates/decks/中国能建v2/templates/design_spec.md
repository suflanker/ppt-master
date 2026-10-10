---
deck_id: 中国能建v2
kind: deck
category: brand
summary: 中国能建集团与项目部的工作汇报、方案评审与专题汇报模板，采用企业蓝、左侧竖栏目录、圆形编号章节及通用自由内容页，并包含感谢和专家欢迎原型。
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
page_count: 6
placeholders:
  01_cover: ["{{TITLE}}", "{{DATE}}", "{{AUTHOR}}"]
  02_toc:
    - "{{TOC_ITEM_1_TITLE}}"
    - "{{TOC_ITEM_2_TITLE}}"
    - "{{TOC_ITEM_3_TITLE}}"
    - "{{TOC_ITEM_4_TITLE}}"
  03_chapter: ["{{CHAPTER_NUM}}", "{{CHAPTER_TITLE}}"]
  04_content: ["{{PAGE_TITLE}}", "{{CONTENT_AREA}}"]
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
| Representative narrative/page roles | 当前原型覆盖封面、目录、章节页、一个通用内容页、感谢页和专家指导欢迎页；具体选页、重复、顺序与内容处理由当前项目的 Strategist 根据材料决定 |

- 视觉基调为企业蓝标题、左侧蓝红竖栏目录、章节圆形编号及浅色正文底图，强调稳重、清晰与工程秩序。
- 结构上分为两个可复用 Master：CEEC v2 Page 承载通用内容页的浅色底图，CEEC v2 Plain 承载其他页面的白底；页面类型背景由各自Layout提供。
- 封面、感谢页和专家指导页参考《中国能建ppt模板.pptx》第1、4、5页重建；源画布960×540按4/3比例适配1280×720，源示例日期、地点和单位设为可替换内容。
- 目录和章节分别采用toc.pptx与chapter.pptx的1280×720页面设计重建；目录源稿的重叠业务文字仅作为参考，不进入可复用原型。

## II. Color Scheme

| Role | Color | Application |
| --- | --- | --- |
| CEEC blue | #0068B7 | 页面标题及感谢语 |
| Motto blue | #0070C0 | 页眉口号 |
| TOC blue | #0166B5 | 目录左侧竖栏及普通条目 |
| TOC edge red | #E10013 | 目录左侧红边 |
| TOC emphasis red | #E10013 | 目录首项底板 |
| Chapter blue | #0067B4 | 章节左侧分区及指向尖角 |
| Body gray | #404040 | 次级正文 |
| White | #FFFFFF | 封面与目录底色、口号底板、条目文字 |

## III. Typography

| Role | Font stack | Application |
| --- | --- | --- |
| Chinese display | `"思源黑体 CN Bold", "微软雅黑", sans-serif` | 封面标题与日期、内容页大标题、结束语 |
| Chinese body | `"微软雅黑", "PingFang SC", sans-serif` | 目录条目、章节标题与编号、内容页标题和正文 |
| TOC display | `SimSun, Times New Roman, serif` | 左侧白色竖排「目录」 |
| TOC English | `Times New Roman, serif` | 白色竖条内旋转的contents字样 |
| Motto | `"思源黑体 CN Normal", "微软雅黑", sans-serif` | 页眉口号「守正｜创新｜实干｜担当」 |
| Closing contact | `"思源黑体 CN Regular", "微软雅黑", sans-serif` | 感谢页联系信息 |
| Closing date | `"思源黑体 CN Medium", Calibri, "微软雅黑", sans-serif` | 感谢页日期 |

字形按源文件保留思源黑体 CN Bold / Normal（用户确认）；本机未安装该字族时回退微软雅黑，不自动嵌入字体。

## IV. Signature Design Elements

- 封面采用新源PPT第1页的整幅蓝底与红蓝分隔；白色顶板上放置标识与「守正｜创新｜实干｜担当」组合图像，白色标题居中，日期地点置于标题下，单位名称居中置于底部。
- 目录采用toc.pptx：白底、左侧蓝色竖栏与红色窄边，白色竖排「目录」和白条内旋转contents；右侧四项圆角横条，首项红底、其余蓝底，白字带源稿阴影。条目字段包含当前序号与标题，不固定原业务文字。
- 章节采用chapter.pptx：浅色世界地图背景，左半蓝色分区与右向尖角，双圆环承托大号章节编号，右侧蓝色章节标题，右上口号。编号为短居中焦点内容，标题保持左对齐。
- 通用内容页仅保留一个04_content.svg：左上企业箭头标识、右上口号、左对齐蓝色加粗页标题及下方完整留白正文区。标题下横线按content.pptx设置：从(48,80)到(1232,80)，颜色#C9DAE8，粗细2px，归属内容页Layout。沿用浅色底图及红蓝页脚，正文可承载文字、表格、图形或图片。
- 感谢页采用新源PPT第4页：白底、左上企业标识和红蓝横线，左侧大号蓝色固定文字「谢谢 Thanks！」，下方日期可替换，左下企业字标与源联系信息保留。
- 专家指导页采用新源PPT第5页：白色品牌顶板与大面积红底，中央白色固定文案「热烈欢迎专家莅临检查指导」，下方日期地点与底部单位名称可替换。
- 通用正文与目录条目从槽位左上区域开始排布；封面标题、专家欢迎语与章节编号作为居中焦点内容；感谢语按源稿左对齐。

## V. Page Roster

| File | Master | Layout key | PowerPoint picker name | Visual character | Reusable slots |
| --- | --- | --- | --- | --- | --- |
| `01_cover.svg` | CEEC v2 Plain | cover | Cover | 新蓝底、白色顶板标识与口号、居中白色标题 | 标题、日期地点、单位名称 |
| `02_toc.svg` | CEEC v2 Plain | agenda | Agenda | 蓝红左竖栏、右侧四项圆角红蓝横条 | 四个目录条目 |
| `03_chapter.svg` | CEEC v2 Plain | chapter | Chapter | 世界地图底图、左半蓝底和圆形编号、右侧标题 | 章节编号、章节标题 |
| `04_content.svg` | CEEC v2 Page | content | Content | 页眉标识与口号、蓝色页标题、标题下浅蓝横线及自由内容区 | 页面标题、内容区 |
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
| page_background.png | 通用内容页的浅色底图（含页脚红蓝条） |
| chapter_world_map.jpeg | chapter.pptx的浅色世界地图背景 |
| ceec_mark.png | 通用内容页左上企业箭头标识 |

感谢页联系文字按用户指定的源文件保留；这些地址、电话、网址属于源稿内容，未作现行信息核验。历史封面与联系栏资产保留在备份及现有图片目录中，不再由当前原型引用。

## VII. Placeholder Overrides

| Placeholder | Meaning |
| --- | --- |
| `{{CHAPTER_TITLE}}` | 章节页右侧标题 |
| `{{CHAPTER_NUM}}` | 左侧圆形区域内章节编号，例如01 |
| `{{CONTENT_AREA}}` | 通用内容页标题下方的自由内容区 |
| `{{DATE}}` | 封面、专家页的日期地点，感谢页的日期；不固定源2015年示例 |
| `{{AUTHOR}}` | 封面和专家页的当前单位名称 |
