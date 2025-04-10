# Hackathon
**University of Sheffield Hackathon**
This repository addresses the dual challenge of climate goals and economic development at the local level in the UK. It stems from two core problem statements:

Net Zero Readiness: Can we predict which local authorities are on track to reach Net Zero by 2050 based on historical emissions?

Economic Linkages: Can we uncover patterns between carbon emissions and economic indicators like business density and Gross Value Added (GVA) by industry?

The analysis focuses on local authorities within the Yorkshire and the Humber region.

**Objectives**
Analyse historical emissions data from 2005–2022.

1.Integrate GVA and business activity data to uncover relationships with emissions.

2.Identify outliers and leading/lagging LAs in terms of climate action.

3.Explore predictive models for emissions trends and Net Zero trajectory.

4.Provide visual insights to support policy-making at the LA level.

**Project files**
📂 data/

    └── emissions_2005_2022.csv
    
    └── business_2017_2022.xlsx
    
    └── gva_by_la.xlsx

📂 notebooks/

    └── 01_Emissions_Trends_Analysis.ipynb
    
    └── 02_GVA_vs_Emissions_Exploration.ipynb
    
    └── 03_NetZero_Prediction_Model.ipynb

📂 plots/

    └── emissions_by_la.png
    
    └── gva_emissions_correlation.png
    
    └── model_accuracy_comparison.png

**Tools & Technologies**
Python (pandas, matplotlib, seaborn, scikit-learn, XGBoost)

Jupyter Notebooks / Google Colab

PowerBI/Tableau (optional for dashboarding)

Data Sources: ONS, gov.uk, local authority datasets

**Ethics**
sources of the data
