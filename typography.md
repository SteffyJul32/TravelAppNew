# Typography

> Source: Travel Figma file — `u7sQtrIT4nyr4a4HPw72dS`
> Token files: Light.tokens 2.json (primitive), Light.tokens 3.json (semantic)
> Updated: 2026-07-27

---

## Font Families

| Token | Value | Usage |
|-------|-------|-------|
| `Font Family/Font Family` | `DM Sans` | Primary typeface for all UI text |
| `Font/Font family/Font family` | `DM Sans` | Alias — same typeface |
| `family/sans` | `Inter` | shadcn/Tailwind base tokens |

---

## Font Weights

| Token | Value | CSS `font-weight` |
|-------|-------|-------------------|
| `Font Weight/Regular` | `Regular` | `400` |
| `Font Weight/Medium` / `Font/Font weight/Medium` | `Medium` | `500` |
| `Font Weight/Semi Bold` / `Font/Font weight/SemiBold` | `Semi Bold` | `600` |
| `Font Weight/Bold` / `Font/Font weight/Bold` | `Bold` | `700` |
| `weight/normal` | `Regular` | `400` |

---

## Font Sizes

| Token | Value (px) | Scale alias |
|-------|------------|-------------|
| `Font size/XXS` | `8` | Scale/200 |
| `Font size/XS` | `12` | Scale/300 |
| `Font size/S` | `16` | Scale/400 |
| `Font size/M` | `20` | Scale/500 |
| `Font size/L` | `24` | Scale/600 |
| `Font size/XL` | `32` | Scale/800 |

> Additional Tailwind aliases: `size/sm` = 14px (Scale/350), `size/base` = 16px, `size/xl` = 20px

---

## Composite Text Styles

Pre-built text style tokens (family + weight + size + lineHeight).

| Token | Size | Weight | Line Height | Letter Spacing |
|-------|------|--------|-------------|----------------|
| `8pt DMSans/Medium Caption 8pt DMSans` | 8px | 500 | 100% | 0 |
| `8pt DMSans/Semibold Caption 8pt DMSans` | 8px | 600 | 100% | 0 |
| `12pt DMSans/Medium Subtitle 12pt DMSans` | 12px | 500 | 100% | 0 |
| `12pt DMSans/Semibold Subtitle 12pt DMSans` | 12px | 600 | 100% | 0 |
| `14pt DMSans/Medium Subtitle 14pt DMSans` | 14px | 500 | 100% | 0 |
| `14pt DMSans/Semibold Title 14pt DMSans` | 14px | 600 | 100% | 0 |
| `14pt DMSans/Bold Title 14pt DMSans` | 14px | 700 | 100% | 0 |
| `16pt DMSans/Medium Subtitle 16pt DMSans` | 16px | 500 | 100% | 0 |
| `16pt DMSans/SemiBold Title 16pt DMSans` | 16px | 600 | 100% | 0 |
| `16pt DMSans/Bold Title 16pt DMSans` | 16px | 700 | 100% | 0 |
| `20pt DMSans/Bold Title 20pt DMSans` | 20px | 700 | 100% | 0 |
| `24pt DMSans/Bold Title 24pt DMSans` | 24px | 700 | 100% | 0 |

---

## Mobile Text Styles

Optimised for mobile screens with explicit line heights.

| Token | Size | Weight | Line Height |
|-------|------|--------|-------------|
| `Mobile/Body text/Body_DMSans Medium 14pt` | 14px | 500 | 20px |
| `Mobile/Subtitle/Subtitle_DMSans SemiBold 16pt` | 16px | 600 | 20px |
| `Mobile/Title/Title_DMSans Bold 20pt` | 20px | 700 | 24px |

---

## shadcn / Tailwind Text Styles

| Token | Family | Size | Weight | Line Height |
|-------|--------|------|--------|-------------|
| `Text-sm/Regular` | Inter | 14px | 400 | 20px |

---

## Text Color Tokens

| Token | Value | Role |
|-------|-------|------|
| `Text/Text-Primary` | `#000000` | Default text |
| `Text/Text-Secondary` | `#5D5D5D` | Muted / secondary text |
| `Text/Text-Invert` | `#FFFFFF` | Text on dark surfaces |
| `Text/Text-Brand` | `#2D9326` | Brand green text |
| `Text/Text-Default Form` | `#888888` | Placeholder / hint text |
| `Text/Text-Disabled` | `#888888` | Disabled state text |
| `Text/Text/Title` | `#000000` | Title text |
| `Text/Text/Body text` | `#4F4F4F` | Body copy |
| `Text/Text/White text` | `#FFFFFF` | White text |
| `Text/Button Text/White text` | `#FFFFFF` | Button label — dark bg |
| `Text/Button Text/Button Text Black` | `#3D3D3D` | Button label — light bg |
