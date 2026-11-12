# dev-showcase-raych

Source for Rachel Chong's legal-tech project showcase, live at https://dev-showcase-raych.rachelcjw101.workers.dev/

- `public/index.html` — the whole site (one static page, no build step)
- `wrangler.jsonc` — tells Cloudflare to serve `public/` from the `dev-showcase-raych` Worker

Pushing to `main` redeploys the site once the Worker is connected to this repo in Cloudflare (Worker → Settings → Builds).
