Trip Split Tracker - hosting on GitHub Pages
============================================
Upload ALL of these files to the top level of a public GitHub repository (not the zip itself):
index.html, manifest.webmanifest, sw.js, icon-192.png, icon-512.png, icon-maskable-512.png

Then: Settings > Pages > Deploy from a branch > main / (root) > Save.
Your address will look like https://YOURNAME.github.io/REPOSITORY/

Install: Android Chrome menu > Install app. iPad/iPhone Safari: Share > Add to Home Screen.

Updating later: upload the new index.html, then edit sw.js and raise the version (trip-split-v5 -> v6)
so devices pick up the update. Your data is stored on each device, per web address.
