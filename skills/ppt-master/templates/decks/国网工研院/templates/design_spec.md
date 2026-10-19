---
deck_id: 国网工研院
kind: deck
category: brand
summary: 国网工研院科技项目启动、阶段汇报与验收评审模板，以国网绿、绿色波纹与浅色地图底组织封面、目录、章节、正文和结束页。
keywords: [国网工研院, 科技项目, 项目汇报, 国网绿, 央企]
primary_color: "#00746F"
canvas_format: ppt169
canvas_width: 1280
canvas_height: 720
canvas_viewbox: "0 0 1280 720"
source_canvas_width: 960
source_canvas_height: 540
source_viewbox: "0 0 960 540"
replication_mode: fidelity
native_structure_mode: structured
page_count: 7
placeholders:
  02_toc: ["{{TOC_ITEM_1_TITLE}}", "{{TOC_ITEM_2_TITLE}}", "{{TOC_ITEM_3_TITLE}}", "{{TOC_ITEM_4_TITLE}}", "{{TOC_ITEM_5_TITLE}}"]
  03_chapter: ["{{CHAPTER_NUM}}", "{{CHAPTER_TITLE}}", "{{CHAPTER_DESC}}"]
  04a_content_text: ["{{PAGE_TITLE}}", "{{SUBTITLE}}", "{{CONTENT_AREA}}", "{{PAGE_NUM}}"]
  04b_content_table: ["{{PAGE_TITLE}}", "{{SUBTITLE}}", "{{PAGE_NUM}}"]
  04c_content_media: ["{{PAGE_TITLE}}", "{{SUBTITLE}}", "{{CONTENT_AREA}}", "{{PAGE_NUM}}"]
  05_ending: ["{{THANK_YOU}}", "{{ENDING_SUBTITLE}}"]
---

# 国网工研院 — Design Specification

## I. Template Overview

| Application context | Definition |
|---|---|
| Recurring presentation family | 国网工研院（国网电力工程研究院有限公司）科技项目启动会、阶段汇报、技术方案评审与验收汇报 |
| Intended audiences and outcomes | 面向国网总部科技部、院管理层、项目组与外部评审专家；帮助受众快速理解项目目标、课题分工、进度安排与成果指标，并推进评审或下一步决策 |
| Delivery and reading assumptions | 以会议讲解为主，同时需要会后流转与归档；标题、结论与表格在无人讲解时仍可独立阅读 |
| Representative narrative/page roles | 封面、目录、章节分隔、文字正文、表格正文、图文正文、结束页；具体选页、重复与顺序由当前项目的 Strategist 根据材料决定 |

- 视觉基调为白底、国网绿结构色与大面积绿色品牌带；封面、章节页和结束页使用绿色波纹与浅绿圆形构成同一套品牌场景。
- 内容页保持低装饰密度：左上深绿三角与页标题、右上机构标识、顶部细绿线、底部绿线与页码构成固定页框，正文区域留给内容。
- 源稿为 960×540；本模板归一为 1280×720，所有页共用同一 16:9 画布与页框坐标。

## II. Color Scheme

| Role | Color | Application |
|---|---|---|
| 国网绿 | #00746F | 主品牌色；页标题、目录条、页脚线、表格表头、封面/章节/结束页底色 |
| 深绿 | #076654 | 内容页左上三角、内容页副标题、深色强调 |
| 青绿 | #17817C | 波纹带的次层色、目录英文标签与辅助结构 |
| 浅绿 | #CDDAD3 | 正文左轨、表格浅色行、图片边框 |
| 雾绿 | #E8F1EE | 图片占位底、浅色面板 |
| 墨色 | #1F2A28 | 正文与表格单元格文字 |
| 分隔线 | #D6E2DF | 表格网格与页眉细线 |
| 白色 | #FFFFFF | 内容页底、封面顶/底栏、反白文字 |

## III. Typography

| Role | Font stack | Size / weight | Application |
|---|---|---|---|
| 中文标题与正文 | `Microsoft YaHei, PingFang SC, sans-serif` | — | 全模板统一；Windows 优先微软雅黑，macOS 回退苹方 |
| 封面主标题 | 同上 | 54 px / bold | 居中于绿色品牌带，短标题两行以内 |
| 封面副标题 | 同上 | 32 px / bold | 会议或汇报类型 |
| 封面机构与日期 | 同上 | 28 / 26 px / bold | 白色底栏，国网绿文字 |
| 目录标题 | 同上 | 128 px / bold | 左侧竖排“目 / 录”两字，配深色竖线 |
| 目录条目 | 同上 | 32 px / bold | 右侧五行列表，白色文字，绿色条目底；编号 26 px |
| 章节数字 | 同上 | 128 px / bold | 浅绿大数字，左侧圆形场景内 |
| 章节标题 / 说明 | 同上 | 60 / 22 px / bold / normal | 白色文字，右侧栏 |
| 内容页标题 | 同上 | 32 px / bold | 国网绿，左上页眉 |
| 内容页副标题 | 同上 | 22 px / bold | 深绿，标题下方关键信息 |
| 正文 | 同上 | 22 px / normal | 墨色，左对齐，行距约 1.6 倍 |
| 表格表头 / 单元格 | 同上 | 19 / 19 px | 表头反白加粗，单元格墨色 |
| 页码 | 同上 | 18 px / bold | 国网绿，右下角 |
| 结束语 / 副标题 | 同上 | 72 / 26 px / bold / normal | 居中于绿色品牌带 |

## IV. Signature Design Elements

