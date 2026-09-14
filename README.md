# API Product Unit Economics Model

An Excel-based product decision model for understanding the economics of API-dependent products and features.

This repository is the companion artifact for the article **[The API Bill Is a Product & Finance Decision](https://tetramesa.com/the-api-bill-is-a-product-finance-decision/)**.

## Download the model

**[Download API_Product_Unit_Economics_Model_v2.xlsx](./API_Product_Unit_Economics_Model_v2.xlsx)**

Version 2.0 · August 2026  
All sample numbers in the workbook are fictional.

## What the model is for

A cheap API call is not necessarily a cheap customer outcome. One product action may trigger multiple vendors, retries, failed work, background activity, or other paid consumption.

This workbook helps product leaders connect that technical usage to questions such as:

- What does one started customer action cost?
- What does one successful customer outcome cost after failed work is included?
- How does API usage affect product gross margin?
- What happens under growth, heavy-user behavior, vendor price increases, or efficiency improvements?
- Can a fixed-price customer become unprofitable as usage rises?
- If the product also sells an API, do downstream prices cover upstream and infrastructure costs?

It is a **management model**, not a GAAP financial statement or a replacement for Finance's formal models.

## Workbook contents

The workbook currently includes:

| Sheet | Purpose |
| --- | --- |
| `ReadMe` | Instructions, color key, and workbook map |
| `Dashboard` | Headline unit-economics, margin, ROI, and decision KPIs |
| `Assumptions` | Product volumes, revenue/value assumptions, operating costs, and scenario inputs |
| `Catalog` | Vendor billable units, variable pricing, fixed fees, free allowances, and attribution inputs |
| `Workflow` | Success/failure paths, execution frequency, retries, caching, and billable units |
| `UnitEconomics` | Cost per action, successful outcome, and customer, plus value/ROI views |
| `PLBridge` | Product-level management P&L bridge |
| `Scenarios` | Base, growth, heavy-user, vendor-shock, and efficiency cases |
| `Crossover` | Negative-margin crossover for a fixed subscription with usage-driven cost |
| `Seller` | Economics for products that also sell an API |
| `Engine` | Calculation layer supporting the model |
| `Sources` | Frameworks and references used to shape the model |
| `Consumption Only` | Guidance for teams that consume APIs but do not sell one |

## How to use it

1. Start on `ReadMe`.
2. Replace the yellow input cells in `Assumptions`, `Catalog`, and `Workflow` with your own assumptions.
3. Return to `Dashboard` and `UnitEconomics` to review cost per started action, cost per successful outcome, product margin, and ROI.
4. Use `Scenarios` to test scale, heavier usage, vendor pricing shocks, and efficiency improvements.
5. Use `Crossover` when customer revenue is relatively fixed but delivery cost rises with usage.
6. Use `Seller` only if your product also sells an API or metered service downstream.

## Important caveats

This is intentionally a learning and product-management model. Real vendor contracts and production economics can be substantially more complicated.

The workbook does **not** attempt to fully model every possible pricing structure, including complex usage tiers, negotiated volume discounts, committed spend, overage schedules, or every variation in token/input/output pricing.

Finance should determine official accounting classifications and allocations. Product, Engineering, Finance, and FinOps may all need to contribute inputs before this kind of model is suitable for an actual business decision.

## Core idea

The important question is not whether an API call costs fractions of a cent.

The useful question is:

> What does it cost to create a successful customer outcome, what is that outcome worth, and do the economics get better or worse when the product wins?

## Article

Read the full companion article:

**[The API Bill Is a Product & Finance Decision](https://tetramesa.com/the-api-bill-is-a-product-finance-decision/)**

## Author

Scott Germaise
