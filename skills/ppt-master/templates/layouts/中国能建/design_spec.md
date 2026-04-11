# 中国能建 - Design Specification

## I. Template Overview

- **Template ID**: 中国能建
- **Display Name**: 中国能建集团 (China Energy Engineering Group)
- **Category**: brand
- **Use Cases**: Corporate reporting, annual summaries, energy project proposals, government briefings, technical presentations for CNCE Group subsidiaries
- **Design Tone**: Professional, authoritative, state-enterprise blue; clean and data-forward; reflects national energy infrastructure identity
- **Reference Source**: `projects/ppt能建.pptx` (5-slide template deck)

---

## II. Canvas Specification

- **Format**: ppt169
- **Dimensions**: 1280 × 720 px
- **viewBox**: `0 0 1280 720`
- **Aspect Ratio**: 16:9

---

## III. Color Scheme

| Role | HEX | Usage |
|------|-----|-------|
| Primary Blue | `#0068b7` | Main brand color; rules, titles, number boxes, TOC accents |
| Dark Navy | `#002f7b` | Horizontal rules, strong accent borders |
| Chapter Blue | `#0067b4` | Chapter page left panel, circle fill |
| Mid Blue | `#005da2` | Content page key-message bar |
| Light Gray | `#f2f2f2` | Content box background |
| Text Dark | `#4d4d4d` | Body text, secondary labels |
| White | `#FFFFFF` | Backgrounds, text on dark panels |
| Accent Gray | `#c9c9c9` | Decorative trim, dividers |

---

## IV. Typography System

- **Primary Font**: `Microsoft YaHei` (微软雅黑), fallback `sans-serif`
- **Title (Cover)**: 52 px, bold, white
- **Subtitle (Cover)**: 26 px, regular, white
- **Page Title**: 32 px, bold, `#0068b7`
- **Section Header**: 28 px, bold, white (on dark panels)
- **Key Message**: 21 px, bold, white (content key-message bar)
- **Body / TOC item**: 18–20 px, regular or bold, `#0068b7` / `#4d4d4d`
- **Chapter Number (circle)**: 128 px, bold, `#0070c0`
- **Chapter Title (right side)**: 40 px, bold, `#0068b7` (displayed over photo background)
- **Caption / Footer**: 13 px, regular, `#4d4d4d`

---

## V. Page Structure

### Common Header (TOC / Content pages)
- Top-right: `brand_logo.png`
  - TOC page: x=985, y=16, width=252 × 50 px
  - Content page: x=990, y=18, width=256 × 63 px
- Thin horizontal navy rule at y = 82 (on TOC page)
- Thick blue rule at y = 91–97 (on Content page, 6 px, `#0068b7`)

### Common Footer (Content pages)
- Page number `{{PAGE_NUM}}` at bottom-right
- Section name `{{SECTION_NAME}}` at bottom-left

### Decorative Elements
- Left blue accent stripe on TOC (x = 0–18, y = 20–82)
- Number box protruding slightly above TOC row top
- Small gray trapezoid trim at top of TOC number box
- Right-pointing chevron at chapter left/right divider

---

## VI. Page Types

| # | File | Type | Key Elements |
|---|------|------|-------------|
| 1 | `01_cover.svg` | Cover | Full-bleed photo (no dark overlay), centered logo, large white title; date/author in white over photo |
| 2 | `02_toc.svg` | TOC | Left branding column with `toc.png` image, 4 indexed TOC item rows |
| 3 | `02_chapter.svg` | Chapter | Blue left panel + photo right, circle chapter number; title in `#0068b7` over photo |
| 4 | `03_content.svg` | Content | `content.png` full-bleed bg (opacity 0.6), header rule, gray content box, key-message bar |
| 5 | `04_ending.svg` | Ending | Centered logo, blue middle band, hardcoded closing message (no editable placeholders) |

---

## VII. Layout Modes

- **Cover**: Full-bleed background (no dark overlay) with centered text overlay; all text (title/subtitle/date/author) rendered white directly over photo
- **TOC**: Two-column — left branding column (`toc.png` image) / right navigation rows
- **Chapter**: Half-split — solid color left, photo right; chapter title in brand blue over photo
- **Content**: Full-bleed `content.png` texture bg (0.6 opacity) + fixed header/footer + free-form gray content area
- **Ending**: Vertically bipartite — logo (top white area) / blue band (hardcoded message); no bottom footer

