# Urban Notes

A frontend-only static blog designed for GitHub Pages.

## Files
- `index.html` — main blog page
- `style.css` — responsive styling
- `script.js` — small interaction
- `images/` — four included SVG image assets (no external image dependency)
- `robots.txt` — crawler instructions
- `sitemap.xml` — sitemap for search engines

## GitHub Pages
1. Create a GitHub repository, for example `urban-notes`.
2. Upload all files and the `images` folder.
3. In **Settings → Pages**, select **Deploy from a branch** and choose `main` / root.
4. Your site will be available at `https://YOUR-USERNAME.github.io/urban-notes/`.
5. Before publishing, replace `YOUR-USERNAME` in `index.html`, `robots.txt`, and `sitemap.xml`.

## Google Search Console
Add the GitHub Pages URL as a property, verify ownership, then use URL Inspection to request indexing. Submit the sitemap URL:
`https://YOUR-USERNAME.github.io/urban-notes/sitemap.xml`

Google does not guarantee immediate indexing or ranking. Original, useful content and crawlable pages matter.


## Included images
The `images` folder contains four self-contained SVG illustrations. They are stored inside the repository, so the blog does not depend on an external image host and the images will display on GitHub Pages after upload.
