# ForgeMarket

**Live on GitHub main** — ready for Vercel.

A beautiful, fully interactive preview of a fairer handmade marketplace (products + bookable services) with 3.5% fees.

## 🚀 Deploy to Vercel (fastest)

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fcajub311%2Fforgemarket)

Click the button above → import the repo → instant preview on Vercel.

## Current Status

- `index.html` + full interactive site is on `main`
- All JS features work (booking, cart with savings math, dynamic listings, etc.)
- Images are in the local folder (push them after you `gh auth login` + `git push`)

## Quick local check + push

```bash
cd Projects/maker-market-preview

# Authenticate (one time)
gh auth login

# Then push everything (including images)
git push -u origin main
```

After pushing images, redeploy on Vercel.

## Features

- Products & Services in one feed
- Working booking system with time slots
- Cart showing "saved vs Etsy"
- Sell on Forge (add listings live)
- 3.5% fee positioning throughout

Repo: https://github.com/cajub311/forgemarket

Built with Grok.