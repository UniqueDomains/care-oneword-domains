# Available .CARE One-Word Domains (10,853)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-10%2C853%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .care one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **10,853 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 10,853 domains · **Median ask:** $37.23 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-17  
**Canonical page:** `https://unique.domains/domains/tld/care`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/care?utm_source=github&utm_medium=referral&utm_campaign=repo_care_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./care.csv">CSV</a> / <a href="./care.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_care_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_care_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .CARE search](https://unique.domains/domains/tld/care?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_care_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .CARE search](https://unique.domains/domains/tld/care?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_care_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_care_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .CARE one-word domain catalog.

### Files

- `care.csv` — public CSV extract (1,000 rows)
- `care.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/care-oneword-domains/main/care.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain           | status    | ask_price | renewal_price | attractiveness | demand | length | registrar        |
| ---------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ---------------- |
| matcha.care      | available | $29.99    | —             | 86             | 39     | 6      | name.com         |
| fit.care         | resell    | —         | —             | 88             | 41     | 3      | Porkbun LLC      |
| etc.care         | premium   | $140      | $280          | 58             | 34     | 3      | namecheap        |
| aliens.care      | available | $29.99    | —             | 56             | 35     | 6      | name.com         |
| coins.care       | resell    | —         | —             | 56             | 41     | 5      | Dynadot Inc      |
| SanDiego.care    | premium   | $69.30    | $138.60       | 74             | 29     | 9      | namecheap        |
| slots.care       | available | $29.99    | —             | 49             | 31     | 5      | name.com         |
| risk.care        | resell    | —         | —             | 62             | 36     | 4      | Porkbun LLC      |
| loans.care       | premium   | $280      | $560          | 58             | 24     | 5      | namecheap        |
| spaces.care      | available | $29.99    | —             | 54             | 30     | 6      | name.com         |
| twin.care        | resell    | —         | —             | 68             | 33     | 4      | Sav.com, LLC     |
| coupons.care     | premium   | $280      | $560          | 52             | 24     | 7      | namecheap        |
| Trex.care        | available | $59.98    | —             | 80             | 24     | 5      | namecheap        |
| inspiration.care | resell    | —         | —             | 88             | 30     | 11     | Spaceship, Inc.  |
| pros.care        | premium   | $69.30    | $138.60       | 53             | 23     | 4      | namecheap        |
| whats.care       | available | $29.99    | —             | 58             | 24     | 5      | name.com         |
| wakeup.care      | resell    | —         | —             | 80             | 23     | 7      | GoDaddy.com, LLC |
| signs.care       | premium   | $69.30    | $138.60       | 64             | 22     | 5      | namecheap        |
| reports.care     | available | $29.99    | —             | 58             | 24     | 7      | name.com         |
| covid.care       | resell    | —         | —             | 74             | 22     | 5      | Dynadot Inc      |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 10,853 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/care?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_care_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/care?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_care_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_care_oneword_domains&utm_content=related_pricing)

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

This set is entirely made up of .care domains, so the main variable is the word itself rather than the extension. The selection mixes directly relevant names such as critical.care with broader or less intuitive options like thirteen.care, flickering.care, and qualitative.care. That creates a wide range of use cases and quality levels. For founders, the best picks are usually the names that read clearly, feel credible, and are easy to say aloud. For investors, the key is whether the word has obvious commercial relevance inside a .care context. With a median ask of 37.24, entry cost is low enough that selection discipline matters more than headline price.

- All names in this selection use the .care extension
- Median ask is 37.24 across 10,842 domains
- Clarity varies from exact-match to abstract words
- Check trademark exposure on names like indeed.care

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .CARE One-Word Domains*. Version 2026-05-17. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .CARE page](https://unique.domains/domains/tld/care?utm_source=github&utm_medium=referral&utm_campaign=repo_care_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_care_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_care_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_care_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
