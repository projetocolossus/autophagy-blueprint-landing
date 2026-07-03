# Autophagy Activation Blueprint — Landing Page

Sales page for the Autophagy Activation Blueprint ($19.99). Static HTML, ready to deploy on Vercel.

## Before going live
1. **Add the two images** into `images/`:
   - `book-mockup.png` — the 3D book cover
   - `mascot.png` — the character/mascot
2. **Set the checkout link:** open `index.html`, search for `SEU-LINK-DE-CHECKOUT-AQUI` and replace all 4 with your Kiwify link.

## Deploy on Vercel
- Import this repository on vercel.com (framework preset: **Other**), or run `vercel` in this folder.
- No build step needed — it serves `index.html` directly.

## Local preview
```
python -m http.server 8000
```
Then open http://localhost:8000
