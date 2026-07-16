# Gallery scripts

Run this after adding new painting images to the project folder:

```sh
python scripts/update-gallery.py
```

The script updates the `filenames` list in `index.html`. It preserves the existing gallery order, keeps intentionally commented-out images excluded, and appends newly discovered image files.
