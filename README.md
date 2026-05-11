# Available .SITE One-Word Domains (72,822)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-72%2C822%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .site one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **72,822 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 72,822 domains · **Median ask:** $374.85 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-11  
**Canonical page:** `https://unique.domains/domains/tld/site`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/site?utm_source=github&utm_medium=referral&utm_campaign=repo_site_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./site.csv">CSV</a> / <a href="./site.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_site_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_site_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .SITE search](https://unique.domains/domains/tld/site?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_site_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .SITE search](https://unique.domains/domains/tld/site?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_site_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_site_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .SITE one-word domain catalog.

### Files

- `site.csv` — public CSV extract (1,000 rows)
- `site.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/site-oneword-domains/main/site.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain              | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                                 |
| ------------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------------------------------------------------- |
| flotation.site      | available | $2.99     | $46.99        | 54             | 72     | 9      | name.com                                                  |
| showup.site         | resell    | $2.99     | —             | 83             | 20     | 7      | West263 International Limited                             |
| communications.site | premium   | $781.25   | $3,125        | 54             | 84     | 14     | name.com                                                  |
| treehugger.site     | available | $2.99     | —             | 78             | 12     | 11     | name.com                                                  |
| topten.site         | resell    | —         | —             | 72             | 88     | 7      | Go Daddy, LLC                                             |
| skills.site         | premium   | $312.50   | —             | 58             | 47     | 6      | name.com                                                  |
| whitevinegar.site   | available | $2.99     | —             | 66             | 12     | 13     | name.com                                                  |
| intuitive.site      | resell    | —         | —             | 74             | 84     | 9      | GoDaddy Online Services Cayman Islands Ltd.               |
| aaron.site          | premium   | $312.50   | $1,250        | 88             | 37     | 5      | name.com                                                  |
| whitesauce.site     | available | $2.99     | —             | 72             | 11     | 11     | name.com                                                  |
| mail.site           | resell    | —         | —             | 94             | 60     | 4      | Radix Technologies Inc. SEZC / CO Services Cayman Limited |
| stories.site        | premium   | $312.50   | —             | 58             | 36     | 7      | name.com                                                  |
| clickbait.site      | available | $2.99     | —             | 66             | 11     | 9      | name.com                                                  |
| agents.site         | resell    | —         | —             | 56             | 50     | 6      | Dynadot Inc                                               |
| etc.site            | premium   | $781.25   | —             | 58             | 34     | 3      | name.com                                                  |
| tomorrows.site      | available | $2.99     | —             | 60             | 11     | 9      | name.com                                                  |
| KeyWest.site        | resell    | —         | —             | 76             | 26     | 8      | West263 International Limited                             |
| aak.site            | premium   | $78.12    | $312.50       | 68             | 32     | 3      | name.com                                                  |
| JollyRoger.site     | available | $31.98    | —             | 82             | 10     | 11     | namecheap                                                 |
| embrace.site        | resell    | —         | —             | 88             | 25     | 7      | West263 International Limited                             |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 72,822 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/site?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_site_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/site?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_site_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_site_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain` — Fully qualified domain name.
- `status` — Current acquisition state for the domain in the public extract.
- `purchase_price` — Visible purchase price when available.
- `renewal_price` — Visible renewal price when available.
- `attractiveness` — Composite naming score used as a decision-support signal.
- `demand` — Relative buyer-pressure score when available.
- `length` — Character count without the TLD.
- `registrar` — Registrar name when known.
- `created_at` — Creation timestamp when known.
- `expires_at` — Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This selection is entirely one-word .site domains. The range includes clean dictionary-style words such as calm.site, excel.site, latin.site, and fame.site, alongside more niche or playful options like pottydance.site and wiggle.site. For founders, the main question is whether the word is memorable, easy to say, and credible on a .site ending. For investors, the core test is whether the ask leaves room for resale relative to how broadly useful the word is. With a median ask of 374.85, these domains sit in a price zone where wording quality matters more than rarity alone. When comparing names, weigh clarity, renewal fit, and trademark exposure before focusing on price.

- Prefer clear, broad words over narrow or awkward phrasing
- Check if the word still feels credible on a .site ending
- Use the 374.85 median ask as a pricing reality check
- Be cautious with terms that may carry trademark risk

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .SITE One-Word Domains*. Version 2026-05-11. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .SITE page](https://unique.domains/domains/tld/site?utm_source=github&utm_medium=referral&utm_campaign=repo_site_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_site_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_site_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_site_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
