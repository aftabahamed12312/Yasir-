# Yasir-

This repository contains a static website served from the repository root.

Deploy it to Cloudflare Workers with static assets using:

```sh
npx wrangler deploy
```

Wrangler is configured in `wrangler.jsonc`; the root `index.html` is the
site's entry page and `_headers` defines response headers.
