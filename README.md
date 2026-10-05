# Yas portfolio

Personal portfolio and product collection at https://yasmerak.site.

## Pages

- `/` — Yas’s portfolio and selected work
- `/apps/weavernote/` — connected notes and AI study tools
- `/apps/expense-whisper/` — voice expense tracker for iPhone and iPad

## Development

A static HTML/CSS site, published from `main` at the repository root. `CNAME` preserves the custom domain and `.nojekyll` disables Jekyll processing.

Preview with `python3 -m http.server 8080 --bind 127.0.0.1`.

## Adding a product

Create `apps/<product>/index.html`, reuse `assets/styles.css`, add a card to the homepage, and update `sitemap.xml`. Product pages can live here permanently or link to a dedicated product website where applicable. Link visitors to the product and its store listing; do not add source-code or developer-account links.

## Identity and content

The public portfolio name is Yas; full name is Yas Merak. Use only these names in portfolio content. Use the blue geometric Y identity, not an asterisk motif.

Weavernote features and public assets are based on the product codebase. Expense Whisper features are based on its App Store listing and local codebase; its gallery uses existing product images from the local marketing assets. Refer to the App Store for current availability and in-app purchase details.
