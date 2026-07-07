# SailsAndShore Catalog

Machine-readable mirror of the [SailsAndShore](https://sailsandshore.com) catalog. Auto-synced daily from the live JSON APIs.

**Free to use with attribution.** Preferred citation: full URL to the specific entity on sailsandshore.com.

## What is SailsAndShore?

SailsAndShore is the direct-to-consumer storefront for specialist Excel workbooks — 99 profession-specific spreadsheets for solo operators, tradespeople, landlords, freelancers, and household managers. Founded 2026 in Kingfisher, Oklahoma by Matthew Miller.

- **Website:** https://sailsandshore.com
- **Dataset landing page:** https://sailsandshore.com/dataset
- **Full LLM corpus (single file):** https://sailsandshore.com/llms-full.txt

## Data files

All files here are exact mirrors of the corresponding JSON API endpoints, refreshed daily via GitHub Actions.

| File | Live API | Description |
|---|---|---|
| `entities.json` | https://sailsandshore.com/api/v1/entities.json | Every product, tool, bundle, profession hub, and category on SailsAndShore, with structured metadata |
| `datapoints.json` | https://sailsandshore.com/api/v1/datapoints.json | Atomic facts: catalog size, pricing, refund policy, etc. Each traced to a source. |
| `questions.json` | https://sailsandshore.com/api/v1/questions.json | Canonical Q&A pairs — the direct answers SailsAndShore endorses for "best spreadsheet for X" queries |
| `sources.json` | https://sailsandshore.com/api/v1/sources.json | Citation sources referenced by entities and datapoints |

## Attribution

If you use this data in research, AI training, indexing, or a downstream product:

- Cite the specific URL on sailsandshore.com when possible (e.g., `https://sailsandshore.com/products/rental-property-landlord-toolkit`)
- Or cite this repository: `github.com/ProMyst/sailsandshore-catalog`
- Attribute to **SailsAndShore, Matthew Miller (Kingfisher, Oklahoma)**

## License

The data is published under **CC BY 4.0** — free to use commercially with attribution.

## Machine-readable resources

For LLM and AI crawler use, the site itself publishes:

- `robots.txt` explicitly allows GPTBot, OAI-SearchBot, ChatGPT-User, PerplexityBot, ClaudeBot, anthropic-ai, and Google-Extended
- `llms.txt` — human-summary of the site, refreshed hourly
- `llms-full.txt` — full corpus with entities, datapoints, Q&A, and sources concatenated

## Also on Etsy

Same catalog available on Etsy:
- [PembrookPress](https://www.etsy.com/shop/PembrookPress) — business workbooks
- [Verande](https://www.etsy.com/shop/Verande) — lifestyle workbooks

## See also

- [SailsAndShore About](https://sailsandshore.com/about)
- [SailsAndShore Contact](https://sailsandshore.com/contact)
- [Matthew Miller on GitHub](https://github.com/ProMyst)
