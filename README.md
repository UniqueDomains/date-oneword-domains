# Available .DATE One-Word Domains (12,662)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C662%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .date one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,662 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,662 domains · **Median ask:** $171.53 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-13  
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

- `date.csv` — public CSV extract (1,000 rows)
- `date.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/date-oneword-domains/main/date.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain            | status    | ask_price | renewal_price | attractiveness | demand | length | registrar |
| ----------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------- |
| Acup.date         | available | $9.98     | —             | 80             | 5      | 5      | namecheap |
| dogsit.date       | available | $9.98     | —             | 96             | 2      | 6      | namecheap |
| playin.date       | available | $9.98     | —             | 80             | 10     | 7      | namecheap |
| pierogi.date      | available | $9.98     | —             | 82             | 7      | 7      | namecheap |
| dogsick.date      | available | $9.98     | —             | 90             | 1      | 7      | namecheap |
| beawake.date      | available | $9.98     | —             | 84             | 3      | 8      | namecheap |
| fitinto.date      | available | $9.98     | —             | 84             | 2      | 8      | namecheap |
| dogstail.date     | available | $9.98     | —             | 94             | 1      | 8      | namecheap |
| getjiggy.date     | available | $9.98     | —             | 80             | 2      | 9      | namecheap |
| midautumn.date    | available | $9.98     | —             | 80             | 2      | 9      | namecheap |
| getiton.date      | available | $9.98     | —             | 84             | 3      | 9      | namecheap |
| turninto.date     | available | $9.98     | —             | 86             | 2      | 9      | namecheap |
| operacake.date    | available | $9.98     | —             | 80             | 1      | 10     | namecheap |
| deeplearning.date | available | $9.98     | —             | 74             | 23     | 13     | namecheap |
| donuts.date       | premium   | $375      | —             | 54             | 62     | 6      | name.com  |
| machines.date     | available | $9.98     | —             | 56             | 22     | 8      | namecheap |
| jobs.date         | premium   | $375      | —             | 79             | 42     | 4      | name.com  |
| managed.date      | available | $9.98     | —             | 58             | 20     | 7      | namecheap |
| stories.date      | premium   | $375      | —             | 58             | 36     | 7      | name.com  |
| mobiles.date      | available | $5.25     | $6.25         | 62             | 19     | 7      | namesilo  |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,662 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/date?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_date_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/date?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_date_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_date_oneword_domains&utm_content=related_pricing)

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

This selection is entirely made up of .date domains. The set includes direct keyword names, conversational phrases, and unusual word combinations, with examples such as Acup.date, LGBTQ.date, dogsit.date, getlife.date, and presents.date. For founders, the best options are usually the names that read naturally, communicate a use case fast, and remain easy to say and recall. For investors, the key question is whether a term has obvious end-user relevance at the right ask. With a median ask of $172, price is accessible, but .date is a niche extension, so renewal cost, buyer fit, and resale depth matter more than raw volume.

- All results use the .date extension
- Median ask across this set is $172
- Prioritize natural phrase fit over novelty
- Check renewal cost before judging the ask

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .DATE One-Word Domains*. Version 2026-05-13. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .DATE page](https://unique.domains/domains/tld/date?utm_source=github&utm_medium=referral&utm_campaign=repo_date_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_date_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_date_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_date_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
