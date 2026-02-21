# OpenLayers KML Map (GitHub Pages)

This repository hosts a simple OpenLayers web map that loads **Iran_new.kml** and shows a popup when you click any feature.

## Files
- `index.html` — the OpenLayers map page
- `Iran_new.kml` — your data

## Publish on GitHub Pages
1. Create a new GitHub repo (e.g. `iran-kml-map`)
2. Upload **all files** from this folder into the repo root
3. In GitHub: **Settings → Pages**
4. Source: **Deploy from a branch**
5. Branch: **main** (or master) and folder **/(root)**, then Save
6. Your map will be at:
   `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/`

## Notes
- Click a feature to view its attributes in a popup.
- The map auto-zooms to the KML extent after it loads.
