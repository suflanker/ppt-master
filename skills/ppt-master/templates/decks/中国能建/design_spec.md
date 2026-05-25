---
template_id: 中国能建
category: brand
summary: 中国能建集团企业风格 — 深蓝稳重、结构清晰、大气专业的央企汇报模板
keywords: [企业蓝, 能源, 稳重, 集团汇报, 大标题]
primary_color: "#0068B7"
canvas_format: ppt169
replication_mode: standard
placeholders:
  01_cover: ["{{TITLE}}", "{{SUBTITLE}}", "{{DATE}}"]
  02_toc: ["{{TOC_ITEM_1_TITLE}}", "{{TOC_ITEM_2_TITLE}}", "{{TOC_ITEM_3_TITLE}}"]
  02_chapter: ["{{CHAPTER_NUM}}", "{{CHAPTER_TITLE}}"]
  03_content: ["{{PAGE_TITLE}}", "{{SECTION_TITLE}}", "{{CONTENT_AREA}}", "{{TAG_LABEL}}", "{{PAGE_NUM}}"]
  04_ending: ["{{THANK_YOU}}"]
---

# 能建集团风格 — Design Specification

## I. Template Overview

适用于中国能建及能源类央企的企业汇报、集团年报、战略规划、项目总结等正式场合。整体风格以深蓝色系为品牌核心，版式稳重、层次分明，兼顾大信息量展示与视觉品质感。浅色底配合深蓝强调色块，传递专业、可靠、大气的组织形象。

## II. Color Scheme

| 角色 | 色值 | 用途 |
|------|------|------|
| 品牌主色 | `#0068B7` | 标题字、核心色块、编号标签、章节标题 |
| 深蓝强调 | `#005DA2` | 内容页标题栏背景 |
| 深蓝装饰 | `#002F7B` | 目录页顶部细线 |
| 浅蓝装饰 | `#4472C4` | 章节页左侧半透明面板 |
| 亮蓝编号 | `#0070C0` | 章节页大号数字 |
| 浅灰底色 | `#F2F2F2` | 内容页正文字区域背景 |
| 白色 | `#FFFFFF` | 页面背景、封面/结尾文字 |
| 深灰文字 | `#4D4D4D` | 目录编号路径字 |
| 黑色 | `#000000` | 正文主文字 |
| 红色高亮 | `#FF0000` | 正文关键词高亮 |

## III. Typography

| 角色 | 字体栈 | 字号 |
|------|--------|------|
| 封面大标题 | `"微软雅黑", sans-serif` | 53px bold |
| 封面副标题 | `"思源黑体 CN Bold", "微软雅黑", sans-serif` | 37px |
| 目录标签 | `"微软雅黑", sans-serif` | 24px bold |
| 目录编号 | `"微软雅黑", sans-serif` | 27px bold |
| 章节编号 | `"微软雅黑", sans-serif` | 143px bold |
| 章节标题 | `"微软雅黑", sans-serif` | 57px bold |
| 内容标题/编号 | `Arial, "微软雅黑", sans-serif` | 32px bold |
| 内容栏目标题 | `"Times New Roman", "微软雅黑", sans-serif` | 27px bold |
| 正文 | `"Times New Roman", "微软雅黑", sans-serif` | 19px |
| 标签按钮 | `"Times New Roman", "微软雅黑", sans-serif` | 20px bold |
| 结尾致谢 | `"微软雅黑 Light", sans-serif` | 64px |

## IV. Signature Design Elements

- **封面底部大图 + 深蓝渐变遮罩**：封面背景图为全宽大图，底部区域展示；标题/副标题白色居中叠加在图片上方
- **目录卡片式设计**：左侧放置 `toc.png` 目录标识图，右侧三张浅灰渐变卡片竖向排列，带轻柔投影和蓝色编号角标（左上角斜切造型），顶部蓝色细线 + 左侧蓝色竖条装饰
- **章节页左侧色块面板**：左半区域为品牌蓝半透明色块 + 同心双圆 + 超大号章节编号，右侧为全幅背景图，章节标题以品牌蓝大字置于右侧
- **内容页结构化框架**：右上 logo + 蓝色分隔线 + 灰色正文背景区 + 深蓝标题栏 + 正文区（支持红色关键词高亮）+ 底部标签按钮
- **结尾页蓝色横带**：居中 logo + 粗蓝色横带 + 白色大字致谢 + 灰色细线上下装饰

## V. Page Roster

| 文件 | 页面类型 | 描述 |
|------|----------|------|
| `01_cover.svg` | 封面 | 底部背景大图 + 居中品牌 logo + 白色大标题 + 白色副标题/日期 |
| `02_toc.svg` | 目录 | 左侧 `toc.png` 目录标识图 + 右侧 3 张卡片式目录条目（渐变底 + 投影 + 蓝色编号角标 01/02/03）+ 蓝色顶线 + 左侧竖条装饰 + 右上 logo |
| `02_chapter.svg` | 章节 | 左侧品牌蓝半透明面板 + 超大编号 01 + 同心双圆装饰 + 右侧全幅背景图 + 大号蓝色章节标题 |
| `03_content.svg` | 内容 | 右上 logo + 蓝色分隔线 + 底部装饰水印 + 页脚(日期/页码) + 灰色正文背景 + 深蓝标题栏 + 多行正文区(支持红色高亮) + 底部标签按钮 |
| `04_ending.svg` | 结尾 | 居中品牌 logo + 蓝色横带 + 白色大字致谢 + 上下灰色细线装饰 |

## VI. Assets

| 文件 | 用途 | 出现页面 |
|------|------|----------|
| `brand_logo.png` | 企业品牌 logo（主标识） | 封面、目录、结尾 |
| `cover_bg.png` | 封面底部背景大图（sprite） | 封面 |
| `chapter_bg.jpeg` | 章节页右侧全幅背景图 | 章节 |
| `logo_top_right.png` | 右上角辅助 logo | 内容 |
| `content_watermark.png` | 内容页底部水印/装饰图（sprite） | 内容 |
| `toc.png` | 目录页左侧目录标识图 | 目录 |

