# APAC Macro Dashboard

Live dashboard tracking macroeconomic indicators across 8 APAC markets:
Singapore, Japan, Australia, South Korea, Indonesia, Philippines, Vietnam, and Malaysia.

## Features

- **FX Rates** — Live EUR exchange rates via ExchangeRate-API + 6-month historical trend (ECB/Frankfurter)
- **Inflation** — CPI annual % from World Bank
- **Interest Rate** — Lending rate % from World Bank
- **GDP Growth** — Annual GDP growth % from World Bank

## Deploy

### Netlify
1. Connect this repo at [app.netlify.com](https://app.netlify.com/) → Add new site → Import from GitHub
2. No build settings needed — it auto-detects

### Vercel
1. Connect this repo at [vercel.com/new](https://vercel.com/new) → Import from GitHub
2. No build settings needed — it auto-detects

## FX API Key

On first visit, paste your free API key from [exchangerate-api.com](https://www.exchangerate-api.com/).
The key is saved in your browser's local storage.

## Data Sources

| Indicator | Source | Refresh |
|-----------|--------|---------|
| FX Rates (live) | ExchangeRate-API | Daily |
| FX Rates (historical) | ECB via Frankfurter | Daily |
| Inflation, Interest Rate, GDP | World Bank | Annual |
