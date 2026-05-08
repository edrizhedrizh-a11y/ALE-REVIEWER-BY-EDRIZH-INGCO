# ALE Building Materials Flash Cards

Ready for GitHub upload.

## Files
- `index.html` - standalone flashcard app
- `cards.json` - ALE Building Materials question bank with image-ready fields

## Image behavior
- Cards use `visualMode: "question"` when a visual target is available.
- The image preview loads online from Wikipedia/Wikimedia Commons through the browser.
- Images are not embedded as base64, so the folder stays light.
- If a preview does not load, the card provides/searches a Google Images fallback target.

## Upload to GitHub
Upload this whole folder as:

```txt
building-materials/
  index.html
  cards.json
```

Then open with GitHub Pages at something like:

```txt
https://YOUR-USERNAME.github.io/YOUR-REPO/building-materials/
```

Generated with 326 cards; 313 cards include question visual targets.
