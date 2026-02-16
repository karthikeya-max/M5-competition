# Series: HOUSEHOLD_1_482_CA_1

## Metadata

- **Item ID:** HOUSEHOLD_1_482  
- **Department:** HOUSEHOLD_1  
- **Category:** HOUSEHOLD  
- **Store:** CA_1  
- **State:** CA  

---

## Series Characteristics (Original Series)

- **Total Observations:** 1941  
- **Number of Zero Values:** 785  
- **Percentage of Zeros:** 40.44%  

The original series exhibits substantial intermittency, with over 40% zero demand observations. This indicates irregular purchasing behavior and extended periods of no demand.

---

## Gap Structure Analysis

Two major zero-demand gaps were identified:

| Gap Number | Start Day | End Day | Length |
|------------|-----------|---------|--------|
| 23         | 264       | 519     | 256    |
| 147        | 1257      | 1438    | 182    |

These extended zero intervals significantly contribute to the intermittent nature of the series and may affect forecasting model stability.

---

## Cleaned Series Characteristics

After removing major structural gaps:

- **Zero Count (Cleaned):** 347  
- **Zero Percentage (Cleaned):** 23.09%  

The cleaned series demonstrates moderate intermittency, allowing for a clearer comparison of forecasting performance without the influence of prolonged inactivity periods.

---

## Contents of This Folder

- Time series visualization (original and cleaned)  

