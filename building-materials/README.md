# ALE Building Materials

GitHub Pages-ready subject folder.

## Files
- `index.html` — standalone flashcard reviewer app
- `cards.json` — ALE Building Materials card bank

## Visual source rule
Images are loaded online inside the flashcard.

Priority:
1. Wikipedia / Wikimedia Commons preview
2. Google Images fallback button only if no preview loads

No image is embedded as base64, so the folder stays lightweight.

## Current card status
- Total cards: 326
- Cards with visual target or concept visual: 313

## Upload path
Place this folder in your GitHub repo root:

```txt
your-repo/
  index.html
  building-materials/
    index.html
    cards.json
    README.md
```

Then open:

```txt
https://USERNAME.github.io/REPO-NAME/building-materials/
```
