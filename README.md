# Bayesian_MMM_Project
Developed a Bayesian Marketing Mix Model using PyMC to quantify the impact of TV, Radio, and Newspaper advertising on sales. Estimated channel effectiveness through posterior distributions and translated findings into actionable business insights using a two-page Power BI dashboard.

Steps-
1. Business Understanding
   ↓
2. Load Advertising Dataset (TV, Radio, Newspaper, Sales)
   ↓
3. Perform Exploratory Data Analysis (EDA)
   ↓
4. Prepare Features (X) and Target Variable (y)
   ↓
5. Build Bayesian Marketing Mix Model using PyMC
      • Define Alpha (Baseline Sales)
      • Define Beta (Channel Impacts)
      • Define Sigma (Model Uncertainty)
   ↓
6. Run MCMC(algorithm PyMC uses) Sampling to Estimate Posterior Distributions
   ↓
7. Analyze Model Results and Channel Effectiveness
   ↓
8. Generate Business Insights & Budget Recommendations
   ↓
9. Export Bayesian Results to CSV
   ↓
10. Build Interactive Power BI Dashboard
      • Marketing Performance Overview
      • Bayesian MMM Insights & Channel Effectiveness
