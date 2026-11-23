# computerphysicslab.github.io

Landing page for the user GitHub Pages site: <https://computerphysicslab.github.io/>.

GitHub serves a user site from the root of the `main` branch in the repository named exactly
`computerphysicslab.github.io`. `index.html` is the homepage; a `README.md` by itself is not
served as a Pages homepage.

To add or update a link, edit the two `<ul>` lists in `index.html` (live demos first, code second).
Each entry has an original SVG thumbnail in `assets/`, referenced with `<img class="thumb">`;
new thumbnails should keep the 480x300 viewBox and the same dark visual style. Then commit and
push to `main`. No Jekyll, build step, secrets or external assets are used; `.nojekyll` keeps
the static files untouched.

Pages source: **Settings → Pages → Build and deployment → Deploy from a branch → main / (root)**.

The documentation in this repository is licensed under CC BY-SA 4.0; see `LICENSE-DOCS.md`.
