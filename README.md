# Yasmerak

Yasin’s portfolio and product collection, published at https://yasmerak.site.

## Pages

- `/` — portfolio and selected work
- `/apps/weavernote/` — Weavernote product page

This is a static HTML/CSS site. GitHub Pages publishes `main` from the repository root. `CNAME` preserves the custom domain; `.nojekyll` disables unnecessary Jekyll processing.

Preview locally with `python3 -m http.server 8080 --bind 127.0.0.1`.

## Adding a product

Create `apps/<product>/index.html`, reuse `assets/styles.css`, add the product to the homepage, and update `sitemap.xml`. Use verified features and actual product assets. Keep credentials and unrelated application source outside this repository.

## Product content

Weavernote copy is based on its About page, feature pages, and implemented workflows. Product images are the existing public logo, workspace, visualizer, and AI Studio WebP assets from the Weavernote codebase. Feature availability and pricing remain linked to the product’s own website.
