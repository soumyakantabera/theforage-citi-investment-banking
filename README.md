# Citi Investment Banking Job Simulation – Best Buy M&A Case

<p>
  <img src="https://img.shields.io/badge/Program-Citi%20Investment%20Banking-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Platform-The%20Forage-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge">
</p>

---

**Best Buy represents a compelling M&A target: a digitally transformed consumer technology leader trading at a significant discount to peers with a clear path to re-rating through membership economics and operational leverage.**

**Target Company**: Best Buy Co., Inc. (NYSE: BBY)

---

## 📋 Table of Contents

- [Repository Purpose](#repository-purpose)
- [Task-by-Task Breakdown](#task-by-task-breakdown)
  - [01\_Target\_Profile/ — M&A Target Company Profile](#01_target_profile--ma-target-company-profile)
  - [02\_IS\_Model/ — Financial Modeling Basics](#02_is_model--financial-modeling-basics)
  - [03\_Trading\_Comps/ — Spreading Comps](#03_trading_comps--spreading-comps)
  - [04\_Key\_Findings/ — Synthesize Key Findings](#04_key_findings--synthesize-key-findings)
  - [executive\_summary/](#executive_summary)
- [Why This Submission Demonstrates Strong Analyst Capability](#why-this-submission-demonstrates-strong-analyst-capability)

---

## Repository Purpose

This repository contains a **complete, self-contained, and professionally packaged** submission for a Citi-style Investment Banking M&A simulation. It replicates the full workflow an analyst would perform when evaluating a potential acquisition target — from initial company profiling through financial modeling, comparable company analysis, and strategic synthesis. All source materials and final deliverables are included for full transparency and auditability.

---

## Task-by-Task Breakdown

### 01_Target_Profile/ — M&A Target Company Profile

**Real-World Context**: In live deals, the first deliverable is almost always a clean, one-page company profile that the deal team and clients can quickly reference. It must be accurate, visually professional, and highlight the key investment highlights and risks.

**Objective**: Populate the provided skeleton template with accurate financial data, enterprise value build-up, leadership information, and recent strategic developments.

**Input Files**:
- `Target Profile Skeleton.pptx` — Pre-formatted template with placeholders for founded year, store count, revenue, EBITDA, EV bridge, leadership, and recent news.
- `Best Buy Q3FY23 Results.pdf` — Primary source document containing Q3 financials, balance sheet (for debt and cash figures), leadership mentions, and discussion of the Totaltech membership launch.

**Output**:
- `Best_Buy_Company_Profile.pptx` — Polished, board-ready slide featuring:
  - Company snapshot (founded 1966, 1,144 stores, ~$51.3B revenue, ~$3.3B EBITDA)
  - Enterprise Value build-up (~$18.47B) using the standard formula (Market Cap + Short-term Debt + Long-term Debt – Cash)
  - Full leadership team (Corie Barry – CEO, Matt Bilunas – CFO, Jason Bonfig – Chief Customer Officer, etc.)
  - Strategic news summary on the launch of Totaltech, its margin implications, and long-term value creation potential

---

### 02_IS_Model/ — Financial Modeling Basics

**Real-World Context**: Every M&A process requires a defensible financial model. Analysts build driver-based projections that the deal team can sensitize for different scenarios (base, upside, downside) and use as the foundation for valuation work (DCF, LBO, accretion/dilution).

**Objective**: Construct a clean, formula-driven 5-year income statement projection model using 2022 actuals and the prescribed operating assumptions.

**Input Files**:
- `IS Template.xlsx` — Blank income statement template with proper line-item structure and formatting conventions.
- `FY22 Annual Report.pdf` — 10-K filing providing the actual 2022 figures for Revenue ($51.8B), COGS, SG&A, and other line items.

**Output**:
- `Best_Buy_IS_Projection_Model.xlsx` — Professional, fully linked 5-year model (2022A through 2027P) incorporating:
  - 10% YoY revenue growth throughout the projection period
  - COGS margin declining linearly from 77% to 76%
  - SG&A margin declining linearly from 16.5% to 16%
  - Depreciation stepped up to 1.5% of revenue after 2022
  - Amortization held constant at $100M
  - Interest expense and tax rate held constant at 20%
  - All calculations flow left-to-right with proper cell references (no hardcoded values in projected years)

**Key Outputs**: Revenue grows to $83.3B by 2027; EBITDA margin expands to 7.0%; Net Income reaches $4.24B.

---

### 03_Trading_Comps/ — Spreading Comps

**Real-World Context**: Trading comps are the fastest way to benchmark valuation. A well-built comps table with live formulas allows the team to instantly see how the target trades relative to peers and identify re-rating potential or over/undervaluation.

**Objective**: Populate the trading comps template for Best Buy plus seven peer big-box retailers, apply consistent formatting and sign conventions, and calculate mean/median multiples.

**Input Files**:
- `Trading Comps Template (1).xlsx` — Pre-formatted blank comps sheet with columns for Price, Market Cap, Enterprise Value, Revenue, EBITDA, margins, and multiples.

**Output**:
- `Best_Buy_Trading_Comps_Analysis.xlsx` — Institutional-quality comps table featuring:
  - All multiples calculated with live Excel formulas (EV/Revenue = EV ÷ Revenue, EV/EBITDA = EV ÷ EBITDA, etc.)
  - Mean EV/Revenue: 1.18x | Median: 1.12x
  - Mean EV/EBITDA: 13.9x | Median: 11.5x
  - Best Buy trading at only 5.75x EV/EBITDA — a ~50% discount to the peer median, highlighting potential re-rating upside as Totaltech scales and margins expand

---

### 04_Key_Findings/ — Synthesize Key Findings

**Real-World Context**: After completing the quantitative work, the analyst must synthesize the qualitative story — what is the company’s strategy, where is it going, and what are the key value drivers and risks? This becomes the foundation of the investment memo and client discussions.

**Objective**: Read the full 2022 Investor Update and distill the company’s strategic path forward into a concise, stakeholder-focused summary.

**Input Files**:
- `2022 Investor Update.pdf` — 92-page investor presentation (March 2022) covering FY22 results, FY23 outlook, Totaltech strategy, omnichannel evolution, and long-term financial targets.

**Output**:
- `Key_Findings_Summary.md` — Executive-ready summary highlighting:
  - Record FY22 performance that already exceeded the original FY25 targets set in 2019
  - Raised FY25 goals ($53.5–56.5B revenue, 6.3–6.8% non-GAAP operating margin)
  - Three strategic pillars: (1) unique tech solutions provider for the connected home, (2) customer-centric ecosystem via Totaltech + omnichannel, (3) operational excellence and efficiency investments
  - Totaltech as the central growth driver (recurring revenue + higher lifetime value) despite near-term margin pressure

---

### executive_summary/

Contains the comprehensive **M&A Investment Thesis** including:
- Valuation context (Best Buy at ~5.8x EV/EBITDA vs. peers at 11.5x median)
- Value drivers table (Totaltech, omnichannel, Best Buy Ads, store optimization, category expansion)
- Key risks and mitigants
- Recommended next steps for the deal team (LBO modeling, synergy identification, Totaltech unit economics deep-dive)

---

## Why This Submission Demonstrates Strong Analyst Capability

- **End-to-end workflow**: Profile → Model → Comps → Strategic Synthesis — exactly what a junior banker produces on a live deal
- **Technical excellence**: All financial models are formula-driven, dynamic, and free of hardcoded values in projected periods
- **Professional standards**: Consistent formatting, proper sign conventions, clean audit trail from input to output
- **Investment judgment**: Clear articulation of why Best Buy is undervalued and what the key catalysts are for value creation
- **Self-contained & reproducible**: Every source document and every deliverable is included

**Total Size**: ~23 MB (full source PDFs included for complete auditability and transparency)

---

*This repository reflects the quality of work expected from a top-tier investment banking analyst and is suitable for submission to bulge-bracket recruiting portals or GitHub portfolios.*
