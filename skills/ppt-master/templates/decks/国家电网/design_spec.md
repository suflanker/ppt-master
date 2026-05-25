---
template_id: 国家电网
kind: deck
category: government
summary: 国家电网风格通用汇报模板 — 青绿色稳重专业，左侧深色竖栏+右侧卡片布局，适合央企内部汇报、项目进展、技术方案
keywords: [国网, 央企汇报, 青绿色, 稳重, 卡片式]
primary_color: "#249087"
canvas_format: ppt169
replication_mode: standard
placeholders:
  02_toc: ["{{TOC_ITEM_1_TITLE}}", "{{TOC_ITEM_2_TITLE}}", "{{TOC_ITEM_3_TITLE}}", "{{TOC_ITEM_4_TITLE}}"]
---

# 国家电网通用汇报模板 — Design Specification

## I. Template Overview

国家电网（SGCC）品牌风格的通用汇报模板。青绿色主色调传递科技感与信任感，左侧深色竖栏 + 右侧卡片式目录布局是其最显著的视觉识别特征。全幅背景图封面/封底营造大气开场与收尾，目录页以 `toc_bg.png` 全幅背景图融合左侧竖栏与装饰元素，内容页以顶部横幅 + 白色圆角大卡片承载正文。适用于央企内部工作汇报、项目进展汇报、技术方案汇报、年度总结等场景。

## II. Color Scheme

| Role | HEX | Usage |
|------|-----|-------|
| Primary | `#249087` | 左侧竖栏渐变终点、目录高亮项文字、燕尾装饰箭头 |
| Dark Teal | `#1D8578` / `#18665C` | 左侧竖栏渐变起点、内容页横幅渐变 |
| Deep Teal | `#18605A` | 目录普通项文字、阴影色 |
| Light BG Start | `#F1F9FC` | 页面背景渐变起点 |
| Light BG End | `#D4F4F2` | 页面背景渐变终点、目录高亮卡片渐变终点 |
| Shadow Teal | `#7DDFD6` | 卡片投影色（带 opacity） |
| White | `#FFFFFF` | 卡片底色、封面/封底文字、目录高亮卡片渐变起点 |

## III. Typography

| Role | Font Stack | Size |
|------|-----------|------|
| 封面标题 | `Microsoft YaHei, 微软雅黑, sans-serif` | 56px bold |
| 封面副标题 | `Microsoft YaHei, 微软雅黑, sans-serif` | 28px bold |
| 目录项标题 | `Microsoft YaHei, 微软雅黑, sans-serif` | 32px bold |
| 页面标题 | `Microsoft YaHei, 微软雅黑, sans-serif` | 37px bold |
| 正文 | `Microsoft YaHei, 微软雅黑, sans-serif` | 24px |
| 封底致谢 | `Microsoft YaHei, 微软雅黑, sans-serif` | 72px bold |

全模板统一使用微软雅黑。微软雅黑是 Windows 预装字体，中英文混排效果好，无需额外字体安装。

## IV. Signature Design Elements

- **左侧深色竖栏 + 全幅背景图**：目录页的标志性结构，深青绿渐变矩形覆盖左侧约 1/3 宽度，叠加 `toc_bg.png` 全幅背景图融合装饰元素与视觉锚点
- **燕尾形渐变箭头**：目录第一项（当前章节）右侧的 3 个燕尾形（chevron）多边形，填充从 6% → 15% → 40% 透明度渐变，指示当前位置
- **圆角白色卡片 + 青绿投影**：目录项和内容区均使用大圆角白色矩形 + `feDropShadow` 青绿色投影，是贯穿全模板的核心视觉语言
- **全幅背景图封面/封底**：封面与封底共享同一张全幅背景图，下方叠加底部渐变遮罩确保白色文字可读性
- **顶部横幅 + 图片叠加**：内容页顶部约 300px 高的深色渐变横幅，叠加半透明图片素材，上方放置章节/小节标题
- **LOG 图标**：封面和封底左上角放置组织 logo（`logo_small.png`），目录和内容页右上角放置小尺寸品牌图标（`header_icon.png`）

## V. Page Roster

| Page | File | Description |
|------|------|-------------|
| Cover | `01_cover.svg` | 全幅背景图 + 底部渐变遮罩。左上角 logo，左侧大标题 `{{TITLE}}`，左下角副标题 `{{SUBTITLE}}` + 日期 `{{DATE}}` |
| TOC | `02_toc.svg` | 浅青绿渐变背景 + 左侧深色竖栏，叠加 `toc_bg.png` 全幅背景图。右侧 4 个圆角白色卡片，第一个为高亮态（白绿渐变底 + 白色描边 + 燕尾箭头），其余为常态白底卡片。每项标题使用 `{{TOC_ITEM_N_TITLE}}` |
| Content | `03_content.svg` | 浅青绿渐变背景。顶部深色横幅 + 图片叠加，横幅上可放置 `{{SECTION_NAME}}`。左上角页面标题 `{{PAGE_TITLE}}`，右上角品牌图标。大面积白色圆角卡片承载 `{{CONTENT_AREA}}` |
| Ending | `04_ending.svg` | 与封面同款全幅背景图 + 底部渐变遮罩。左上角 logo，居中大字 `{{THANK_YOU}}`，下方可选 `{{CLOSING_MESSAGE}}` |

## VI. Assets

| File | Dimensions | Size | Usage |
|------|-----------|------|-------|
| `cover_bg.png` | — | 6.9 MB | 封面、封底全幅背景图 |
| `logo_small.png` | — | 33 KB | 封面、封底左上角组织 logo |
| `toc_bg.png` | — | 1.2 MB | 目录页全幅背景图，融合左侧竖栏装饰与"目录"标识 |
| `header_icon.png` | — | 36 KB | 目录页、内容页右上角品牌图标 |
| `content_banner.jpeg` | — | 3.1 MB | 内容页顶部横幅叠加图片（sprite crop） |

`content_banner.jpeg` 通过嵌套 `<svg viewBox="...">` 做 sprite crop，裁剪关系已写入对应 SVG，**不可展平为裸 `<image>`**。
