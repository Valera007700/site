# newlibram static site

Static landing page prepared for local preview and GitHub Pages.

Public URL after enabling GitHub Pages:

`https://valera007700.github.io/site/`

## Structure

- `index.html` is the deployable entry point for GitHub Pages.
- `assets/logos/` contains local SVG brand assets used by the page.

## Local run

The page is static, but it depends on external Tilda CDN assets, so local preview requires internet access.

Run from the project root:

```bash
python3 -m http.server 8000
```

Then open `http://127.0.0.1:8000/`.

## GitHub Pages

1. Push the repository to GitHub.
2. In the repository settings, open `Pages`.
3. Set `Build and deployment` to `Deploy from a branch`.
4. Select the `main` branch and `/ (root)` as the folder.
5. Save.

## Optional custom domain

If you want to publish the site on a custom domain such as `newlibram.com`, add a `CNAME` file later with that domain name and configure DNS on your registrar.
