# Evans Nyonje — Personal Portfolio

A responsive, static personal portfolio for AI engineering and full-stack development work.

## Run locally

Open `index.html` in a browser. No build step or package installation is required.

## Deploy

Deploy this folder as a static site to Vercel, Netlify, GitHub Pages, or any static hosting provider. The site root is this folder; no build command is required.

## Update before launch

- Confirm project descriptions and technical stacks against each repository.
- Add verified live demo URLs only where the deployed application is working and publicly accessible.
- Add a downloadable CV if desired.
- Add a custom domain after selecting and registering one.

The portfolio intentionally links to source repositories rather than claiming unverified production capabilities.


## Media manager
Open `admin.html` in the same browser as the portfolio to manage profile photos, project screenshots, gallery images and YouTube demos. Media is stored locally in that browser using IndexedDB. Use **Export backup** to save your media data and **Import backup** to restore it.

**Publishing limitation:** this static version does not sync uploads to a public cloud server. Media added in the manager appears in the portfolio in that same browser only. To publish uploads for all visitors, connect a cloud media service/backend and admin authentication before using the manager on a public deployment.


## SEO files included

- `robots.txt` allows search engines to crawl the public portfolio and points to the sitemap.
- `sitemap.xml` lists the canonical homepage.
- The homepage includes a canonical URL, social-sharing metadata and Person/WebSite structured data.
- `favicon.svg` supplies a lightweight browser icon.

After deploying these changes:
1. Open Google Search Console and add `evansnyonje.nexusthecore.com` as a URL-prefix property.
2. Verify ownership using the HTML tag or DNS method provided by Search Console. If using the HTML tag method, add the exact verification meta tag to `index.html` before deploying.
3. In Search Console, submit `https://evansnyonje.nexusthecore.com/sitemap.xml`.
4. Use URL Inspection for the homepage and request indexing.

The sitemap and canonical metadata use `https://evansnyonje.nexusthecore.com/`. Update both if the public domain changes.
