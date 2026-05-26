# ✈️ AirAsia QR Generator

A branded QR code generator for AirAsia Group airlines — deployable to Vercel in one click.

## Features

- **9 Airline Codes** — AK, D7, QZ, FD, Z2, XT, XJ, BIG, AVA
- **AirAsia logo** embedded in every QR code
- **Flight details** — flight number, route, date, seat, passenger name
- **Custom QR data** — override with any URL or text
- **Style controls** — QR color, background color, size, logo size
- **Error correction** levels (L / M / Q / H)
- **Download** as PNG or SVG

---

## Deploy to Vercel

### Option 1 — Vercel CLI (fastest)
```bash
npm i -g vercel
cd airasia-qr
vercel
```
Follow the prompts. Done! 🎉

### Option 2 — Drag & Drop
1. Go to [vercel.com/new](https://vercel.com/new)
2. Drag the `airasia-qr` folder onto the page
3. Click **Deploy**

### Option 3 — GitHub
1. Push this folder to a GitHub repo
2. Import the repo at [vercel.com/new](https://vercel.com/new)
3. Vercel auto-detects it as a static site — click **Deploy**

---

## Local Development

Just open `index.html` in a browser — no build step needed.

```bash
# Or use a simple server:
npx serve .
```

---

## Project Structure

```
airasia-qr/
├── index.html    ← Single-file app (HTML + CSS + JS)
├── vercel.json   ← Vercel deployment config
└── README.md
```

---

## Tech Stack

- Vanilla HTML/CSS/JS — zero build tools
- [qrcode.js](https://github.com/soldair/node-qrcode) via CDN
- Google Fonts (Barlow Condensed)
- Vercel static hosting

---

*Built for AirAsia Group internal/demo use.*
