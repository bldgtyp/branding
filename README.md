# BLDGTYP Design System

The canonical brand and UI reference for all BLDGTYP web products.

**Live site:** https://bldgtyp.github.io/brand

## What's here

```
brand/
├── index.html          ← Design system site (GitHub Pages)
├── tokens/
│   ├── tokens.css      ← CSS custom properties (importable)
│   └── tokens.json     ← Machine-readable design tokens
├── assets/
│   ├── hero-drafting.png
│   ├── detail-foundation.png
│   └── detail-wall-section.png
└── README.md
```

## Quick start

Import the CSS tokens in any BLDGTYP web product:

```css
@import url('https://bldgtyp.github.io/brand/tokens/tokens.css');
```

Then set `data-theme="light"` or `data-theme="dark"` on `<html>` and use the custom properties:

```css
body {
    background-color: var(--bg-page);
    color: var(--text-primary);
    font-family: var(--font-primary);
}
```

## Products using this system

| Product | Repo | Status |
|---------|------|--------|
| bldgtyp.com | — | Reference implementation |
| PH-Navigator | [ph-navigator](https://github.com/bldgtyp/ph-navigator) | Planned |
| Design-Phase Reports | — | Planned |

## Fonts

Load from Google Fonts:

```html
<link href="https://fonts.googleapis.com/css2?family=Outfit:wght@200;300;400;500;600;700&family=JetBrains+Mono:wght@300;400&display=swap" rel="stylesheet">
```

---

*Building-Type LLC &middot; 2026*
