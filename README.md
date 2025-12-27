# hospital-charges-medicare-analysis
Analysis of U.S. hospital charges using Medicare inpatient data and linear regression.

This project uses and analyzes publicly available Medicare inpatient hospital data from the Centers for Medicare & Medicaid Services (CMS) to identify key factors associated with variation in hospital charges across the United States. This analysis quantifies how Medicare payments, patient risk, and hospital volume relate to submitted hospital charges.

Data Source and Collection:

Source: Centers for Medicare & Medicaid - https://data.cms.gov/provider-summary-by-type-of-service/medicare-inpatient-hospitals/medicare-inpatient-hospitals-by-provider/data 

Samples: 3,093 hospitals

Features: 57 volume, financial, and risk variables

Key variables used:

- Total Submitted Covered Charges  
- Total Medicare Payment Amount  
- Total Payments  
- Total Discharges  
- Average Beneficiary Risk Score



Methods:
  
- Data cleaning and removal of duplicates and missing values
  
- Log transformation of highly skewed financial variables
   
- Linear regression modeling

- Regression coefficients to find the relationship between target and predictor variables
  
- Train/test split for model evaluation


  Findings:
  
- Medicare payment amounts are strongly and positively associated with hospital charges
  
- Higher average patient risk scores correspond to higher hospital charges
  
- Log-log modeling allows percentage-based interpretation of regression coefficients. Log transformation was used for certain variables that were highly skewed.
  
- R² ≈ 0.91 for both train and test so model explains 91% of the variation in hospital charges


Tools & Libraries:

-Python 

-Pandas

-NumPy

-Matplotlib

-Scikit-learn

  
