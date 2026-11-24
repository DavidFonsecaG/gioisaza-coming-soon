# gioisaza.com: coming soon page

Static page shown at gioisaza.com until the Shopify store launches.

- `index.html`: the page (English first, Spanish toggle)
- `img/looks/`: the runway looks (backgrounds removed)
- `img/`: wordmark, monogram, favicons

No build step. Deployed with Cloudflare Pages: build command empty, output directory `/`.

Deploys run through Cloudflare Workers Builds on every push to `main` (see `wrangler.jsonc`).
