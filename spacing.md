# Spacing & Scale

> Source: Travel Figma file — `u7sQtrIT4nyr4a4HPw72dS`
> Token files: Light.tokens 2.json (primitive Scale), Light.tokens 3.json (semantic spacing)
> Updated: 2026-07-27

---

## Gap Scale

| Token | Value (px) | Scale alias |
|-------|------------|-------------|
| `Gap/XXS` | `2` | Scale/50 |
| `Gap/XS` | `4` | Scale/100 |
| `Gap/S` | `8` | Scale/200 |
| `Gap/M` | `16` | Scale/400 |
| `Gap/L` | `24` | Scale/600 |
| `Gap/XL` | `32` | Scale/800 |
| `Gap/XXL` | `40` | Scale/1000 |

---

## Padding Scale

| Token | Value (px) | Scale alias |
|-------|------------|-------------|
| `Padding/XXS` | `2` | Scale/50 |
| `Padding/XS` | `4` | Scale/100 |
| `Padding/S` | `8` | Scale/200 |
| `Padding/M` | `16` | Scale/400 |
| `Padding/L` | `24` | Scale/600 |
| `Padding/XL` | `32` | Scale/800 |
| `Padding/XXL` | `40` | Scale/1000 |

---

## Border Radius

| Token | Value (px) | Scale alias | Usage |
|-------|------------|-------------|-------|
| `Border radius/XS` | `8` | Scale/200 | Cards, inputs, buttons |
| `Border radius/S` | `20` | Scale/500 | Pill-style small elements |
| `Border radius/M` | `32` | Scale/800 | Large rounded containers |
| `Border radius/L` | `40` | Scale/1000 | Full pill / large rounded |

> shadcn aliases: `radius-md` = 8px

---

## Border Width

| Token | Value (px) | Scale alias | Usage |
|-------|------------|-------------|-------|
| `Border width/XS` | `1` | Scale/25 | Default border |
| `Border width/S` | `2` | Scale/50 | Prominent border |
| `Border width/M` | `4` | Scale/100 | Heavy / focus border |
| `Border width/L` | `8` | Scale/200 | Extra heavy border |

---

## Primitive Scale — Full Table

Raw numeric scale that all spacing/size tokens alias into.

| Scale token | Value (px) |
|-------------|------------|
| `Scale/0` | `0` |
| `Scale/25` | `1` |
| `Scale/50` | `2` |
| `Scale/100` | `4` |
| `Scale/200` | `8` |
| `Scale/300` | `12` |
| `Scale/400` | `16` |
| `Scale/500` | `20` |
| `Scale/600` | `24` |
| `Scale/700` | `28` |
| `Scale/800` | `32` |
| `Scale/900` | `36` |
| `Scale/950` | `38` |
| `Scale/1000` | `40` |

---

## Tailwind / shadcn Spacing Aliases

| Token | Value (px) | Tailwind equivalent |
|-------|------------|---------------------|
| `py-1` | `4` | `py-1` |
| `py-1,5` / `gap-1,5` | `6` | `py-1.5` / `gap-1.5` |
| `py-2` / `pl-2` / `px-2` | `8` | `py-2` / `pl-2` / `px-2` |
| `px-3` / `pl-3` / `pr-3` / `gap-3` | `12` | `px-3` / `gap-3` |
| `gap-5` / `gap-x-5` | `20` | `gap-5` |
| `gap-8` | `32` | `gap-8` |

---

## Shadows / Effects

| Token | Value | Usage |
|-------|-------|-------|
| `Box Shadow/shadow-xs` | `DROP_SHADOW · #0000001A · offset (0,1) · radius 2 · spread 0` | Subtle card shadow |
| `shadow` | `DROP_SHADOW · #00000017 · offset (0,4) · radius 6 · spread 0` | Card / floating element shadow |
| `Notification Shadow` | `DROP_SHADOW · #0000001A · offset (0,2) · radius 6 · spread 0` | Toast / notification shadow |
