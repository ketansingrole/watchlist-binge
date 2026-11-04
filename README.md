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
- Full screens, status bar included, overridden to look like a real device: 9:41, full Wi-Fi
  and cellular bars, white battery at 100% (`--batteryState discharging --batteryLevel 100`).
  A charging battery (green with a bolt) looks fake. iPad: same, without the cellular flags.
- iPad in both orientations: landscape (sidebar) in the hero, portrait for Details.
- Flat, side by side. Never stack one screenshot on another.
- Shown flat with a thin edge: no device frames, no tilt, nothing stacked on top of anything else.

When the app is live, swap the "Coming soon" copy for an App Store link
(`https://apps.apple.com/app/id6778711336`).
