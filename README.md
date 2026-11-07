# IPO Quality Inspector

**Pre-IPO Financial Quality Scoring Platform — "Uncover the Truth Before the Market Does."**

A gamified educational platform that teaches retail investors, finance students and aspiring analysts to evaluate IPO prospectus documents (DRHP / Form S-1) with professional rigour — by playing the role of a Financial Quality Detective.

> Built as a research and product-design project at **ZeTheta Algorithms Private Limited**, Mumbai (Startup & Private Equity Intelligence · No-Code Innovation & Research Project).

---

## Why this exists

Retail investors are the most information-disadvantaged participants in an IPO. Promoters, institutions and underwriters have months of inside knowledge; a retail investor gets one prospectus and a few days to decide. The cost of that gap is real — Paytm fell ~80% within a year of listing.

The IPO Quality Inspector closes that gap with a systematic framework: instead of relying on sentiment, subscription numbers or grey-market premiums, any investor can score an IPO's financial quality directly from the filing itself.

## The Framework — Four Dimensions

Every IPO is scored out of 100 across four equally weighted dimensions. Every input comes from the prospectus and its audited financials — never from commentary about the filing.

| Dimension | What it tests |
|---|---|
| **Revenue Quality** | Sustainability, customer concentration, recurring vs one-time revenue, recognition policies, deferred revenue trends |
| **Earnings & Cash Flow Quality** | CFO/NI ratio, accruals, non-recurring items dressed as recurring, expense capitalisation, free cash flow sustainability |
| **Balance Sheet Quality** | Asset and goodwill valuation, contingent liabilities, off-balance-sheet arrangements, working capital sustainability |
| **Governance Quality** | Board independence, related-party transactions and their pricing, auditor quality, disclosure transparency |

## Backtested on six landmark IPOs

The framework was applied to six real cases, scored from the primary filings (S-1 for WeWork, DRHPs for the Indian listings) and validated afterwards against market outcomes:

| Company | Market | Score | Verdict | Outcome |
|---|---|---|---|---|
| WeWork | US (2019) | **26/100** | Strong Avoid | IPO withdrawn |
| Ola Electric | India (2024) | **32/100** | Strong Avoid | −45% vs issue price in 2 years |
| Paytm | India (2021) | **43/100** | Avoid | Fell ~80% within a year |
| Zomato | India (2021) | **67/100** | Qualified Buy | Listed at +53% premium |
| Jio Platforms | India (2026) | **69/100** | Qualified | Live case — listed Oct 2026, +21% on debut |
| Alibaba | US (2014) | **81/100** | Strong Buy | $25B IPO; strong long-term performance |

## What's in the submission

The document in this repository is the complete design blueprint:

- **Part 1 — Domain fundamentals:** the IPO process, global market landscape (India/US/UK/Singapore/China/SEA), a 40+ term glossary, stakeholder map, the four-dimension framework, regulatory comparison and a DRHP navigator's guide
- **Part 2 — Case studies:** full scored analyses of the six IPOs above, with the specific red flags behind each score
- **Part 3 — Simulation design:** Campaign Mode (six levels, fictional companies with embedded red flags), Arena Mode (competitive multiplayer) and Sandbox Mode (free play)
- **Part 4 — Scoring engine:** methodology, weight allocation and benchmark calibration
- **Part 5 — Interface:** eleven UI wireframe concepts
- **Part 6 — Business model:** revenue streams, pricing tiers and three-year projections, plus IP and competitive analysis

## Data sources

Primary filings first: SEBI and SEC EDGAR prospectuses, NSE/BSE listing data, MCA21 — supplemented by PRIME Database and public market data. Exchange prices were used only to validate scores after the fact, never as scoring inputs.

## Repository contents

| File | Description |
|---|---|
| `IPO_Quality_Inspector_Submission.docx` | The full submission document — framework, case studies, simulation design, scoring engine and business model |
| `README.md` | This file |

## Author

**Hitesh Aryan Acharya** — built during a pre-MBA investment analyst internship at ZeTheta Algorithms (Summer 2026).

## Disclaimer

This project is an educational research artefact. The scores are retrospective case-study exercises based on public filings; nothing here is investment advice or a recommendation to buy or sell any security.

