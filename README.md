
# Auction Invoice Calculator (PWA)

This is a fast, mobile-friendly **Progressive Web App (PWA)** designed to calculate auction invoices based on:

- Bid Total
- Number of Lots
- Auction Premium (15%)
- Lot Fee ($2/item)
- Sales Tax (8.75%)

## Features

- Modern dark UI optimized for iPhone
- Works offline with Service Worker
- Installable on mobile and desktop
- No dependencies, no build tools — just HTML + JS

## Live Demo

Once deployed on Vercel or another static host, open your browser and try it:

**Example URL**:
```
https://dddar.vercel.app
```

> Add to Home Screen on iPhone or Android to install as an app.

## Files

- `auction.html` — main UI
- `manifest.json` — PWA manifest
- `service-worker.js` — offline caching logic

## Deployment (Vercel Recommended)

1. Log in to [vercel.com](https://vercel.com)
2. Import this GitHub repo
3. Choose **Other** as framework
4. Leave build command empty
5. Set output directory to `.` (dot)
6. Deploy and enjoy

---

**Made by [Stillrem](https://github.com/stillrem)**
