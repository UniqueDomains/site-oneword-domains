# Available .SITE One-Word Domains (5,622,006)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-10%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-5%2C622%2C006%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .site one-word domains from Unique Domains.

> **Important:** this repository is a **public 10,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **5,622,006 domains** on the canonical page below.

**Public extract:** 10,000 rows · **Live catalog:** 5,622,006 domains

**Last updated:** 2026-04-10  
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

- `site.csv` — public CSV extract (10,000 rows)
- `site.json` — public JSON extract (10,000 rows)
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

| domain             | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                                       |
| ------------------ | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------------------------------------------------------- |
| sundries.site      | available | $2.99     | $46.99        | 68             | 92     | 8      | name.com                                                        |
| footprint.site     | resell    | —         | —             | 64             | 96     | 9      | PDR Ltd. d/b/a PublicDomainRegistry.com                         |
| maps.site          | premium   | $1,562.50 | $6,250        | 56             | 96     | 4      | name.com                                                        |
| glazing.site       | available | $2.99     | $46.99        | 62             | 88     | 7      | name.com                                                        |
| burrito.site       | resell    | —         | —             | 90             | 92     | 7      | HOSTINGER operations, UAB                                       |
| product.site       | premium   | $781.25   | $3,125        | 84             | 92     | 7      | name.com                                                        |
| geriatrics.site    | available | $2.99     | $46.99        | 56             | 80     | 10     | name.com                                                        |
| Bitcoin.site       | resell    | —         | —             | 74             | 92     | 7      | Namecheap                                                       |
| tops.site          | premium   | $156.25   | $625          | —              | 92     | 4      | name.com                                                        |
| apiculture.site    | available | $2.99     | $46.99        | 56             | 80     | 10     | name.com                                                        |
| wavelength.site    | resell    | —         | —             | 54             | 92     | 10     | Go Daddy, LLC                                                   |
| sage.site          | premium   | $78.12    | $312.50       | 132            | 88     | 4      | name.com                                                        |
| AandE.site         | available | $24.98    | —             | 50             | 80     | 7      | namecheap                                                       |
| topten.site        | resell    | —         | —             | 72             | 88     | 7      | Go Daddy, LLC                                                   |
| supply.site        | premium   | $312.50   | $1,250        | 100            | 88     | 6      | name.com                                                        |
| overalls.site      | available | $2.99     | $46.99        | —              | 76     | 8      | name.com                                                        |
| plantlife.site     | resell    | —         | —             | 62             | 88     | 10     | Namecheap                                                       |
| debit.site         | premium   | $156.25   | $625          | 96             | 88     | 5      | name.com                                                        |
| railtransport.site | available | $2.99     | $46.99        | —              | 76     | 14     | name.com                                                        |
| soundboard.site    | resell    | —         | —             | 60             | 88     | 10     | VIRTUA DRUG Kutatási Szolgáltató Korlátolt Felelősségű Társaság |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract           | Unique Domains                                   |
| ------------------------ | ------------------------------------------------ |
| 10,000-row public sample | 5,622,006 live domains                           |
| Static CSV / JSON        | live search and daily refresh                    |
| Basic exported fields    | deeper price, demand, risk, and workflow context |
| No persistence           | Radar, saved search, and alerts                  |
| No founder workflow      | Project, shortlist, and next-step workflow       |

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

This repository follows the exact public search represented by the canonical page above.

- This repository is a public extract, not the full live catalog.
- Counts, prices, and statuses can change over time.
- Scores are decision-support signals, not guarantees of resale value.
- Trademark, SEO, and risk signals should be treated as screening inputs, not legal or specialist advice.
- Unique Domains contains deeper filters, monitoring, and decision workflows than this public extract.

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .SITE One-Word Domains*. Version 2026-04-10. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .SITE page](https://unique.domains/domains/tld/site?utm_source=github&utm_medium=referral&utm_campaign=repo_site_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_site_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_site_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_site_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
