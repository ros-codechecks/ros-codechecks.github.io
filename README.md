# ros-codechecks.github.io

Website for the ROS CODECHECK study (Amsterdam UMC and TU Delft, funded by Open Science NL and NWO, file 110.110.017).

Live at <https://ros-codechecks.github.io>.

## Structure

- `index.html`: the whole site (single page)
- `404.html`: not-found page
- `assets/style.css`: styles, system fonts only, no third-party requests
- `assets/favicon.svg`
- `.nojekyll`: tells GitHub Pages to serve files as-is, without a Jekyll build

## Editing

Plain HTML and CSS, no build step. Open `index.html` in a browser to preview, or run:

```sh
python3 -m http.server 8000
```

and visit <http://localhost:8000>.

## Publishing

Pushing to `main` publishes the site. In the repository settings under Pages, set the source to "Deploy from a branch", branch `main`, folder `/ (root)`.
