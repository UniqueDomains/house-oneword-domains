# Available .HOUSE One-Word Domains (11,054)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-11%2C054%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .house one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **11,054 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 11,054 domains · **Median ask:** $30.32 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-11  
**Canonical page:** `https://unique.domains/domains/tld/house`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/house?utm_source=github&utm_medium=referral&utm_campaign=repo_house_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./house.csv">CSV</a> / <a href="./house.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_house_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_house_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .HOUSE search](https://unique.domains/domains/tld/house?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_house_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .HOUSE search](https://unique.domains/domains/tld/house?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_house_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_house_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .HOUSE one-word domain catalog.

### Files

- `house.csv` — public CSV extract (1,000 rows)
- `house.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/house-oneword-domains/main/house.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain             | status    | ask_price | renewal_price | attractiveness | demand | length | registrar   |
| ------------------ | --------- | --------- | ------------- | -------------- | ------ | ------ | ----------- |
| Acup.house         | available | $55.98    | —             | 80             | 5      | 5      | namecheap   |
| Adidas.house       | available | $55.98    | —             | 88             | 23     | 6      | namecheap   |
| gearup.house       | available | $27.99    | —             | 80             | 16     | 7      | name.com    |
| playon.house       | available | $27.99    | —             | 80             | 14     | 7      | name.com    |
| makeit.house       | available | $27.99    | —             | 82             | 22     | 7      | name.com    |
| stirup.house       | available | $27.99    | —             | 82             | 3      | 7      | name.com    |
| watches.house      | available | $27.99    | —             | 84             | 19     | 7      | name.com    |
| dogsick.house      | available | $27.99    | —             | 90             | 1      | 7      | name.com    |
| presents.house     | available | $27.99    | —             | 80             | 9      | 8      | name.com    |
| shortcuts.house    | available | $27.99    | —             | 48             | 41     | 10     | name.com    |
| best.house         | resell    | —         | —             | 82             | 55     | 4      | Porkbun LLC |
| SanDiego.house     | premium   | $242      | $242          | 74             | 29     | 9      | namesilo    |
| neuroscience.house | available | $27.99    | —             | 80             | 37     | 12     | name.com    |
| shop.house         | resell    | —         | —             | 73             | 52     | 4      | Porkbun LLC |
| weddings.house     | premium   | $78.54    | $78.54        | 64             | 18     | 8      | namesilo    |
| payments.house     | available | $27.99    | —             | 58             | 33     | 8      | name.com    |
| gold.house         | resell    | —         | —             | 72             | 48     | 4      | Porkbun LLC |
| ladies.house       | premium   | $123.75   | —             | 80             | 17     | 6      | name.com    |
| letsgo.house       | available | $27.99    | —             | 57             | 31     | 7      | name.com    |
| trade.house        | resell    | —         | —             | 82             | 45     | 5      | Porkbun LLC |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 11,054 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/house?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_house_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/house?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_house_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_house_oneword_domains&utm_content=related_pricing)

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

This selection is made up of one-word domains on the .house extension. The names range from dictionary-style words to coined or less intuitive terms, with examples such as Acup.house, finals.house, jewels.house, forces.house, getup.house, and useit.house. When comparing these domains, start with how clearly the word reads, how easily it can be spoken and recalled, and whether the pairing with .house feels natural. Price discipline matters too: the median ask across this set is 30.32. Be careful with terms that may raise trademark concerns, especially names like Adidas.house or Apples.house, where brand conflict can outweigh apparent appeal.

- 11,054 one-word domains on the .house extension
- Median ask across this set is 30.32
- Strongest picks are clear, memorable, and easy to say
- Avoid names with obvious trademark conflict risk

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .HOUSE One-Word Domains*. Version 2026-05-11. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .HOUSE page](https://unique.domains/domains/tld/house?utm_source=github&utm_medium=referral&utm_campaign=repo_house_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_house_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_house_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_house_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
