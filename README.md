# ASHEN ISLAND — Forest & Ruins Upgrade

A browser-based first-person survival-horror prototype built with Three.js. This upgrade adds a denser, more textured forest, weather-beaten facility ruins, layered pine boughs and roots, undergrowth, scattered debris, procedural surface textures, improved moonlight/shadows, and low ground mist. Textures are generated in the browser, so there are no large image assets to manage.

## Play

- Open `index.html` through a local web server or publish the folder with GitHub Pages.
- An internet connection is required because Three.js is loaded from jsDelivr.
- Desktop: click **ENTER THE ISLAND**, use **WASD** to move, **Shift** to run, **F** for flashlight, **E** to collect fuses, and mouse to look.
- Mobile: tap **TAP TO ENTER**, use the left joystick to move, drag the right side to look, and use the touch buttons.
- Find three amber fuses and reach the extraction gate at the north end. Avoid the creatures.
- Open **SETTINGS** to adjust graphics quality, touch sensitivity, film grain, and shadows.

## What changed in this upgrade

- Procedural ground, concrete, wall, bark, and rust textures created locally with CanvasTexture.
- More layered pine trees with branch silhouettes, root flares, and denser boughs.
- Fern-like undergrowth, dead brush, fallen branches, and scattered stones/debris.
- Abandoned structures with raised foundations, window frames, doorways, roof beams, broken wall fragments, grime streaks, and electrical boxes.
- Better moonlight fill, expanded shadow map, darker forest fog, and slow-moving ground mist.
- Kept the existing fuse objective, creature AI, flashlight, HUD, desktop controls, and mobile touch controls.

## Publish with GitHub Pages

1. Download and unzip the project.
2. Open your GitHub repository, then choose **Add file → Upload files**.
3. Upload `index.html`, `README.md`, and `.gitignore` from this folder. If GitHub asks whether to replace files already in the repository, replace the existing files rather than creating duplicates.
4. Enter a commit message such as `Upgrade forest, ruins, textures and lighting`, then click **Commit changes**.
5. In the repository, open **Settings → Pages**.
6. Under **Build and deployment**, choose **Deploy from a branch**, select branch `main` and folder `/(root)`, then save.
7. Wait for the Pages deployment to finish. Open the website link shown in the Pages section.

## Performance notes

- Start with **Low (mobile)** quality on older phones. Medium or High can look better but may reduce frame rate.
- This is still a procedural prototype, not a finished photorealistic commercial game. The world is assembled from generated geometry and textures.
- If the game does not load, confirm internet access (for the Three.js CDN) and open the browser console for errors.
