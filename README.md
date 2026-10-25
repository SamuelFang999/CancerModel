# CancerModel

An interactive cancer body map built around Pichael Productions’ Grey Man model.

## Run the viewer

Install the dependencies once, then start the local web server:

```sh
pnpm install
pnpm start
```

Open [http://localhost:4173](http://localhost:4173). The FBX model and its texture are served from `assets/`.

## Publish with GitHub Pages

The `Deploy CancerModel to GitHub Pages` workflow builds a static copy of the viewer, including Three.js and the model assets, and deploys it whenever changes are pushed to `main`.

1. Push the repository to GitHub.
2. In the repository, open **Settings → Pages** and set **Build and deployment → Source** to **GitHub Actions**.
3. Push a commit to `main`, or run the workflow manually from the **Actions** tab.

After the first successful deployment, GitHub shows the public site URL under **Settings → Pages**. The viewer's local `pnpm start` workflow continues to work as before.

## Cancer list and medical sources

The body map uses the National Cancer Institute’s U.S. common-cancer categories and 2026 U.S. incidence estimates from SEER (Cancer Facts & Figures 2026, American Cancer Society). The body markers are schematic primary-site illustrations. This educational viewer is not a diagnostic tool.

- [NCI Common Cancer Types](https://www.cancer.gov/types/common-cancers)
- [SEER Common Cancer Sites](https://seer.cancer.gov/statfacts/html/common.html)

Each cancer detail card links to its NCI overview page.

## Model attribution

“Male Character - Grey Man” by Pichael Productions, [Sketchfab](https://sketchfab.com/3d-models/male-character-grey-man-f3139eca23564711bb8c3c83b0e12303), licensed under [Creative Commons Attribution 4.0](https://creativecommons.org/licenses/by/4.0/).
