# Available .PLACE One-Word Domains (11,409)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-11%2C409%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .place one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **11,409 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 11,409 domains · **Median ask:** $27.35 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-06  
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

- `place.csv` — public CSV extract (1,000 rows)
- `place.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/place-oneword-domains/main/place.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain            | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                 |
| ----------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ------------------------- |
| inspiration.place | available | $25.99    | —             | 88             | 30     | 11     | name.com                  |
| game.place        | resell    | —         | —             | 88             | 50     | 4      | Porkbun LLC               |
| payments.place    | premium   | $14       | $28           | 58             | 33     | 8      | namecheap                 |
| blocks.place      | available | $25.99    | —             | 53             | 29     | 6      | name.com                  |
| human.place       | resell    | —         | —             | 74             | 49     | 5      | Porkbun LLC               |
| rewards.place     | premium   | $46.20    | $92.40        | 62             | 30     | 7      | namecheap                 |
| whats.place       | available | $22.49    | $22.49        | 58             | 24     | 5      | namesilo                  |
| coffee.place      | resell    | —         | —             | 76             | 43     | 6      | Porkbun LLC               |
| videos.place      | premium   | $14       | $28           | 52             | 30     | 6      | namecheap                 |
| holidays.place    | available | $22.49    | $22.49        | 78             | 23     | 8      | namesilo                  |
| mobile.place      | resell    | —         | —             | 62             | 43     | 6      | Porkbun LLC               |
| bees.place        | premium   | $14       | $28           | 54             | 27     | 4      | namecheap                 |
| veterans.place    | available | $25.99    | —             | 56             | 23     | 8      | name.com                  |
| watch.place       | resell    | —         | —             | 76             | 36     | 5      | Porkbun LLC               |
| traders.place     | premium   | $14       | $28           | 60             | 26     | 7      | namecheap                 |
| webshop.place     | available | $25.99    | —             | 76             | 22     | 8      | name.com                  |
| quotes.place      | resell    | —         | —             | 58             | 29     | 6      | Go Australia Domains, LLC |
| schools.place     | premium   | $14       | $28           | 72             | 24     | 7      | namecheap                 |
| guns.place        | available | $25.99    | —             | 68             | 22     | 4      | name.com                  |
| spicy.place       | resell    | —         | —             | 81             | 28     | 5      | NameCheap, Inc.           |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 11,409 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/place?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_place_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/place?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_place_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_place_oneword_domains&utm_content=related_pricing)

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

This set is entirely made up of one-word domains on the .place extension. The names range from direct terms like consult.place and express.place to broader or more unusual words like renegade.place and knowledgeable.place. When comparing these domains, focus on whether the word makes sense with “place” as a suffix, whether it sounds natural when spoken aloud, and whether the full name is easy to remember. The median ask is 27.35, which keeps entry pricing accessible, but low price alone does not make a name strong. Favor words with clear commercial meaning, clean spelling, and obvious use cases.

- Prefer words that read naturally with .place
- Short, clear spelling usually improves recall
- Check if the word feels commercial or generic
- Low ask helps, but fit matters more than price

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .PLACE One-Word Domains*. Version 2026-05-06. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .PLACE page](https://unique.domains/domains/tld/place?utm_source=github&utm_medium=referral&utm_campaign=repo_place_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_place_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_place_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_place_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
