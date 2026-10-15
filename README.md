# GameLine Displays — GameLine Pro Website

A responsive, static product website featuring the **GameLine Pro**, a **5-foot LED sports display** with a planned price of **$999 USD**.

## Included

- Actual product photographs supplied by the creator, optimized to WebP
- Responsive hero, product gallery, features, and product specifications
- Full-screen image viewer and a clearly labeled coming-soon purchasing state
- Cloudflare Workers static-assets configuration (`wrangler.jsonc`)

## Publish to Cloudflare Workers

1. Copy the contents of this folder into your `gamelinedisplays-website` GitHub repository root. Keep the `assets/` folder and `wrangler.jsonc`.
2. Commit and push to `main`.
3. In Cloudflare Workers & Pages → your Worker → Settings → Builds, set the **build command** to blank and **deploy command** to `npx wrangler deploy`.
4. Your connected GitHub build should deploy the update automatically.

## Local preview

Open `index.html` in a browser, or use `python -m http.server 8000` in this folder and visit `http://localhost:8000`.

## Before launch

This is a product preview, not a functioning online store. The $999 price is user-provided. Checkout, payments, inventory, private administration, tax/shipping, policies, customer support and availability must be implemented before taking orders. Confirm final hardware specifications, rights to use third-party sports logos and data, and product compliance before commercial launch.
