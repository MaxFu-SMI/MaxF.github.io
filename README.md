# Max Fu | Portfolio

A static portfolio site. No build step, no dependencies.

## Files
- `index.html` : the page (edit the project cards here)
- `style.css` : the styling (supports light and dark mode)
- `assets/` : put your videos, GIFs, images, and `Max_Fu_Resume.pdf` here
- `.nojekyll` : tells GitHub Pages to serve the files as-is

## Edit it
1. Search `index.html` for `[` to find every bracketed placeholder and replace it with your own text.
2. Search for `YOUR-USERNAME` and `YOUR-PROFILE` and replace them with your GitHub and LinkedIn names.
3. For each project, replace the `<div class="placeholder">` with a `<video>`, `<img>`, or YouTube `<iframe>` (examples are in the comments).
4. Copy your resume to `assets/Max_Fu_Resume.pdf`.

## Preview locally
Open `index.html` in a browser, or run `python3 -m http.server` in this folder and visit http://localhost:8000.

## Host on GitHub Pages (free)
1. Create a new public repository on GitHub. For a clean address, name it `YOUR-USERNAME.github.io`.
2. Upload these files to the repository (or use `git add . && git commit -m "Portfolio" && git push`).
3. In the repository, go to **Settings > Pages**, set the source to **Deploy from a branch**, choose `main` and `/ (root)`, and save.
4. Your site will be live at `https://YOUR-USERNAME.github.io` within a minute or two.

## Tips
- Keep videos short (10 to 30 seconds) and under 25 MB each. GitHub files over 100 MB are rejected. Longer demos are better on YouTube, embedded with an `<iframe>`.
- To use your own domain, add it under **Settings > Pages > Custom domain**.
- Unity WebGL builds can be hosted too: put the build folder in the repo and link to its `index.html`, or embed it with an `<iframe>`.
