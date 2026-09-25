# Available .SITE One-Word Domains (83,403)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-83%2C403%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .site one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **83,403 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 83,403 domains · **Median ask:** $170.23 · **High-demand under $2,500:** 240

**Last updated:** 2026-09-25
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

- `site.csv`, public CSV extract (1,000 rows)
- `site.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/site-oneword-domains/main/site.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain         | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                 |
| -------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ----------------------------------------- |
| rimy.site      | available | $0.98     | $31.98        | medium         | low    | 4      | namecheap                                 |
| asat.site      | resell    | —         | —             | high           | low    | 4      | GMO Internet Group, Inc. d/b/a Onamae.com |
| aak.site       | premium   | $78.12    | $312.50       | high           | low    | 3      | name.com                                  |
| xciv.site      | available | $0.98     | $31.98        | high           | low    | 4      | namecheap                                 |
| errand.site    | resell    | —         | —             | high           | high   | 6      | GMO Internet Group, Inc. d/b/a Onamae.com |
| ant.site       | premium   | $1,562.50 | —             | high           | medium | 3      | name.com                                  |
| acned.site     | available | $0.98     | $31.98        | medium         | low    | 5      | namecheap                                 |
| bitcoin.site   | resell    | —         | —             | high           | high   | 7      | Namecheap                                 |
| diy.site       | premium   | $1,625    | $6,500        | high           | low    | 3      | namecheap                                 |
| algid.site     | available | $0.98     | $31.98        | medium         | low    | 5      | namecheap                                 |
| burrito.site   | resell    | —         | —             | high           | high   | 7      | HOSTINGER operations, UAB                 |
| gun.site       | premium   | $312.50   | —             | high           | low    | 3      | name.com                                  |
| gaily.site     | available | $0.98     | $31.98        | high           | low    | 5      | namecheap                                 |
| apparent.site  | resell    | —         | —             | high           | low    | 8      | GoDaddy.com, LLC                          |
| lao.site       | premium   | $156.25   | $625          | high           | low    | 3      | name.com                                  |
| girth.site     | available | $2.99     | $38.50        | high           | low    | 5      | namesilo                                  |
| passcode.site  | resell    | —         | —             | high           | low    | 8      | Atak Domain Bilgi Teknolojileri A.Ş.      |
| airy.site      | premium   | $156.25   | $625          | high           | low    | 4      | name.com                                  |
| ilxxx.site     | available | $0.98     | $31.98        | medium         | low    | 5      | namecheap                                 |
| footprint.site | resell    | —         | —             | high           | high   | 9      | PDR Ltd. d/b/a PublicDomainRegistry.com   |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 83,403 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 240 high-demand names under $2,500         |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/site?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_site_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/site?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_site_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_site_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain`, Fully qualified domain name.
- `status`, Current acquisition state for the domain in the public extract.
- `purchase_price`, Visible purchase price when available.
- `renewal_price`, Visible renewal price when available.
- `attractiveness`, Public composite naming band used as a decision-support signal.
- `demand`, Public buyer-pressure band when available.
- `length`, Character count without the TLD.
- `registrar`, Registrar name when known.
- `created_at`, Creation timestamp when known.
- `expires_at`, Expiry timestamp when known.
- `status_verified_at`, When status was last established against the registry. Null means never checked.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This set of one-word .site domain names covers a wide range of styles, from playful compounds like coffeeman.site and smileyface.site to punchy single-word picks like embrace.site and develop.site. With a median ask of $240 across 72,834 domains, pricing stays approachable for most buyers, though renewal cost and use-case fit are worth checking before purchase. The .site TLD suits startups, personal brands, and niche projects that don't require a .com.

- 72,834 one-word .site domain names in this selection
- Median ask: $240 across the full list
- Includes brandable picks like astound.site and embrace.site
- Updated daily to reflect newly listed .site domains

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The snapshot date above is when this file was written, not when each row was checked. Read `status_verified_at` for that: a name whose status was last established months ago is exported with its real date rather than the snapshot's.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .SITE One-Word Domains*. Version 2026-09-25. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .SITE page](https://unique.domains/domains/tld/site?utm_source=github&utm_medium=referral&utm_campaign=repo_site_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_site_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_site_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_site_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `kai@unique.domains`
