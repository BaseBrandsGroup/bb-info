# bb-info (Base Brands info pages for prospects)

Public GitHub Pages site for pages we send direct to prospects and clients: pricing, service info, proposals. Live at https://basebrandsgroup.github.io/bb-info/<folder>/

## Rules
- One folder per page, lowercase with dashes (e.g. `meta-pricing-detailed`), holding an `index.html`.
- Every page must carry `<meta name="robots" content="noindex, nofollow">`; `robots.txt` blocks crawlers too.
- The root `index.html` stays a plain "use the link you were sent" page. Never list pages there or link them anywhere.
- Public to anyone with the link: no client data, passwords or keys.
- Pages are final when handed over: don't edit the HTML unless asked.

## Publishing
Push with the `GITHUB_PERSONAL_ACCESS_TOKEN` from Claude's settings via a one-off `http.extraheader` (`gh` isn't installed). Pages updates 1-2 minutes after a push.
