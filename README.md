# Priyadharsan & Monisha — Wedding Invitation

A scroll-driven wedding invitation. Static site, no build step.

**Live:** https://USERNAME.github.io/REPO/

## Files

| Path | What it is |
| --- | --- |
| `index.html` | The invitation (entry point) |
| `support.js` | Runtime the page loads |
| `png/` | Sticker artwork |
| `png/moments/` | Cut-out stickers for the rolling "In between" strip |
| `music/theme.wav` | Background piano loop |
| `Wedding Invitation.dc.html` | Editable source (same content as `index.html`) |

## Deploying on GitHub Pages

1. Push everything in this folder to the repository root.
2. **Settings → Pages**
3. **Source:** Deploy from a branch
4. **Branch:** `main`, folder `/ (root)` → **Save**
5. Wait ~1 minute; the URL appears at the top of the same page.

## Local preview

Open `index.html` directly, or serve the folder:

```
python3 -m http.server 8000
```

Then visit http://localhost:8000

## Notes

- Keep the folder structure intact — asset paths are relative.
- Music starts on first tap/click (browsers block autoplay).
- Editing copy: change it in both `index.html` and `Wedding Invitation.dc.html`, or re-copy one over the other.
