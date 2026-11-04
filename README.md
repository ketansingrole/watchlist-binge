# watchlist-binge

Landing page and privacy policy for the **Watchlist Binge** app (iPhone and iPad).

- Landing: https://ketansingrole.github.io/watchlist-binge/ (App Store Support URL)
- Privacy: https://ketansingrole.github.io/watchlist-binge/privacy.html (App Store Privacy Policy URL)

Plain HTML and CSS (`index.html`, `privacy.html`, `style.css`), no build step. GitHub Pages
serves `main` as is. The app's own repo is private; this one is public only so Pages can serve it.

## Screenshots

`shots/` holds dark-mode captures from the app's screenshot demo library (`-ScreenshotDemoLibrary`,
see `scripts/app-store-screenshots` in the app repo). Its title list avoids Disney-owned and
Apple TV+ artwork; App Review rejected a build over Toy Story art, and this page is the Support
URL, so keep using that library.

- Dark only: light screens glare on this dark page.
- Cropped below the status bar. Don't use `simctl status_bar override` (fake 9:41) shots here.
- Shown flat with a thin edge: no device frames, no tilt, nothing stacked on top of anything else.

When the app is live, swap the "Coming soon" copy for an App Store link
(`https://apps.apple.com/app/id6778711336`).
