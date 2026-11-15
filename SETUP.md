# Set up your GitHub profile README

This package was prepared for `github.com/Fahrin720`.

## 1. Create or open the profile repository

Visit https://github.com/Fahrin720/Fahrin720. Your profile repository must be public and have the exact same name as your username.

## 2. Add the files

Keep this exact structure at the root of your profile repository:

```
Fahrin720/
├── README.md
└── assets/
    └── cover.svg
```

Replace the existing `README.md` only if you want to replace your current profile content. Upload `cover.svg` to the `assets` directory.

## 3. Preview

Visit https://github.com/Fahrin720. The README displays directly on your profile.

## 4. Customize later

Open `profile-studio.html` in a browser, edit the text/colors, and select the projects you wish to show. Use **Sync GitHub** for live public repository metadata, then download the new cover and README and commit both files again. Changing the editor does not automatically update GitHub.

## Notes

- The SVG is standalone: no external fonts, scripts, external images, or fetches inside the exported image.
- The editor *optionally* loads Google Fonts for its own interface; it will fall back to system fonts offline.
- Public GitHub API sync may be limited by your network or GitHub's unauthenticated API rate limit. On failure, the editor shows an error instead of fictional metrics.
- Featured projects in the included `README.md` were selected from the publicly visible repositories, not created by the app's offline fallback.
- Minimal SVG animation is optional. Rendering can vary across GitHub's image proxy, so the design remains legible in its static frame.
