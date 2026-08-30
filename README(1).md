# Hungry Birds AR Menu — final site

Upload every file in this folder to any static host (GitHub Pages, Netlify, Cloudflare Pages).
Keep the files together. Do not open index.html as a saved file if you want camera AR.

## Tested
- Menu page loads
- Pizza and burger 3D models load and stand upright
- AR page loads both dishes
- Buttons go to ar.html?dish=pizza and ar.html?dish=burger
- QR code points at the live page address
- AR startup now tries a minimal WebXR hit-test session, retries without DOM overlay, then automatically falls back to Android Scene Viewer when WebXR cannot start
- Local HTML/JavaScript syntax checks pass
- All packaged HTML/model/poster assets return HTTP 200 from a local static server

Camera AR can only be finished on a phone:
1. Publish this folder to https
2. Open the link in Chrome on Android
3. Tap Place on my table
4. Tap Start camera AR and allow the camera
5. Tap the table to set the dish down

## Files
- index.html
- ar.html
- colored_pizza.glb
- burger.glb
- pizza-poster.jpg
- burger-poster.jpg
- .nojekyll (helps GitHub Pages)
