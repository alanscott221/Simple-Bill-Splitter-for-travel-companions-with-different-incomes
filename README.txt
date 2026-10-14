Trip Split Tracker - hosting on GitHub Pages
============================================
1. Create a free account at github.com and click New repository (name it e.g. trip-split, set it to Public).
2. Click "uploading an existing file", drag in ALL the files from this folder (index.html, manifest.webmanifest, sw.js and the three icon-*.png files) and click Commit changes.
3. Go to Settings > Pages. Under "Build and deployment" choose Source: Deploy from a branch, Branch: main, folder: / (root), then Save.
4. After a minute or two the page shows your address, like https://YOURNAME.github.io/trip-split/
5. Open that address on your phone or iPad.
   - Android (Chrome): menu > Install app.
   - iPad / iPhone (Safari): Share > Add to Home Screen.

Updating later: upload the new index.html over the old one, and change the version in sw.js (trip-split-v3 -> v4) so devices pick up the update.

Note: data is stored per device and per web address, so a new address starts empty.
