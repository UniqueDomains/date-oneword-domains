# Available .DATE One-Word Domains (15,565)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-15%2C565%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .date one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **15,565 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 15,565 domains · **Median ask:** $182.64 · **High-demand under $2,500:** 29

**Last updated:** 2026-08-14
**Canonical page:** `https://unique.domains/domains/tld/date`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/date?utm_source=github&utm_medium=referral&utm_campaign=repo_date_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./date.csv">CSV</a> / <a href="./date.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_date_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_date_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .DATE search](https://unique.domains/domains/tld/date?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_date_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .DATE search](https://unique.domains/domains/tld/date?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_date_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_date_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .DATE one-word domain catalog.

### Files

- `date.csv`, public CSV extract (1,000 rows)
- `date.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/date-oneword-domains/main/date.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain      | status    | ask_price | renewal_price | attractiveness | demand | length | registrar        |
| ----------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ---------------- |
| ahuh.date   | available | $5.25     | $6.25         | high           | low    | 4      | namesilo         |
| yesno.date  | resell    | $9.98     | —             | low            | low    | 6      | GoDaddy.com, LLC |
| aid.date    | premium   | $375      | —             | medium         | low    | 3      | name.com         |
| cxxv.date   | available | $5.25     | $6.25         | low            | low    | 4      | namesilo         |
| change.date | resell    | —         | —             | high           | medium | 6      | GoDaddy.com, LLC |
| ala.date    | premium   | $375      | —             | high           | low    | 3      | name.com         |
| grew.date   | available | $5.25     | $6.25         | high           | low    | 4      | namesilo         |
| ane.date    | premium   | $375      | $62.50        | low            | low    | 3      | name.com         |
| laws.date   | available | $5.25     | $6.25         | high           | low    | 4      | namesilo         |
| axe.date    | premium   | $116      | $29.50        | medium         | low    | 3      | namesilo         |
| lxiv.date   | available | $5.25     | $6.25         | low            | low    | 4      | namesilo         |
| bay.date    | premium   | $375      | $62.50        | low            | low    | 3      | name.com         |
| xvii.date   | available | $5.25     | $6.25         | medium         | low    | 4      | namesilo         |
| BJP.date    | premium   | $375      | —             | medium         | low    | 3      | name.com         |
| xxii.date   | available | $5.25     | $6.25         | medium         | low    | 4      | namesilo         |
| btw.date    | premium   | $375      | —             | high           | low    | 3      | name.com         |
| apian.date  | available | $5.25     | $6.25         | low            | low    | 5      | namesilo         |
| bum.date    | premium   | $375      | $62.50        | low            | low    | 3      | name.com         |
| azido.date  | available | $5.25     | $6.25         | low            | low    | 5      | namesilo         |
| CNN.date    | premium   | $375      | —             | high           | low    | 3      | name.com         |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 15,565 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 29 high-demand names under $2,500          |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/date?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_date_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/date?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_date_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_date_oneword_domains&utm_content=related_pricing)

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

This list of .date domain names centers on short, one-word titles such as BarUp.date, LightUp.date, and BonVoyage.date. With 12,662 names in this selection and a median asking price near $216, the .date extension offers a wide, affordable pool of memorable one-word options. Names range from everyday verbs and objects to distinctive brand-style words, making the TLD flexible for uses well beyond dating-related sites.

- 12,662 one-word .date domain names in this selection
- Median asking price near $216 per domain
- Brandable picks like PopUp.date and BarUp.date
- Short, single-word structure across the list

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .DATE One-Word Domains*. Version 2026-08-14. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .DATE page](https://unique.domains/domains/tld/date?utm_source=github&utm_medium=referral&utm_campaign=repo_date_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_date_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_date_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_date_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
