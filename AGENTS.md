# Project architecture

This is a static website supplied as a complete ZIP archive. Netlify publishes `public/` directly using `netlify.toml`; there are no package dependencies or build commands.

## Directories

- `public/`: seven HTML pages and the favicon.
- `public/img/`: restaurant and food photography, including `gallery/`.
- `.netlify/assets/`: original uploaded source archives; not published.

## Conventions

Preserve the supplied copy, design, inline CSS, and JavaScript unless changes are requested. Keep page links and asset paths relative. Shared page styles and scripts are repeated across HTML files, so changes to shared behavior must be applied consistently. Metadata belongs in each document head. Do not add a single-page-app fallback: the pages are individual HTML documents.
