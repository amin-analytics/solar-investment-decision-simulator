# 200 MW Utility-Scale Solar Investment Decision Simulator
[![Live Dashboard](https://img.shields.io/badge/Live-Dashboard-blue)](https://bdcerts.com/projects/solar-investment)

## Project Overview
Investment-grade Power BI model simulating a 200 MW utility-scale solar project under Dutch market assumptions (2026 Outlook).

This project demonstrates portfolio-level decision analytics aligned with infrastructure investment committee practices.
## 🔗 Live Interactive Dashboard

👉 **View Live Power BI Report (Web Version)**  
[https://bdcerts.com/projects/solar-investment](https://bdcerts.com/projects/solar-investment)

## Project Objectives
Build a transparent screening model that answers:
- Is the project investable?
- What drives valuation?
- Where is risk concentrated?
- How sensitive is NPV to pricing, CAPEX, and discount assumptions?

The simulator is intentionally conservative and designed for auditability rather than financial close precision.

## Model Design Principles
- Unlevered project economics
- 30-year operating life
- Full CAPEX in Year 0
- PPA-backed revenue with merchant tail
- Explicit degradation and availability modeling
- Dutch corporate tax logic
- Transparent sensitivity framework
- No black-box calculations

This structure mirrors infrastructure investment committee screening models.

## Key Features
- Year-by-year energy production modeling
- Contracted + merchant revenue structure
- Fixed and variable OPEX framework
- EBITDA → NOPAT → FCFF cash flow chain
- NPV / IRR / Payback metrics
- Tornado sensitivity analysis
- Interactive stress testing
- Assumption transparency pages
- Audit-friendly layout

## Assumption Framework
Synthetic but NL-comparable assumptions are used:
- Capacity factor aligned with Dutch solar benchmarks
- Conservative degradation
- Screening-level EPC pricing
- Merchant tail valuation
- Flat nominal OPEX for conservatism

No subsidies or financing structure are included to isolate asset economics.

## Dashboard Structure
1. Executive Investment Summary
2. Project Overview & Assumptions
3. Investment Decision Metrics
4. Energy Model
5. Revenue Structure
6. Cost Structure
7. Cash Flow & Profitability
8. Investment Sensitivity & Risk
9. Dynamic Scenario Stress Testing
10. Transparency Appendix (Accounting detail)

Each page is structured to mimic an internal IC presentation deck.

## Modeling Notes
Synthetic but NL-comparable assumptions are used:
- Sensitivity logic is isolated from construction cash flow to prevent artificial Year 0 distortion.
- Adjusted CAPEX only applies to scenario runs and does not corrupt base case accounting.
- This safeguard ensures realistic tornado behavior.

## Known Limitations (Intentional)
- No debt financing layer
- No subsidy modeling
- No curtailment forecasting
- No merchant price stochastic modeling
- Screening model, not financial close model

These are design choices to preserve clarity.

## Purpose
This project is a portfolio demonstration of investment analytics capability, not a live investment recommendation.

## Screenshots
Screenshots of all pages are uploaded together as a PDF file for convenience. 

## 🔁 Direct Power BI Access (Optional)

If you prefer to open the report directly in Power BI Service:
https://app.powerbi.com/view?r=eyJrIjoiYWRmZGJhNzYtMjkyNi00NTM1LWE3M2EtNWQ5MzA0ZjdiZDAwIiwidCI6IjJhMGRlOTE5LTRmNzUtNDhiYy1hMDJhLWUwMzRhMmM1MDgyMSIsImMiOjh9&pageName=cf92beb5aba64e022e3e

## PBIX File Access
The Power BI (.pbix) file is available upon request for hiring managers and reviewers.

## Author
Energy & Infrastructure Investment Analytics
Portfolio project aligned with EU renewable investment screening practices.
Amin  
Helsinki, Finland  
📧 amin@bdcerts.com
