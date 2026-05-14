# Membra Investor Room

**Membra Investor Room is the buyer, investor, and diligence data-room namespace for MEMBRA Labs and the MEMBRA Proof Network.**

It packages the company narrative, product thesis, valuation posture, demo script, roadmap, screenshots, claims registry, and handoff material into a buyer-ready room.

## Company Context

- Company: **MEMBRA Labs**
- Flagship product: **MEMBRA Proof Network**
- Module: **Membra Investor Room**
- Category: investor room, buyer package, diligence room, acquisition handoff, sales enablement

## One-Line Thesis

Membra Investor Room turns the repo portfolio into a coherent company package that a buyer, investor, or venture studio can understand and diligence.

## Product Role

This repo should contain or reference:

- executive summary
- pitch narrative
- valuation map
- demo script
- pricing model
- product roadmap
- screenshots
- traction model
- claims registry
- risk memo
- repository map
- buyer handoff checklist
- deployment guide
- diligence checklist

## Required Buyer Narrative

Use this positioning:

> MEMBRA Labs builds proof infrastructure for physical-world monetization. Its first product, MEMBRA Proof Network, turns physical surfaces and local assets into verified QR/NFC media inventory with proof review, scan attribution, campaign reporting, and payout eligibility.

Do not present MEMBRA as a revenue-generating operating company unless revenue, customers, and transactions are documented.

## Data-Room Structure

Recommended structure:

```text
Membra_Investor_Room/
  00_Executive_Summary.md
  01_Product_Overview.md
  02_Demo_Script.md
  03_Architecture_Map.md
  04_Repository_Map.md
  05_Valuation_Memo.md
  06_Risk_and_Compliance_Memo.md
  07_Roadmap.md
  08_Screenshots/
  09_Claims_Registry.md
  10_Buyer_Handoff_Checklist.md
```

## Diligence Checklist

A serious buyer should be able to answer:

- What is the company?
- What is the first product?
- Which repo is the source of truth?
- Which repos are runnable today?
- Which repos are module stubs?
- What is the demo flow?
- What is missing before operating-company status?
- What are the legal/compliance risks?
- What are the value unlocks?
- What exactly transfers in a sale?

## Integration Points

| Repo | Investor Room Relationship |
|---|---|
| `overandor/membra` | company hub, productization docs, appraisal, doctrine |
| `overandor/Membra_ads` | first commercial backend wedge |
| `overandor/membra-qr-gateway` | buyer-visible dashboard and screenshots |
| `overandor/Membra_kpi` | KPI/reporting demo and investor metrics |
| `overandor/Membra_demo_data` | seed data for demo script and screenshots |
| `overandor/Membra_wallet` | payment-boundary and non-custodial safety story |
| `overandor/Membra_proofbook` | verification/audit story |

## Appraisal Posture

MEMBRA should be appraised as:

- prototype/IP package today
- demo-ready company package after deployment and screenshots
- pilot-stage company only after real proof events and users
- operating company only after customers/revenue/retention are documented

## Safety Rules

- no unsupported revenue claims
- no guaranteed income claims
- no guaranteed advertiser performance claims
- no implied custody claims
- no real-funds contract claims without audit/legal review
- separate demo data from live data
- map claims to evidence

## Current Stage

Investor/data-room namespace. Highest priority is to mirror the company package docs from `overandor/membra/docs/company/` and add screenshots/demo artifacts once the product demo is connected.