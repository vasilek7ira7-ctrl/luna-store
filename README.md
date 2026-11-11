# LUNA — portfolio demo store

Static site, no build step. Open `index.html` or upload the whole folder to any static host (GitHub Pages, Netlify, Vercel).

Keep the folder structure: `index.html` + `img/` + `favicon.png` + `apple-touch-icon.png` + `og-image.jpg`.

## Before publishing
1. In `index.html` replace `https://YOUR-DOMAIN.com/` (canonical, og:url, og:image, twitter:image) with the real URL.
2. `favicon.png`, `apple-touch-icon.png`, `og-image.jpg` are generated placeholders (letter on a dark background). Replace them with real artwork, keeping the sizes: 32x32, 180x180, 1200x630.
3. Social links in the footer and mobile menu still point to `#`.

## After publishing
- pagespeed.web.dev (Performance, Accessibility, Best Practices, SEO)
- opengraph.xyz or developers.facebook.com/tools/debug for the link preview

Demo only: orders, payment, accounts and reviews are simulated in the browser (localStorage).
