# GitHub Pages Setup

This folder is ready to publish as a simple GitHub Pages site.

## Files used

- `index.html` — the hosted itinerary homepage
- `TreCimeParkingPass.png` — image used inside the itinerary
- `.nojekyll` — tells GitHub Pages to serve the site as plain static files

## Fastest publish path

1. Create a new GitHub repository.
2. Upload these files to the root of the repository:
   - `index.html`
   - `TreCimeParkingPass.png`
   - `.nojekyll`
3. In GitHub, open `Settings` -> `Pages`.
4. Under `Build and deployment`, choose:
   - `Source`: `Deploy from a branch`
   - `Branch`: `main`
   - `Folder`: `/ (root)`
5. Save.
6. Wait a minute or two for GitHub Pages to publish.

Your URL will usually be:

`https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/`

## Optional cleanup

You can keep the original local file:

- `Switzerland 26 Itinerary Styled.html`

But GitHub Pages will use:

- `index.html`

## Important note

The jump links at the top should behave much more reliably once the file is served over `https://` instead of opened locally from `file:///...`.
