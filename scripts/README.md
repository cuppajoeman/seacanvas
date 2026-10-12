# Gallery scripts

Run this after adding new painting images to the project folder:

```sh
python scripts/update-gallery.py
```

The script updates the `filenames` list in `index.html`. It puts newly discovered image files at the top of the gallery, preserves the existing gallery order, and keeps intentionally commented-out images excluded.

The image filename is also its gallery title. Use the exact painting title as the filename; for example, `Winter Waterfall.webp` displays as “Winter Waterfall.”
