# Investment Projection Tool — William Gray

A single-page tool for projecting portfolio returns under two modes:

- **Linear** — apply a constant assumed annual return.
- **Historical** — apply actual blended portfolio returns from a chosen calendar-year window (1996–2025).

The tool supports nine asset classes (S&P 500, FTSE 100, MSCI World, MSCI Emerging Markets, Bloomberg US Aggregate Bond, Gold, USD T-Bills, XLK, EURO STOXX 50), three preset allocations, and exports a print-ready PDF report.

## Local preview

It's a single static file. Open `index.html` in any browser, or serve the folder:

```bash
npx serve .
```

## Deployment

Hosted on Vercel as a static site. No build step — Vercel serves `index.html` from the project root.

## Disclaimer

For illustration only. Not financial advice. See the disclaimer at the foot of the tool itself.
