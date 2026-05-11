# Available .SERVICES One-Word Domains (10,397)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-10%2C397%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .services one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **10,397 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 10,397 domains · **Median ask:** $26.44 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-11  
**Canonical page:** `https://unique.domains/domains/tld/services`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/services?utm_source=github&utm_medium=referral&utm_campaign=repo_services_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./services.csv">CSV</a> / <a href="./services.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_services_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_services_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .SERVICES search](https://unique.domains/domains/tld/services?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_services_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .SERVICES search](https://unique.domains/domains/tld/services?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_services_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_services_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .SERVICES one-word domain catalog.

### Files

- `services.csv` — public CSV extract (1,000 rows)
- `services.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/services-oneword-domains/main/services.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain             | status    | ask_price | renewal_price | attractiveness | demand | length | registrar        |
| ------------------ | --------- | --------- | ------------- | -------------- | ------ | ------ | ---------------- |
| stories.services   | available | $15.99    | —             | 58             | 36     | 7      | name.com         |
| checkout.services  | resell    | —         | —             | 72             | 78     | 9      | GoDaddy.com, LLC |
| events.services    | premium   | $560      | $1,120        | 68             | 37     | 6      | namecheap        |
| spectra.services   | available | $15.99    | —             | 62             | 34     | 7      | name.com         |
| Your.services      | resell    | —         | —             | 68             | 45     | 4      | Sav.com, LLC     |
| etc.services       | premium   | $46.20    | $92.40        | 58             | 34     | 3      | namecheap        |
| trends.services    | available | $15.99    | —             | 60             | 32     | 6      | name.com         |
| Phil.services      | resell    | —         | —             | 78             | 41     | 4      | Spaceship, Inc.  |
| partners.services  | premium   | $140      | $280          | 61             | 32     | 8      | namecheap        |
| whats.services     | available | $15.99    | —             | 58             | 24     | 5      | name.com         |
| coins.services     | resell    | —         | —             | 56             | 41     | 5      | Dynadot Inc      |
| loans.services     | premium   | $280      | $560          | 58             | 24     | 5      | namecheap        |
| rekt.services      | available | $15.99    | —             | 40             | 24     | 4      | name.com         |
| premium.services   | resell    | —         | —             | 85             | 39     | 7      | Porkbun LLC      |
| boats.services     | premium   | $140      | $280          | 52             | 24     | 5      | namecheap        |
| resources.services | available | $15.99    | —             | 58             | 21     | 9      | name.com         |
| label.services     | resell    | —         | —             | 70             | 39     | 5      | GoDaddy.com, LLC |
| flights.services   | premium   | $140      | $280          | 61             | 22     | 7      | namecheap        |
| blogs.services     | available | $15.99    | —             | 52             | 21     | 5      | name.com         |
| tree.services      | resell    | —         | —             | 74             | 38     | 4      | Porkbun LLC      |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 10,397 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/services?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_services_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/services?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_services_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_services_oneword_domains&utm_content=related_pricing)

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

This selection is entirely made up of .services domains. The set ranges from direct dictionary terms such as cat.services, cake.services, and hybrid.services to more specific or conceptual names like antiracist.services, subsidiary.services, and cherryontop.services. When comparing these domains, focus on whether the word reads naturally before .services, whether it signals a clear service category, and whether the phrase is easy to say and remember. The median ask is 26.45, which keeps price comparison straightforward across a large set. For stronger picks, prefer names that are clear, commercially usable, and unlikely to create trademark friction.

- All domains in this selection use the .services extension
- Median ask across the set is 26.45
- Best fits read clearly before .services
- Check memorability, specificity, and trademark risk

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .SERVICES One-Word Domains*. Version 2026-05-11. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .SERVICES page](https://unique.domains/domains/tld/services?utm_source=github&utm_medium=referral&utm_campaign=repo_services_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_services_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_services_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_services_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
