# Predicting restaurant tips using predictive analytics on Excel
I have used Regression Analysis (an important type of data analysis) for the prediction of tips.
The dependent variable to be predicted was tips and independent variables which may impact the tips prediction were sex, smoker, day, time, size and total bill.
Data cleaning was done for checking missing values,duplicate values etc. (Luckily the data was already clean)
I started by plotting graphs to observe any correlation.
The categorical variables were converted to dummy variables(numeric) for performing multi linear regression.
Multi linear regression were performed using the data analysis toolpak.
sex, smoker, day, time were excluded from the regression analysis as their p value was larger than 5% which could be explained by randomness.
Prediction calculator was built to calculate tips based on size and total_bill.
Predicted Tips= intercept +(coefficient of size * size) + (coefficient of total_bill* total_bill) Y=Constant +B1*(X1)+B2*(X2)+....BnXn
Root mean square error was calculated which could be used to evaluate the quality of predictions.
