# Thomas Digital Shop — Resellers Website

Reseller website for Thomas Digital Shop — Digital Product Myanmar's digital subscriptions and AI tools shop, for resellers.

Live site: https://thomasdigitalshopresellerwebsite.vercel.app

## What this site is

A single-page static website (`index.html`) that lists the shop's digital products and plans, with prices in Myanmar kyat (Ks). Visitors can browse the catalog, build an order in the cart, and then contact the admin on Telegram to place the order. There is no account, sign-in, or on-site payment checkout in this repository.

## What it lists

Products are grouped by category in the store, with search, category filters, and sorting. Categories in `index.html` include:

- **AI Tools** — ChatGPT, Claude AI, Gemini, Grok AI, GitHub Copilot, Cursor AI, Perplexity AI, HeyGen, Runway, ElevenLabs, Leonardo AI, Gamma AI, and others
- **VPN** — Express VPN, LetsVPN, NordVPN, Surfshark, ExitLag, Outline VPN, V2Box, HMA VPN
- **Adobe Suite** — Creative Cloud, Photoshop, Lightroom, Premiere Pro, Illustrator, After Effects, Acrobat Pro, InDesign, and others
- **Editing apps** — CapCut Pro, Alight Motion, Canva Pro, Picsart, Remini, Wink, VSCO, PhotoRoom
- **Streaming, music, and social** — Netflix, HBO Max, Crunchyroll, Spotify, Apple Music, YouTube Premium, TikTok Japan, Zoom
- **Telegram and storage** — Telegram Premium, Telegram Boosting, TeraBox, Google Drive, Google One
- **Education** — Duolingo Super, Coursera, Microsoft 365, WPS Office
- **Payment accounts** — PayPal, Wise, Payoneer
- **Boosting services** — Facebook, Instagram, TikTok, and Telegram boosting

Each product shows its available plans and durations. Prices and plans change, so check the live site for the current listing — this README does not duplicate the price list.

## How ordering works on the site

1. Browse the store, search, or filter by category.
2. Open a product to see its plans, choose quantities, and add them to the cart.
3. At checkout, the site shows payment instructions for KBZPay and WavePay and generates an order receipt.
4. Copy the order details and message the admin on Telegram to confirm the order.

## Service hours shown on the site

- Monday–Friday: 4:30 PM – 12:00 AM
- Saturday: 9:30 AM – 12:00 AM
- Sunday: Off

## Contents

- `index.html` — the reseller website (single-page static site; Tailwind CSS via CDN and vanilla JavaScript, no build step)
- `LICENSE` — MIT License

## View locally

Open `index.html` in a browser, or serve the folder with any static file server. An internet connection is needed for the CDN assets (Tailwind CSS, Font Awesome, and Google Fonts) used by the page.

## Contact

Telegram: https://t.me/Thomas_Shops

## License

MIT — see [LICENSE](LICENSE).
