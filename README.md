# ⛏️ Gold Recovery Prediction (Zyfra Mining)

## Project Overview
This project was developed as part of the Data Science Bootcamp (TripleTen).  
The goal is to predict the recovery efficiency of gold from ore at different stages of the extraction and purification process, helping mining companies optimize production and reduce losses.

---

## Problem Statement
In mining operations, predicting gold recovery is critical for operational efficiency.  
An accurate forecast allows companies to adjust parameters and avoid inefficient or costly processes.

---

## Dataset
- Source: Industrial dataset from **Zyfra Mining**.  
- Size: ~16,000 records.  
- Features: Concentrations of metals (Au, Ag, Pb), recovery rates at different processing stages (rougher, cleaner).  
- Target: Final gold recovery rate.  

---

## Tech Stack
- **Languages/Libraries**: Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Models**: Linear Regression, Random Forest, Gradient Boosting  
- **Metrics**: Custom metric **sMAPE** (Symmetric Mean Absolute Percentage Error)  

---

## Key Results / KPIs
- Compared Linear Regression, Random Forest, and Gradient Boosting models.  
- Final model achieved **sMAPE = 9.21%**, surpassing baseline results.  
- Provided actionable insights about the influence of feed composition on final recovery rates (e.g., gold recovery increased from ~10% in feedstock to 40–50% in final product).  

---

## Visualisations
The project includes:
- Distribution of gold concentration by stage.  
- Feature importance analysis.  
- Model performance comparison (sMAPE).  

---

## How to Reproduce
1. Clone the repository:
   ```bash
   git clone https://github.com/SantiagoPulidoH/prediccion-recuperacion-zyfra.git
   cd prediccion-recuperacion-zyfra
