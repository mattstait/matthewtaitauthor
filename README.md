# Matthew Tait — Horror Author

Official website of Matthew Tait, Australian horror author.

## Deployment

Hosted on **Cloudflare Pages**.

### Cloudflare Pages Settings

| Setting | Value |
|---|---|
| Build command | *(leave empty — site is pre-built)* |
| Build output directory | `/` |
| Root directory | `/` |

The site is a pre-built React/Vite static app. No build step required — Cloudflare Pages serves it directly from the repository root.

> **Note:** A `_redirects` file is included to handle client-side routing (all routes fall back to `index.html`).
