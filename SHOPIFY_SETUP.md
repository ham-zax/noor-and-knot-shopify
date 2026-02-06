# Noor & Knot Shopify Theme (Starter)

This repo is based on Shopify Dawn and includes a custom homepage section:

- `sections/noor-landing.liquid`
- `assets/noor-and-knot.css`
- `templates/index.json`
- media assets copied from your current site (`assets/noor-*.jpg`, `assets/noor-video-*.mp4`)

## Quick Start

1. Install Shopify CLI:
```bash
npm install -g @shopify/cli @shopify/theme
```

2. Login:
```bash
shopify login --store YOUR-STORE.myshopify.com
```

3. Run locally:
```bash
shopify theme dev
```

4. Push theme:
```bash
shopify theme push --unpublished
```

## Theme Customizer

Open Online Store -> Themes -> Customize.

Homepage uses **Noor Landing** section.

Update these settings:
- WhatsApp URL
- Instagram URL
- Heading/subheading
- Product cards (image, title, description, price)

## Notes

- Currency/pricing text is currently set to INR in section defaults.
- For production, connect your Shopify payments/shipping settings in Shopify admin.
