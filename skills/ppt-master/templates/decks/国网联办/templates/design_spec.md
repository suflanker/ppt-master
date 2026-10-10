---
deck_id: 国网联办
kind: deck
category: brand
summary: 国网联办能源研究、项目方案与工作汇报模板，以绿色品牌框架组织封面、目录、自由正文和结束页。
keywords: [国网联办, 能源研究, 项目方案, 工作汇报]
primary_color: "#00706B"
canvas_format: ppt169
canvas_width: 1280
canvas_height: 720
canvas_viewbox: "0 0 1280 720"
source_canvas_width: 1280
source_canvas_height: 720
source_viewbox: "0 0 1280 720"
replication_mode: standard
native_structure_mode: structured
page_count: 4
placeholders:
  01_cover: ["{{TITLE}}", "{{AUTHOR}}", "{{DATE}}"]
  02_toc: ["{{TOC_ITEM_1_TITLE}}", "{{TOC_ITEM_2_TITLE}}", "{{TOC_ITEM_3_TITLE}}", "{{TOC_ITEM_4_TITLE}}", "{{TOC_ITEM_5_TITLE}}", "{{TOC_ITEM_6_TITLE}}", "{{TOC_ITEM_7_TITLE}}", "{{TOC_ITEM_8_TITLE}}"]
  03_content: ["{{PAGE_TITLE}}", "{{CONTENT_AREA}}", "{{PAGE_NUM}}"]
  04_ending: []
---

# 国网联办 — Design Specification

## I. Template Overview

| Application context | Definition |
| --- | --- |
| Recurring presentation family | 能源研究、项目建设方案及工作汇报 |
| Intended audiences and outcomes | 面向管理、研究、研发和评审人员，支持概况说明、方案讨论、工作进展与行动安排 |
| Delivery and reading assumptions | 现场讲述结合会后阅读，内容页保留完整可编辑正文区 |
| Representative narrative/page roles | 封面、目录、通用内容、结束四个原型 |

源文件《国网联办.pptx》为带业务内容的汇报稿。本模板提炼其视觉框架，名称沿用用户指定“国网联办”。源稿中的项目名称、业务章节、表格、架构和计划作为设计证据；具体内容与页数由新汇报材料决定。

## II. Color Scheme

| Role | HEX | Application |
| --- | --- | --- |
| 主色 | #00706B | 标题、目录序号与结束语 |
| 页眉标记 | #00706A | 内容页左侧绿色竖条 |
| 正文 | #333333 | 自由内容区 |
| 辅助文字 | #666666 | 署名和页码 |
| 规则线 | #DFDFD7 | 标题下横线及封面浅色横条 |
| 白色 | #FFFFFF | 页面底色及封面横带内的标题 |

## III. Typography

| Role | Typeface | Reference size |
| --- | --- | --- |
| 封面标题 | Microsoft YaHei, Arial, sans-serif，粗体 | 44px |
| 内容页标题 | Microsoft YaHei, Arial, sans-serif，粗体 | 34px |
| 目录条目 | Microsoft YaHei, Arial, sans-serif | 30px |
| 正文与署名 | Microsoft YaHei, Arial, sans-serif | 24px |
| 页码 | Microsoft YaHei, Arial, sans-serif | 16px |
| 结束语 | Microsoft YaHei, Arial, sans-serif，粗体 | 64px |

字号为模板原型参考。新项目根据素材和阅读方式确定正文层级，使用同一通用内容框架排版。

## IV. Signature Design Elements

封面使用源绿色横带背景及左上品牌图像，右上设置署名，横带内偏右设置白色主标题，横带下右侧设置日期。日期框完整置于画布内。

目录沿用淡绿色能源景观和右上标识；左侧为目录标题，中部偏右为疏朗的八项编号列表。绿色序号与深灰条目保持层级。目录原型提供八个条目槽，当前材料少于八项时相应条目可为空；重新组织条目数量时由新项目声明对应版式。

通用内容页保留顶部右侧标识、左侧绿色竖条、标题下浅色规则线和底部城市、风机、光伏景观。页标题左对齐；其下是一个完整自由正文区。原稿各业务内容页统一归纳至此原型，正文可承载段落、列表、表格及图形，无固定业务字段、层数或场景。

结束页使用同一能源景观底图和标识，中间固定显示用户指定的源稿文字“汇报完毕，谢谢！”，保持大留白。封面主标题、结束语是居中短焦点内容；正文从框内左上开始，左对齐。

## V. Page Roster

| File | Master | Layout key | PowerPoint picker name | Visual character | Reusable slots |
| --- | --- | --- | --- | --- | --- |
| `01_cover.svg` | Guowang Plain | cover | Cover | 绿色横带、左上品牌图像、右侧白色标题 | 标题532 265 700 125；署名600 135 620 70；日期1030 487 210 62 |
| `02_toc.svg` | Guowang Plain | toc | Table of Contents | 淡色能源底图、左侧目录标题、右侧编号列表 | 八个目录条目，单项480 125起、650×48，纵向间隔59px |
| `03_content.svg` | Guowang Plain | content | Title and Free Content | 企业绿色标题、右上标识、下方完整留白正文区 | 标题67 27 880 65；正文76 130 1128 440；页码1120 666 85 28 |
| `04_ending.svg` | Guowang Plain | ending | Closing | 能源底图、居中绿色结束语 | 结束语200 245 880 140 |

## VI. Assets

| File | Role |
| --- | --- |
| images/cover_background.png | 源封面的绿色横带及弧线纹理 |
| images/brand_lockup.png | 源稿提供的国家电网与全球能源互联网集团标识图像 |
| images/content_background.png | 源内容页的城市、风机、光伏和淡绿色起伏景观 |

三张位图直接复用源资产；文字与几何由新原型原生绘制。原稿两张业务表格的预览图片不进入精简模板。
