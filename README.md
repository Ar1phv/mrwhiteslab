# mrwhiteslab

A static HTML publication and research site built around a multi-part blockchain, digital assets, and web3 education narrative.

## Contents

- `index.html` — landing page
- `part-00-author.html` through `part-12-research-vault.html` — content chapters
- `*.png` assets — author photos, OG image, favicons, and cover art
- `LICENSE` — project license

## Local preview

From the repository root:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## GitHub Pages publishing

1. Push the repository to GitHub.
2. Open the repository in GitHub.
3. Go to Settings → Pages.
4. Set Source to:
   - Deploy from a branch
5. Set Branch to:
   - `main` (or the default branch used by the repo)
   - `/ (root)`
6. Save.
7. Wait a minute or two for GitHub to build the site.
8. Visit the Pages URL shown in the settings page.

## Notes

- This repo is a static website, so there is no build step.
- The site is designed to be served directly from the repository root.
- If you want to host a custom domain later, you can add a CNAME and configure DNS in your domain provider.
- Archive ZIP files in the root can be kept for distribution, or moved to GitHub Releases if you want a cleaner public site.
