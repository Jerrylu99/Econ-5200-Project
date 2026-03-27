# ECON 5200 Data Project  
## Minimum Wage and Employment: A Difference-in-Differences and Event Study Analysis  

---

## 📌 Project Overview

This project replicates the Difference-in-Differences (DID) analysis from Card and Krueger (1994), examining the impact of a minimum wage increase on employment in fast-food restaurants in New Jersey (treatment group) and Pennsylvania (control group).

The project further extends the baseline analysis by implementing an event study design to analyze the dynamic effects of the policy over time.

---

## 🎯 Key Findings

- The DID analysis shows that employment in New Jersey did not decrease relative to Pennsylvania after the minimum wage increase.  
- Event study results support the parallel trends assumption prior to the policy change.  
- There is no evidence of significant negative employment effects in the post-treatment periods.  
- The dynamic analysis confirms that the policy impact remains stable over time.  

---

## 📊 Data Description

The dataset consists of fast-food restaurant employment data collected from New Jersey and Pennsylvania before and after the minimum wage increase.

Key variables include:
- Employment levels  
- Treatment indicator (New Jersey vs Pennsylvania)  
- Time indicator (pre vs post policy)  

---

## 🧩 Methodology

### 1. Difference-in-Differences (DID)

The baseline model estimates the average treatment effect of the minimum wage increase using a DID framework:

- Compares employment changes over time between treatment and control groups  
- Assumes parallel trends between groups prior to the policy  

---

### 2. Event Study Extension

To address limitations of the standard DID model, this project implements an event study approach:

- Interacts treatment status with time indicators  
- Estimates dynamic treatment effects across multiple periods  
- Allows for testing the parallel trends assumption visually  

---

## 📈 Results and Interpretation

The DID results indicate no statistically significant negative effect of the minimum wage increase on employment.

The event study further supports this finding:
- Pre-treatment coefficients are close to zero, supporting parallel trends  
- Post-treatment coefficients do not show a decline in employment  

Overall, the results suggest that the policy did not reduce employment in the short run.

---

## 📁 Repository Structure

- `Notebook 1`: Data cleaning and preparation  
- `Notebook 2`: Baseline DID replication  
- `Notebook 3`: Event study extension and analysis  

---

## ⚠️ Data Validation

Basic validation checks were performed to ensure data quality, including:
- Summary statistics (`describe()`)  
- Missing value checks (`isna().sum()`)  

The dataset shows no major inconsistencies and is suitable for analysis.

---

## 📌 Conclusion

This project successfully replicates the original DID findings and extends the analysis through an event study framework.

By incorporating dynamic treatment effects, the extension provides a more comprehensive understanding of the policy impact and strengthens the credibility of the empirical results.

---

## 🚀 Future Improvements

- Incorporate additional robustness checks  
- Explore alternative model specifications  
- Extend the analysis using larger datasets or different policy contexts  

---

## 👤 Author

Tianrui Lu  
Northeastern University – ECON 5200  