---

## VIII. Spacing Specification

- **Global margin**: 55 px left/right
- **Cover logo**: centered, x=453, y=28, width=374 × 98 px
- **Blue rule (content)**: rect x=0, y=91, height=6 px (bottom edge at y=97)
- **Content box top**: y = 105 px from top
- **Content box height**: 560 px (y = 105 → 665)
- **Key-message bar height**: 68 px
- **TOC row height**: 50 px, gap between rows: ~112 px (row y-positions: 230, 342, 454, 566)
- **TOC number box**: 71 × 54 px, protrudes 12 px above row top
- **Chapter circle center**: (319, 337), outer radius 115 px, inner radius 109 px
- **Ending blue band**: y = 274, height = 282 px (to y = 556)

---

## IX. SVG Technical Constraints

- All SVG files use `viewBox="0 0 1280 720"` and explicit `width="1280" height="720"`
- Font references use `font-family="Microsoft YaHei, sans-serif"` (no @font-face embedding)
- Asset paths are relative (e.g., `brand_logo.png`, `cover_bg.png`)
- `preserveAspectRatio="xMidYMid slice"` for full-bleed background images
- `preserveAspectRatio="xMidYMid meet"` for logos
- No JavaScript, no external stylesheets
- `<clipPath>` IDs are unique per file (prefixed with file-specific prefix)

---

## X. Placeholder Specification

### Cover (`01_cover.svg`)
| Placeholder | Location | Style |
|-------------|----------|-------|
| `{{TITLE}}` | Center over photo, y = 335 | 52 px bold `#FFFFFF` |
| `{{SUBTITLE}}` | Below title, y = 400 | 26 px regular `#FFFFFF` |
| `{{DATE}}` | Over photo, y = 636 | 18 px `#FFFFFF` |
| `{{AUTHOR}}` | Over photo, y = 666 | 16 px `#FFFFFF` |

> ⚠️ No dark overlay on the cover. All text renders in white directly over `cover_bg.png`.

### TOC (`02_toc.svg`)
| Placeholder | Location |
|-------------|----------|
| `{{TOC_ITEM_1_TITLE}}` | Row 1 text area, y = 261 |
| `{{TOC_ITEM_2_TITLE}}` | Row 2 text area, y = 373 |
| `{{TOC_ITEM_3_TITLE}}` | Row 3 text area, y = 485 |
| `{{TOC_ITEM_4_TITLE}}` | Row 4 text area, y = 597 |

> Left column branding uses `toc.png` image (x=81, y=287, 324.8×156.8 px).

### Chapter (`02_chapter.svg`)
| Placeholder | Location | Style |
|-------------|----------|-------|
| `{{CHAPTER_NUM}}` | Inside white circle, center (319, 370) | 128 px bold `#0070c0` |
| `{{CHAPTER_TITLE}}` | Right side over photo, x=730, y=370 | 40 px bold `#0068b7` |

> Chapter number label ("第 X 章") and chapter description are removed (commented out).

### Content (`03_content.svg`)
| Placeholder | Location | Style |
|-------------|----------|-------|
| `{{PAGE_TITLE}}` | Top header, x=55, y=74 | 32 px bold `#0068b7` |
| `{{KEY_MESSAGE}}` | Dark blue bar (y=105, h=68), x=42, y=148 | 21 px bold `#FFFFFF` |
| `{{CONTENT_AREA}}` | Gray content box body (y=173–665) | Free layout by Executor |
| `{{PAGE_NUM}}` | Bottom-right, x=1225, y=712 | 13 px `#4d4d4d` |
| `{{SECTION_NAME}}` | Bottom-left, x=55, y=712 | 13 px `#4d4d4d` |

> Content page has `content.png` full-bleed background at 60% opacity beneath all elements.

### Ending (`04_ending.svg`)
> ⚠️ The ending page uses **hardcoded text** — there are no user-editable placeholders.

| Element | Location | Style |
|---------|----------|-------|
| Brand logo | x=427, y=91, 426×111 px | `preserveAspectRatio="xMidYMid meet"` |
| Closing message (hardcoded) | Blue band center, x=640, y=396 | 54 px bold `#FFFFFF`; text: "敬请批评指正！" |

> To customize the closing message, edit `04_ending.svg` directly and change the hardcoded text.
