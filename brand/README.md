# Porma Software brand

Monochrome river mark plus the "Porma" wordmark. Every SVG uses `currentColor`, so the same file renders dark on light backgrounds and light on dark ones: set `color` on the parent element.

| File | Use |
|---|---|
| `porma-wordmark.svg` | Horizontal lockup (mark + "Porma" + "SOFTWARE"). Docs, headers, proposals. |
| `porma-mark.svg` | Mark alone, 256×256 viewBox. Favicons, app icons, small sizes (reads down to ~32 px). |
| `porma-avatar.svg` | Mark on a dark slate rounded square (`#0f172a` / white). The only file with fixed colors. |
| `porma-avatar-512.png`, `porma-avatar-1024.png` | Rasterized avatar for GitHub and marketplaces. |
| `alternatives/` | Two other explorations (river-and-bank, river-with-tributaries) kept for reference. |

The wordmark uses a system font stack (Inter, Segoe UI, Helvetica, Arial). Convert the text to outlines before print use.

## Organization avatar

GitHub has no API for organization avatars. Upload `porma-avatar-512.png` by hand: **Organization → Settings → Profile → Profile picture → Upload new picture**.

## Colors

The brand is monochrome. Recommended pairings: text `#0f172a` on white, white on `#0f172a`. No gradients, no secondary colors.
