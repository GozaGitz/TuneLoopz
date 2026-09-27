# TuneLoopz prototype

A static, installable web app prototype. Local audio files and playlist metadata are stored by the browser on the current device.

## Preview in VS Code

Open this folder in VS Code and launch `index.html` with the Live Server extension. Service workers and install prompts need `localhost` or an HTTPS site; opening the file directly is fine for a basic preview but does not enable those features.

## Publish with GitHub Pages

1. Create a new GitHub repository for the app.
2. Upload the contents of this folder (`index.html`, `manifest.webmanifest`, `sw.js`, `icon.svg`, and both `icon-*.png` files) to the repository's top level.
3. On GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/(root)`, then save.
5. Wait for GitHub Pages to finish publishing. The site address will look like `https://YOUR-USERNAME.github.io/REPOSITORY/`.
6. Open the HTTPS address on your phone and use the browser's **Add to Home Screen** or **Install app** option.

Because this is a static app, each user's playlists and audio remain in that user's browser storage. They are not uploaded or synced between devices. Clearing site data or uninstalling the browser can remove that local data. Keep original music files backed up elsewhere.

