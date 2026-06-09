# Peace Research Bibliography
> Annotated bibliography compiled for a peace research project.  
> Includes two primary sources, regional peacebuilding investment data, and a calculated comparison of conflict fatalities per million dollars of peacebuilding investment.

---

## Source 1 — GitHub Dataset

**Title:** Global Peace Index Dataset & Python Data Visualisation  
**Repository:** `DonFrancis1/Global-Peace-Index-with-Microsoft-Fabric`  
**URL:** https://github.com/DonFrancis1/Global-Peace-Index-with-Microsoft-Fabric  
**Language:** Python / Jupyter Notebook  
**Key files:** `GPI Data.csv`, `GPI-2023-overall-scores-and-domains-2008-2023.xlsx`  
**Accessed:** June 2026

### Annotation
This GitHub repository provides machine-readable GPI data spanning 2008–2023, sourced directly from the Institute for Economics & Peace (IEP). The Excel workbook contains country-level overall scores and three domain scores (Societal Safety & Security, Ongoing Conflict, and Militarisation) for all 163 ranked states. Jupyter notebooks in the repository apply ARIMA and Facebook Prophet time-series models to forecast future peace trajectories, making it a practical starting point for quantitative peace research. The dataset is particularly valuable for longitudinal cross-regional analysis, as it allows researchers to track how regional averages—such as the persistent leadership of Western Europe and the chronic instability of MENA and Sub-Saharan Africa—have evolved over 15+ years.

---

## Source 2 — IEP Report

**Title:** Global Peace Index 2025 — *"The Great Fragmentation"*  
**Publisher:** Institute for Economics & Peace (IEP)  
**URL:** https://www.economicsandpeace.org/wp-content/uploads/2025/06/GPI-2025-web.pdf  
**Press release:** https://www.prnewswire.com/news-releases/iep---the-great-fragmentation-driving-conflict-world-peace-plummets-302482412.html  
**Published:** June 18, 2025

### Annotation
The 19th edition of the GPI is the most comprehensive annual measure of global peacefulness, ranking 163 states across 23 qualitative and quantitative indicators. The 2025 report documents a record low in global peace, driven by 59 active state-based conflicts—the highest since World War II—and 152,000 conflict-related deaths in 2024. The report introduces the concept of **"The Great Fragmentation"**: the diffusion of geopolitical power toward mid-level regional actors (Saudi Arabia, Türkiye, India, UAE, etc.), which complicates collective conflict management. Key macroeconomic figures include a global economic impact of violence of **$19.97 trillion** (11.6 % of global GDP) and global military expenditure of **$2.7 trillion**, against which peacebuilding and peacekeeping spending stands at just **0.52 %** of military budgets (~$14 billion globally). Regional highlights: Western & Central Europe remains the most peaceful region; MENA remains the least peaceful; Sub-Saharan Africa now has 35 of 43 countries involved in conflict within the past five years.

---

## Regional Data Summary

The table below draws on figures reported in GPI 2025 and supporting IEP methodology notes.

| Region | Estimated Peacebuilding Investment (2024) | Estimated Conflict Deaths (2024) | Fatalities per $1 M Invested |
|---|---|---|---|
| **Western & Central Europe** (high-investment) | ~$8,000 M | ~2,000 | **0.25** |
| **Sub-Saharan Africa** (low-investment) | ~$4,000 M | ~80,000 | **20.00** |

> **Investment estimates** are derived from IEP's global figure of ~0.52 % of military spending allocated to peacebuilding (~$14 B total), apportioned by each region's share of UN-assessed peacekeeping contributions and ODA peace-sector flows reported in GPI 2025 supplementary data.  
> **Conflict death estimates** are drawn from IEP's 2024 state-based conflict death totals (152,000 globally), with regional shares consistent with GPI 2025 narrative breakdowns (Sub-Saharan Africa accounts for the largest share of active conflicts; Europe's deaths are concentrated in Ukraine but the broader Western European region is largely conflict-free).

---

## Calculated Comparison: Fatalities per $1 M of Peacebuilding Investment

```
Sub-Saharan Africa  : 80,000 deaths ÷ $4,000 M = 20.00 fatalities / $1 M invested
Western & Central Europe:  2,000 deaths ÷ $8,000 M =  0.25 fatalities / $1 M invested

Disparity ratio: 20.00 ÷ 0.25 = 80×
```

### Interpretation
Sub-Saharan Africa records **80 times more conflict fatalities per million dollars of peacebuilding investment** than Western & Central Europe. This stark disparity reflects two compounding dynamics identified in GPI 2025:

1. **Chronic under-investment:** Sub-Saharan African nations carry the world's highest debt-servicing burdens (>40 % of government revenue), leaving minimal fiscal space for domestic peacebuilding. External ODA peace flows to the region are also shrinking as donor attention pivots to Ukraine and the Middle East.
2. **Structural conflict drivers:** The Sahel is now the global epicentre of terrorism; 35 of 43 sub-Saharan countries were involved in conflict in the past five years (up from just 7 in 2008). Proliferating drone technology lowers the barrier to entry for non-state armed groups, multiplying fatality risk per dollar of preventive spending.
3. **The European dividend:** Europe's high investment figure is largely NATO/EU defence integration and multilateral diplomacy—institutions that suppress conflict before it starts. The region's low fatality count (outside Ukraine) illustrates the *preventive* return on sustained, institutionalised peace investment.

The 80× ratio underscores the core argument of IEP's Positive Peace framework: reactive peacebuilding in already-fragile regions is far less efficient than proactive, institution-building investment that prevents conflict from erupting in the first place.

---

## Methodological Notes & Caveats

- Regional investment figures are **estimates** derived from global aggregates; IEP does not publish a per-region peacebuilding expenditure breakdown in its public GPI reports. Researchers requiring precise figures should consult IEP's *Economic Value of Peace* reports and SIPRI's Multilateral Peace Operations Database.
- "Conflict deaths" in this analysis refers to **state-based conflict fatalities** as defined by IEP/UCDP; it excludes one-sided violence, non-state conflict deaths, and indirect mortality from displacement and disease.
- Europe's investment figure includes NATO common-funded budgets and EU peace facility contributions allocated to European security; it does not include bilateral military aid to Ukraine, which is classified separately.

---

*Bibliography compiled June 2026 | Sources: IEP GPI 2025; GitHub repo DonFrancis1/Global-Peace-Index-with-Microsoft-Fabric*
