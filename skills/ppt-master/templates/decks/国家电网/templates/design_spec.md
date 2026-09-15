---
deck_id: 国家电网
kind: deck
category: brand
summary: 国家电网内部汇报、项目进展与技术方案，用于说明进展并对齐决策和下一步；采用青绿稳重、左侧结构栏的央企视觉。
keywords: [国家电网, 电力, 央企汇报, 项目进展]
primary_color: "#249087"
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
---

# 国家电网 — Design Specification

## I. Template Overview

| Application context | Definition |
| --- | --- |
| Recurring presentation family | 内部工作汇报、项目进展说明、技术方案介绍与阶段性总结 |
| Intended audiences and outcomes | 面向内部管理层、项目团队与技术评审者；帮助受众理解进展与结论，并推进评审或下一步安排 |
| Delivery and reading assumptions | 以会议讲解为主，同时需要会后流转；页面保留关键结论与必要上下文，不依赖口头说明才能辨认主题 |
| Representative narrative/page roles | 当前原型覆盖封面、目录、开放内容和结束语；具体选页、重复、顺序与内容处理由当前项目的 Strategist 根据材料决定 |

- 视觉基调为青绿品牌色、浅色渐变底与白色内容卡片，强调稳重、清晰与专业。
- 结构上分为两个可复用 Master 家族：SGCC Photo 服务封面与结束页，SGCC Light 服务目录与正文；它们按图片底与浅色底两套视觉体系分工，不是按单个 Layout 拆分出的重复 Master。

## II. Color Scheme

| Role | Color | Application |
| --- | --- | --- |
| State Grid teal | #249087 | 深色页面底、高亮目录项、青绿结构元素 |
| Deep teal | #18605A | 目录项文字与深色强调 |
| Panel teal | #1D8578 | 目录页左侧栏渐变、内容页横幅渐变起点 |
| Banner teal | #18665C | 内容页横幅渐变终点 |
| Light aqua | #F1F9FC | 浅色页面底与内容承载区 |
| Card aqua | #D4F4F2 | 浅色渐变底与高亮卡片渐变终点 |
| White | #FFFFFF | 内容卡片、正文页底与反白文字 |
| Text black | #000000 | 内容页标题与正文 |

## III. Typography

| Role | Font stack | Application |
| --- | --- | --- |
| Chinese title and body | `Microsoft YaHei, PingFang SC, sans-serif` | 封面、目录、内容与结束页全部可见文字 |

字体栈仅使用常见系统字体；Windows 优先微软雅黑，macOS 可回退苹方，不依赖额外字体安装。

## IV. Signature Design Elements

- 封面与结束页共用整幅品牌照片底、下半幅深色渐隐遮罩与左上角小号标识；两页除文字槽位外不引入额外装饰。
- 目录页为浅色渐变底加满幅浅色底图，右侧四行白色圆角卡片，首行使用高亮渐变与青色描边，并在行尾保留三段递进透明度的箭头装饰。
- 内容页使用“左上页面标题 + 青绿横幅 + 白色内容卡片”的固定结构，横幅右上保留小号页眉图标；横幅内叠加以 20% 透明度铺设的品牌照片。
- 目录页与内容页共用同一浅色 Master 底色，页面级渐变与照片均位于 Layout 层。

## V. Page Roster

| File | Master | Layout key | PowerPoint picker name | Visual character | Reusable slots |
| --- | --- | --- | --- | --- | --- |
| `01_cover.svg` | SGCC Photo | cover | Cover | 品牌照片底、渐隐遮罩与左上标识，左对齐标题簇 | 标题、副标题、日期 |
| `02_toc.svg` | SGCC Light | agenda | Agenda | 浅色渐变底、四行卡片目录与首行高亮 | 四个目录项 |
| `03_content.svg` | SGCC Light | content | Title and Content | 青绿横幅与白色开放内容卡片 | 页面标题、章节名称、内容对象 |
| `04_ending.svg` | SGCC Photo | closing | Closing | 品牌照片底与居中结束语 | 结束标题、结束副标题 |

## VI. Assets

| File | Intended usage |
| --- | --- |
| cover_bg.png | 封面与结束页的整幅品牌照片底 |
| logo_small.png | 封面与结束页左上角小号标识 |
| toc_bg.png | 目录页满幅浅色底图 |
| header_icon.png | 目录页与内容页右上角页眉图标 |
| content_banner.jpeg | 内容页横幅内以 20% 透明度叠加的品牌照片 |