- **品牌带**：封面与结束页使用白色顶栏、白色底栏与中部 440 px 高国网绿横带；横带内左侧铺 `wave_ribbon.png` 波纹，右缘保留纯色留白，形成“左动右静”的品牌场景。
- **浅色地图底**：封面、目录与内容页使用 `world_map_bg.png` 满幅铺底，透明度约 0.6–0.72，保持白底可读性而不引入额外色块。
- **内容页页框**：左上为深绿三角 `M 0 16 L 0 78 L 52 47 Z`，页标题从 x=68 起排；顶部 y=88 的 6 px 国网绿细线与右上角标识构成横向页眉；底部 y=712 的 8 px 国网绿线承托右下页码。
- **目录版式**：左上角放工研院组合标识；左侧竖排 128 px 国网绿“目 / 录”，右侧深色竖线分隔；右侧五行 700×88 国网绿条目，条目带浅绿投影、白色圆形编号 1–5，文字 32 px 反白。
- **章节场景**：全幅国网绿底，左侧 300 px 半径浅绿圆与 330 px 细圆环叠出景深，128 px 浅绿数字压在圆心；右侧以细白竖线分隔标题与说明。
- **表格**：表头国网绿反白，正文行白/雾绿交替，1 px 浅绿网格；表格由原生 table 槽承载，保持可编辑。
- **居中例外**：封面标题、封面元信息与结束语采用居中轴对齐；其余正文槽均左上起排、左对齐，以适配长文本替换。

## V. Page Roster

| File | Master | Layout key | PowerPoint picker name | Visual character | Reusable slots |
|---|---|---|---|---|---|
| `01_cover.svg` | SGCC Institute | cover | Cover | 白顶栏 + 国网绿波纹带 + 白底栏；左上机构标识 | display title（body idx 1）、subtitle、author、date；标题居中，bounds 120 190 1040 150 |
| `02_toc.svg` | SGCC Institute | agenda | Agenda | 左上角组合标识 + 浅色地图底 + 左侧竖排“目 录” + 右侧五行绿色编号条目 | 五个 body 条目槽（idx 1–5），每槽 600×88；竖排标题固定 |
| `03_chapter.svg` | SGCC Institute | chapter | Chapter | 全幅国网绿 + 浅绿大圆/圆环 + 128 px 章节数字 | chapter number（body idx 1）、display title（body idx 3）、chapter description（body idx 2）；左数字右标题 |
| `04a_content_text.svg` | SGCC Institute | content-text | Content – Text | 白底地图 + 固定页眉/页脚 + 左轨正文 | page title、subtitle、content area、page number；正文槽 1112×472 |
| `04b_content_table.svg` | SGCC Institute | content-table | Content – Table | 白底地图 + 固定页眉/页脚 + 原生表格 | page title、subtitle、table、page number；表格槽 1144×456，4 列×4 行示例 |
| `04c_content_media.svg` | SGCC Institute | content-media | Content – Media | 白底地图 + 左文右图双栏 | page title、subtitle、content area、picture、page number；正文槽 620×472，图片槽 460×460 |
| `05_ending.svg` | SGCC Institute | closing | Closing | 与封面同构的白顶栏 + 国网绿波纹带 + 白底栏 | display title（body idx 2）、ending subtitle；居中结束语 |

- 每个内容页的固定页眉、页脚、标识与页码位置一致；三种内容页只在正文承载方式上不同。
- 封面、章节与结束页的大字号主标题使用 `body` 槽承载，以保留 54 / 60 / 72 px 的直接字号；PowerPoint 的 `title` 槽由 Master 统一为内容页的 24 pt，不适合承载品牌页的大标题。内容页仍使用标准 `title` 槽。
- 目录页固定 4 项；如需增减条目，应在当前项目内新增 Layout，而不是改写本原型。

## VI. Assets

| File | Intended usage |
|---|---|
| `logo_lockup.png` | “国家电网 + 国网电力工程研究院有限公司”组合标识；封面/结束页左上，内容页右上 |
| `wave_ribbon.png` | 封面与结束页绿色品牌带左侧的波纹装饰 |
| `world_map_bg.png` | 封面、目录与内容页的满幅浅色世界地图底 |
| `media_placeholder.png` | 图文内容页图片槽的中性占位图；替换为项目实拍或示意图 |

未纳入：源稿项目照片、目录图标、章节标题位图、原 PPTX 默认版式。它们属于当前汇报内容或源包结构，不作为可复用身份资产。

## VII. Placeholder Overrides

| Page | Markers | Note |
|---|---|---|
| `01_cover.svg` | `{{TITLE}}` / `{{SUBTITLE}}` / `{{AUTHOR}}` / `{{DATE}}` | 主标题为 body 槽，保留 54 px 直排字号 |
| `02_toc.svg` | `{{TOC_ITEM_1_TITLE}}` … `{{TOC_ITEM_5_TITLE}}` | 竖排标题“目 / 录”与编号为固定文字；五行条目为独立 body 槽 |
| `03_chapter.svg` | `{{CHAPTER_NUM}}` / `{{CHAPTER_TITLE}}` / `{{CHAPTER_DESC}}` | 章节数字、标题与说明分列左右；标题为 body 槽 |
| `04b_content_table.svg` | `{{PAGE_TITLE}}` / `{{SUBTITLE}}` / `{{PAGE_NUM}}` | 表格由原生 table 槽承载，无文本占位符 |
| `04c_content_media.svg` | `{{PAGE_TITLE}}` / `{{SUBTITLE}}` / `{{CONTENT_AREA}}` / `{{PAGE_NUM}}` | 图片由 picture 槽承载，无文本占位符 |
| `05_ending.svg` | `{{THANK_YOU}}` / `{{ENDING_SUBTITLE}}` | 结束语为 body 槽，保留 72 px 直排字号 |
