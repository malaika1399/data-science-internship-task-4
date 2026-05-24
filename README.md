# data-science-internship-task-4
Task 4 added Insurance claim prediction


## Task 4: Predicting Insurance Claim Amounts

### Objective
Linear Regression se insurance charges predict karna

### Approach
1. insurance.csv dataset load kiya
2. Missing values check kiye — dataset clean tha
3. sex, smoker, region columns encode kiye
4. Linear Regression model train kiya (80/20 split)
5. MAE aur RMSE se evaluate kiya

### Results
- Smoking sabse bada factor nikla (0.79 correlation)
- Model R2 Score: ~0.78
- MAE: ~$4,200

### Tools Used
Python, pandas, matplotlib, seaborn, scikit-learn
