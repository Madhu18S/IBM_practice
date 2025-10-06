"# IBM_practice" 
Project: Insurance Prediction based on Disease Severity
Role: Person A — Data Cleaning & Feature Engineering

✅ Steps Done:
- Removed invalid values (negative billing, bad room numbers)
- Encoded categorical features: Gender, Blood Type, Medical Condition, etc.
- Normalized numeric columns using StandardScaler
- Added synthetic columns: BMI, BloodPressure, Cholesterol, ClaimAmount, AnnualIncome
- Created derived features:
    * Health_Risk_Index = (Age × Cholesterol × BloodPressure) / BMI
    * Claim_to_Income_Ratio = ClaimAmount / AnnualIncome
- Saved clean dataset: clean_health_insurance.csv

📁 Files shared:
1. data_cleaning.ipynb — full notebook
2. clean_health_insurance.csv — ready for model training
3. README_PersonA.txt — summary for integration
