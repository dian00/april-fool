# GitHub Pages Deploy

This folder is a plain static site for GitHub Pages.

Required files:
- `index.html`
- `main-image.jpg`
- `og-gift.png`
- `.nojekyll`

## Recommended structure

Put these files at the repository root if you want to publish from the root.

## Deploy steps

1. Create a new GitHub repository.
2. Upload all files in this folder to the repository root.
3. In GitHub, open `Settings > Pages`.
4. Under `Build and deployment`, choose `Deploy from a branch`.
5. Select the branch you want, usually `main`.
6. Select the folder `/ (root)`.
7. Save and wait for the Pages URL to be generated.

## Important

- This project now uses relative asset paths, so it works on both:
  - `https://username.github.io/`
  - `https://username.github.io/repository-name/`
- After the real site URL is available, update `og:url` in `index.html`.
- For the most reliable social preview, replace `./og-gift.png` with the full public URL after deployment.
