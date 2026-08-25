# Fonts Directory

This folder is reserved for custom font files.

## Current Setup

Fonts are currently loaded from Google Fonts CDN:
- **Plus Jakarta Sans** — https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700;800
- **JetBrains Mono** — https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;500

## To Use Local Fonts

1. Download `.woff2` files for each font variant
2. Place them in this folder
3. Create or update `css/fonts.css` with @font-face declarations
4. Link to it in the HTML `<head>` before `css/styles.css`

Example:
```css
@font-face {
  font-family: 'Plus Jakarta Sans';
  src: url('../fonts/PlusJakartaSans-400.woff2') format('woff2');
  font-weight: 400;
}

@font-face {
  font-family: 'Plus Jakarta Sans';
  src: url('../fonts/PlusJakartaSans-700.woff2') format('woff2');
  font-weight: 700;
}
```

## Font Weights in Use

- **400** — Regular body text
- **500** — Medium (inputs, secondary content)
- **600** — Semi-bold (labels, section titles)
- **700** — Bold (headings, active states)
- **800** — Extra bold (hero text, emphasis)

## Monospace (JetBrains Mono)
- **400** — Regular code
- **500** — Bold code/emphasis
