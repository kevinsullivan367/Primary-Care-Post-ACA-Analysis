# Medicaid Expansion and Primary Care Utilization - All analysis done in R

---

## Executive Summary  
This study evaluates the causal impact of Medicaid Expansion under the Affordable Care Act on primary care utilization in the United States using Medical Expenditure Panel Survey (MEPS) data from 2005 to 2022. Using a difference-in-differences design, three proxy outcomes were analyzed: number of doctor visits (NDV), having a usual source of care (USOC), and appointments made for primary care (MAPC). Results show significant increases in NDV and USOC among Medicaid recipients after 2014, but a slight decrease in MAPC. This suggests that while coverage and formal access improved, actual primary care engagement did not fully increase. Robustness checks confirmed these findings.

---

## Problem Statement, Dataset Overview, and Outcomes  
Access to primary care is vital for early disease detection and reducing health system costs. Medicaid Expansion was intended to improve healthcare access for low-income populations, but the extent to which it increased actual primary care utilization is unclear. This project analyzes how Medicaid Expansion affected primary care usage in the U.S. from 2005 to 2022.

- **Dataset:** Medical Expenditure Panel Survey (MEPS) 2005–2022  
- **Sample:** Individuals categorized by Medicaid recipient status  
- **Design:** Difference-in-differences comparing pre- and post-2014 trends between Medicaid recipients (treatment) and non-recipients (control)  
- **Outcomes (proxies for primary care utilization):**  
  1. Number of doctor visits (NDV)  
  2. Usual source of care (USOC)  
  3. Making an appointment for primary care (MAPC)

---

## Methods  
- Applied a difference-in-differences (DiD) design to isolate the effect of Medicaid Expansion  
- Compared treatment and control groups over time (before and after 2014)  
- Controlled for demographic and socioeconomic variables to check robustness  
- Used regression modeling to estimate statistical significance and effect sizes on the three outcomes

---

## Results  
- Significant increases in NDV and USOC for Medicaid recipients post-2014  
- Slight but statistically significant decrease in MAPC after expansion  
- Indicates improved coverage and formal access, but possible barriers to appointment-making  
- Robust to inclusion of socioeconomic and demographic controls

---

## Evaluation and Discussion  
Findings highlight that Medicaid Expansion successfully increased some measures of primary care access but did not lead to a proportional increase in primary care engagement, as measured by appointment-making. This gap may reflect provider shortages, administrative barriers, or patient-level factors limiting actual utilization. Policymakers should consider incentives for primary care providers in underserved areas and public education to improve engagement.

---

## Future Work  
- Investigate provider availability and appointment scheduling barriers in Medicaid populations  
- Explore qualitative data on patient experiences post-expansion  
- Assess the impact of state-level variation in Medicaid policies on primary care utilization  
- Expand outcomes to include health outcomes and emergency department usage  
