# CSS Directory

This folder contains all stylesheets for the GRC Practice Lab.

## Files

- **styles.css** — Main stylesheet with all component styles, themes, and responsive design

## Font References

Google Fonts are currently loaded from CDN in the HTML:
- **Plus Jakarta Sans** (weights: 400, 500, 600, 700, 800) — Primary sans-serif font
- **JetBrains Mono** (weights: 400, 500) — Monospace font for code and technical content

To use custom fonts, download `.woff2` files and place them in the `../fonts/` folder.

## CSS Custom Properties (Design Tokens)

Key variables defined in `:root`:

### Colors
- `--bg-base` — Primary background
- `--bg-surface` — Card/surface background
- `--bg-elevated` — Elevated surface
- `--text-primary` — Primary text color
- `--text-secondary` — Secondary text color
- `--text-muted` — Muted/disabled text

### Accents
- `--accent-blue` — Blue accent color
- `--accent-green` — Green accent color
- `--accent-purple` — Purple accent color
- `--accent-red` — Red/error color
- `--accent-amber` — Amber/warning color
- `--accent-cyan` — Cyan accent color

### Shadows
- `--shadow-sm`, `--shadow-md`, `--shadow-lg`, `--shadow-xl`
- `--shadow-glow-blue`, `--shadow-glow-green`, `--shadow-glow-purple`

### Radii
- `--radius-sm` — 6px
- `--radius-md` — 8px
- `--radius-lg` — 12px
- `--radius-xl` — 16px
- `--radius-full` — 9999px

### Transitions
- `--transition-fast` — 0.15s ease
- `--transition-normal` — 0.2s ease
- `--transition-slow` — 0.3s ease

## Dark Mode

Dark mode colors are defined in `html[data-theme="dark"]` selector (currently disabled).
To re-enable, modify `initModes()` in the HTML to load dark theme preferences.

## Future Updates

When making style changes:
1. Edit `css/styles.css` directly (no need to touch HTML)
2. Use CSS custom properties for consistency
3. Test responsiveness on mobile (768px breakpoint)
4. Update this README with new sections or components
