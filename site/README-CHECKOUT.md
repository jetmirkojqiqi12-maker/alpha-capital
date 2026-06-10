# Alpha Capital Webflow Site (with live checkout)

Checkout is integrated on:

- `index.html` — below the pricing plans section
- `product.html` — below **Still Not Sure? Check out our other plans** (`.pricing_seaction`)

## Preview locally

```bash
npx --yes serve . -l 8080
```

- http://localhost:8080/index.html
- http://localhost:8080/product.html

## Re-integrate after checkout updates

```bash
cd ../alpha-capital-checkout
npm run export:webflow
node scripts/integrate-webflow-site.mjs "/path/to/your/webflow-site-folder"
```
