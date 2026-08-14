# Stitchline

A before-and-after photo composer for **ETA Jumpsuit Restorations**, built for Instagram and Facebook.

Build up to eight before/after pairs at once, each exported as a 1080×1350 (4:5) image:

- **Crop on upload** — trim a photo down before it lands in a pair, with quick vertical/horizontal snap presets
- **Reposition & zoom** — drag to pan, scroll to zoom, auto-fit to re-center
- **Brightness** adjustment per photo
- **Photo bin** — add a batch of photos at once, then drag each onto the slot it belongs in
- **Swap** — flip the before/after photos in a pair with one click
- **Batch naming** — name the set once, every downloaded file picks it up automatically
- **Download all** — save every finished pair in one pass

Everything runs client-side in the browser — no photos are ever uploaded anywhere.

## Use it

Open `index.html` directly in a browser, or visit the hosted version via GitHub Pages.

## Note on saving

This project was originally built as a Claude Artifact, where a `Save Image` capability lets the browser hand a finished file straight to disk with one click. Outside that environment (e.g. here, on GitHub Pages), the save button falls back automatically to a simple "long-press or right-click the image to save it" step — everything else works identically.
