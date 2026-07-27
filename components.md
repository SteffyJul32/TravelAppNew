# Components

> Source: Travel Figma library — `u7sQtrIT4nyr4a4HPw72dS`
> Library: **Travel** (team library, published)

---

## Button

**Type:** component_set

**Variants:**
- `Variant`: Primary, Secondary, Tertiary, Ghost, Outline
- `Size`: Small, Medium, Large
- `State`: Default, Hover, Active, Disabled
- `Icon`: None, Left, Right

**Token usage:**

| Variant | Default | Hover | Disabled |
|---------|---------|-------|----------|
| Primary | `Action/Primary/Primary-Default` `#2D9326` | `Action/Primary/Primary-Hover` `#225C1F` | `Action/Primary/Primary-Disabled` `#D1D1D1` |
| Secondary | `Action/Secondary/Secondary-Default` `#E2F8E0` | `Action/Secondary/Secondary-Hover` `#98E392` | `Action/Secondary/Secondary-Disabled` `#D1D1D1` |
| Tertiary | `Action/Tertiary/Tertiary-Default` `#FCE4E4` | `Action/Tertiary/Tertiary-Hover` `#F7AAAA` | `Action/Tertiary/Tertiary-Disabled` `#D1D1D1` |
| Quaternary | `Action/Quaternary/Quaternary-Default` `#F3EDFA` | `Action/Quaternary/Quaternary-Hover` `#D8C4EE` | `Action/Quaternary/Quaternary-Disabled` `#D1D1D1` |
| Quinary | `Action/Quinary/Quinary-Default` `#FDEFC8` | `Action/Quinary/Quinary-Hover` `#F7C852` | `Action/Quinary/Quinary-Disabled` `#D1D1D1` |

- Label: `Text/Button Text/White text` (#FFFFFF) / `Text/Button Text/Button Text Black` (#3D3D3D)
- Border: `Border/Button/Button Stroke Active` (#B0B0B0) when outlined

---

## Icon button

**Type:** component_set

**Variants:**
- `Variant`: Primary, Secondary, Ghost
- `Size`: Small (24px), Medium (32px), Large (40px)
- `State`: Default, Hover, Active, Disabled

**Token usage:**
- Icon color: `Icon/Icon-Primary` (#2d9326), `Icon/Icon-Invert` (#ffffff), `Icon/Icon-Default` (#6d6d6d)

---

## Tab

**Type:** component_set

**Variants:**
- `State`: Active, Inactive
- `Icon`: With icon, Without icon

**Token usage:**
- Active text: `Text/Text-Brand` (#2d9326)
- Inactive text: `Text/Text-Secondary` (#5d5d5d)
- Active indicator: `Action/Primary/Primary-Default` (#2d9326)

---

## Text form

**Type:** component_set

**Variants:**
- `State`: Default, Focused, Error, Disabled, Filled
- `Type`: Text, Password, Email, Number

**Token usage:**
- Placeholder: `Text/Text-Default Form` (#888888)
- Label: `Text/Text-Primary` (#000000)
- Border default: `Border/Border-Default` (#D1D1D1)
- Border active: `Border/Border-Active` (#888888)
- Border disabled: `Border/Border-Disabled` (#B0B0B0)
- Border error: `Alert/Error/Error-Default` (#D23030)
- Background: `Background/Background-White` (#FFFFFF)

---

## Snackbar

**Type:** component

**Variants:**
- `Type`: Success, Error, Info, Warning

**Token usage:**
- Success background: `Alert/Success/Success-Invert` (#2d9326)
- Error background: `Alert/Error/Error-Default` (#d23030)
- Text: `Text/Text-Invert` (#ffffff)
- Shadow: `Notification Shadow`

---

## Banner template

**Type:** component

**Variants:**
- Single variant — full-width hero/promotional banner

**Token usage:**
- Background: `Background/Background-Brand` (#2d9326) or image
- Text: `Text/Text-Invert` (#ffffff)

---

## Trip thumbnail

**Type:** component_set

**Variants:**
- `Size`: Small, Medium, Large
- `State`: Default, Saved/Bookmarked

**Token usage:**
- Background: `Background/Background-White` (#ffffff)
- Shadow: `shadow` (DROP_SHADOW · #00000017 · offset 0,4 · radius 6)
- Radius: `Border radius/XS` (8px)
- Location text: `Text/Text-Secondary` (#5d5d5d)
- Title text: `Text/Text-Primary` (#000000)

---

## Location

**Type:** component_set

**Variants:**
- `Size`: Small, Medium, Large
- `Style`: Pin, Label

**Token usage:**
- Icon: `Icon/Icon-Primary` (#2d9326)
- Text: `Text/Text-Secondary` (#5d5d5d)

---

## Location icon

**Type:** component_set

**Variants:**
- `Size`: Small, Medium, Large
- `Style`: Filled, Outline

**Token usage:**
- Fill: `Action/Primary/Primary-Default` (#2d9326)
- Icon: `Icon/Icon-Invert` (#ffffff)

---

## NavIcons

**Type:** component_set

**Variants:**
- `Icon`: Home, Explore, Bookings, Profile (or similar nav destinations)
- `State`: Active, Inactive

**Token usage:**
- Active: `Icon/Icon-Primary` (#2d9326)
- Inactive: `Icon/Icon-Default` (#6d6d6d)

---

## Icons

**Type:** component_set

**Variants:**
- `Name`: All Lucide icon names (see `icons.md`)
- `Size`: 16, 20, 24, 32

**Token usage:**
- Default: `Icon/Icon-Default` (#6d6d6d)
- Primary: `Icon/Icon-Primary` (#2d9326)
- Invert: `Icon/Icon-Invert` (#ffffff)

---

## Notes

- Exact variant property names are set in Figma. Values above are inferred from token usage across screens.
- shadcn/ui and iOS UI Kit libraries are linked but their components are separate from the Travel library.
- Icon library: **Lucide Icons (Community)** — see `icons.md`.
