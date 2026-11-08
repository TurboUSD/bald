# baldonbase.com

Static, optimized export of the original WordPress (Elementor) site for Bald On Base.
Served as plain static files from `public/` on Vercel: no build step, no serverless functions, no JS frameworks.

- `public/index.html` — the single page, from the live WordPress HTML with WP/plugin scripts removed
- CSS purged to the rules the page uses; images converted to WebP; fonts limited to latin/latin-ext
- Old WordPress URLs (posts, categories, feeds, wp-admin) redirect to `/`
