# Building Materials Visual Reset v3 — Personal Study Ready

This fixes the bad direction from previous BM image batches.

## What this package fixes now

- Removes ugly/weak Building Materials images.
- Removes Google/search fallback cues from the Building Materials reviewer page.
- Keeps Identify cards ready for local embedded images.
- Adds `image-intake-board.html` with exact product/material source candidates.
- Adds audit/source CSVs.

## Final image standard

```txt
Building Materials = accurate real product/material photo.
No old artifact.
No random generic image.
No sketch/diagram when item is real hardware/material.
No answer-revealing label before answering.
```

## How to finish each image

1. Open `building-materials/image-intake-board.html`.
2. Open the source link for each item.
3. Screenshot/crop the product only.
4. Save as the recommended file, for example:
   `building-materials/assets/BM-107.jpg`
5. Patch the card to:
   `"questionImage": "assets/BM-107.jpg"`

## Upload

Upload/replace:

```txt
building-materials/
```



## v3.1 fix

Identify cards that do not have a local embedded `questionImage` are now hidden from the active reviewer.

This prevents impossible Identify questions from appearing without an image.

When the image is ready:
1. Save it in `building-materials/assets/`, e.g. `BM-107.jpg`
2. Set the card field: `"questionImage": "assets/BM-107.jpg"`
3. Remove or set `"skipUntilImageEmbedded": false`

