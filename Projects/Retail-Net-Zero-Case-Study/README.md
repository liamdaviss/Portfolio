# Retail Net Zero Case Study — Solar + PPA Feasibility

This repository documents a case study completed for a **CORE Markets** internship assessment. The client is a multi-site retailer (350 locations across NSW, VIC, QLD) seeking a cost-optimal strategy to reach **50% or 100% renewable electricity** from **1 July 2025 to 31 December 2030**, combining on-site solar PV and a renewable **Power Purchase Agreement (PPA)**. The brief also asks for annual carbon abatement (tCO₂-e) and its equivalent value in **ACCUs**.

---

## Repository contents

- `CORE_Markets_Intern_Analyst_Case_Study_2025.pdf` — official task brief (problem, key considerations, and state load profiles).
- `CORE_Markets_Intern_Analyst_Case_Study_Data_2025.xlsx` — raw dataset as supplied with the brief.  
- `Retail-Net-Zero-Case-Study.pptx` — my final presentation deliverable summarising analysis and recommendations.
- `README.md` — this file.

---

## Problem framing (from the brief)

- **Sites**: 160 NSW, 80 QLD, remainder VIC (total 350).
- **Objective**: Choose a cost-optimal mix of on-site PV + PPA to achieve **50% or 100% renewable**.
- **Deliverables**: Costs under each strategy, PV feasibility across states, and annual **tCO₂-e** savings with **ACCU** valuation.

**Load profiles (per site archetype, weekday):**
- **NSW** — Peak 8:00–21:00; Peak demand 100 kW; Off-peak 40 kW.
- **QLD** — Peak 10:00–23:00; Peak demand 90 kW; Off-peak 35 kW.
- **VIC** — Peak 9:00–22:00; Peak demand 120 kW; Off-peak 80 kW.

---

## Approach & methodology

1. **On-site PV prefeasibility**  
   - Screened by state load profiles, solar resource assumptions, and site practicality factors (roof area/structure, daylight/obstructions, connection and permitting).  
   - Used a conservative CAPEX estimate and long-life amortisation to compare **$ saved per additional kW** of PV.

2. **Economic optimisation**  
   - Evaluated marginal savings vs. marginal cost to find the **economically optimal PV size per state** (separately for 50% and 100% renewable pathways).

3. **PPA structuring**  
   - Sized the **nominated renewable percentage** in the PPA to complement on-site PV, then compared **retailers** for total supply cost under each pathway.

4. **Carbon accounting**  
   - Converted PV generation to **tCO₂-e avoided** and valued reductions at the provided **ACCU** price point.

> The brief’s “Key Considerations” guided the structure above (PPA renewables %, PV feasibility factors, strategy to 50%/100%).

---

## Key results (per final deck)

### Economically optimal PV sizing
- **NSW** — **185 kW per site** (both 50% & 100% pathways).
- **QLD** — **215 kW** (100% pathway) or **162 kW** (50% pathway) per site.
- **VIC** — Longer payback within PPA term, but **up to 256 kW per site** viable on a 30-year amortised basis. 

### Carbon & PPA outcomes
- **100% renewable** pathway: ~**174,819 tCO₂-e/year avoided** (≈111,118 tCO₂-e/year from on-site PV); **Retailer B** lowest cost; blended energy ~**44.53% PV / 55.47% renewable via retailer**.
- **50% renewable** pathway: ~**87,409 tCO₂-e/year avoided** (≈103,955 tCO₂-e/year from on-site PV); **Retailer B** lowest cost; mix ~**43.49% PV / 6.51% renewable via retailer / 50% non-renewable**. 
- Illustrative ACCU valuation in the presentation used **$35.75/tonne**.

---

## Assumptions (as used in the deck)

- **PV CAPEX**: representative **$/kW** (conservative), amortised over **30 years** for economic viability checks.  
- **Demand**: steady across the PPA horizon for retailer cost comparison.  
- **Scope**: storage value not included in cost totals (noted separately in deck).

---

## How to navigate this repo

1. Read the **brief** for scope, objectives, and load assumptions.
2. Inspect the **raw dataset** that underpins the analysis.  
3. Open the **presentation** (`CORE Markets Case Study.pptx`) for the results, charts, and recommendations. 

---

## What this showcases

- **Energy market analysis** — PV feasibility by state load/solar context; PPA structuring.  
- **Financial modelling** — marginal analysis, long-life amortisation, retailer cost comparison.  
- **Carbon accounting** — tCO₂-e abatement + ACCU valuation.  
- **Executive communication** — distilling technical modelling into client-facing recommendations.

---
