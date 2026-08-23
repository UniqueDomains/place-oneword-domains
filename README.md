# Available .PLACE One-Word Domains (17,791)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-17%2C791%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .place one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **17,791 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 17,791 domains · **Median ask:** $24.17 · **High-demand under $2,500:** 3

**Last updated:** 2026-08-23
**Canonical page:** `https://unique.domains/domains/tld/place`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/place?utm_source=github&utm_medium=referral&utm_campaign=repo_place_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./place.csv">CSV</a> / <a href="./place.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_place_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_place_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .PLACE search](https://unique.domains/domains/tld/place?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_place_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .PLACE search](https://unique.domains/domains/tld/place?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_place_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_place_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .PLACE one-word domain catalog.

### Files

- `place.csv`, public CSV extract (1,000 rows)
- `place.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/place-oneword-domains/main/place.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain       | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                  |
| ------------ | --------- | --------- | ------------- | -------------- | ------ | ------ | -------------------------- |
| smooth.place | available | $22.49    | $22.49        | high           | low    | 6      | namesilo                   |
| aim.place    | available | $22.49    | $22.49        | high           | low    | 3      | namesilo                   |
| old.place    | resell    | —         | —             | high           | low    | 3      | Porkbun LLC                |
| aaa.place    | premium   | $26       | $26           | high           | medium | 3      | namecheap                  |
| are.place    | available | $22.49    | $22.49        | high           | low    | 3      | namesilo                   |
| tax.place    | resell    | —         | —             | high           | medium | 3      | Sav.com, LLC               |
| btw.place    | premium   | $46.20    | $92.40        | high           | low    | 3      | namecheap                  |
| BJP.place    | available | $25.99    | —             | medium         | low    | 3      | name.com                   |
| date.place   | resell    | —         | —             | high           | low    | 4      | Porkbun LLC                |
| bum.place    | premium   | $42.90    | $85.80        | low            | low    | 3      | namecheap                  |
| bob.place    | available | $22.49    | $22.49        | high           | medium | 3      | namesilo                   |
| press.place  | resell    | —         | —             | medium         | low    | 5      | Porkbun LLC                |
| dye.place    | premium   | $23.10    | $46.20        | medium         | low    | 3      | namecheap                  |
| clv.place    | available | $22.49    | $22.49        | medium         | low    | 3      | namesilo                   |
| unity.place  | resell    | —         | —             | high           | low    | 5      | Sav.com, LLC               |
| ear.place    | premium   | $46.20    | $92.40        | high           | low    | 3      | namecheap                  |
| cup.place    | available | $25.99    | —             | high           | low    | 3      | name.com                   |
| center.place | resell    | —         | —             | high           | high   | 6      | Squarespace Domains II LLC |
| fee.place    | premium   | $23.10    | $46.20        | high           | low    | 3      | namecheap                  |
| gal.place    | available | $22.49    | $22.49        | medium         | low    | 3      | namesilo                   |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 17,791 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 3 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/place?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_place_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/place?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_place_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_place_oneword_domains&utm_content=related_pricing)

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

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This list covers 11,411 one-word .place domain names, including compound picks like whitewater.place, solarenergy.place, and destination.place. The .place extension suits location, lifestyle, and community-themed brands, with a median ask of $25 across the set. Pricing stays accessible, making it easy to compare options and secure a domain that fits your budget before renewal costs apply.

- 11,411 one-word .place domains available in this set
- Median ask of $25 keeps entry cost low for most buyers
- Compound-word names fit location and lifestyle branding
- Compare pricing and renewal before locking in a pick

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .PLACE One-Word Domains*. Version 2026-08-23. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .PLACE page](https://unique.domains/domains/tld/place?utm_source=github&utm_medium=referral&utm_campaign=repo_place_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_place_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_place_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_place_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
