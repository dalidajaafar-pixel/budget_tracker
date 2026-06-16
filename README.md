# Ledger — Budget Tracker

A clean, single-page budget tracker. Dashboard (live pie + bar charts), Transactions
(add / edit / delete, income & expense, month filter), custom Categories, and CSV Export.
Data persists in the browser via localStorage. No build step, no backend.

## Files
- `index.html` — the app (entry point)
- `support.js` — the runtime it loads (keep it next to index.html)

## Deploy to Vercel
1. Create a new GitHub repo and add `index.html`, `support.js`, and this README.
2. Go to vercel.com → **Add New… → Project** → import the repo.
3. Framework preset: **Other**. No build command, output directory = root. Click **Deploy**.

It's a static site, so it goes live as-is.

## Run locally
Open `index.html` in a browser, or serve the folder: `npx serve .`
