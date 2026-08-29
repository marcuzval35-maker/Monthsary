# Monthsary Website

A static, GitHub Pages-ready personal website. No build step, web server, or environment variables are required.

## Files

- `index.html` — the complete website
- `assets/audio/coffee-by-miguel.mp3` — the background music
- `assets/html2canvas.min.js` — a local copy of the screenshot helper, included so the capture button does not rely on a CDN
- `.nojekyll` — tells GitHub Pages to publish this folder as plain static files

## Test it locally

Open `index.html` in a modern browser. Photos, captions, names, dates, and the letter are stored only in that browser on that device.

## Publish with GitHub Pages

1. Create a new GitHub repository. Any repository name works.
2. Upload every file and folder in this project, keeping the folder structure exactly as shown above. `index.html` must be at the repository root.
3. In the repository, open **Settings** → **Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and the `/ (root)` folder, then save.
6. Wait for GitHub to finish publishing. The Pages address appears at the top of the same screen.

For a project repository named `monthsary-site`, the public address is usually:

`https://YOUR-GITHUB-USERNAME.github.io/monthsary-site/`

For a repository named `YOUR-GITHUB-USERNAME.github.io`, it is:

`https://YOUR-GITHUB-USERNAME.github.io/`

## Updating the site

Edit `index.html` and replace the MP3 at `assets/audio/coffee-by-miguel.mp3` if desired. Then commit and push the changes; GitHub Pages will republish automatically.
