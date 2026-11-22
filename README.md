# ClipVariants Landing Page (`clipvariants.com` / `www.clipvariants.com`)

Standalone white-theme landing page (`index.html`, compiled `styles.css`, logo, and scroll-autoplay MP4s under `25 MiB` each for Cloudflare compatibility).

## Deploy via Cloudflare Dashboard + GitHub

- **Cloudflare Workers (Git integration):**
  - Build command: *(leave empty)*
  - Deploy command: `npx wrangler deploy` *(reads `wrangler.jsonc` -> `./public`)*
- **Cloudflare Pages (Git integration):**
  - Framework preset: `None`
  - Build command: *(leave empty)*
  - Build output directory: `public`

Once deployed, add both `clipvariants.com` and `www.clipvariants.com` under **Settings → Domains & Routes → Add Custom Domain**.
