# Multinomial-logistic-regression-in-R
This project uses multinomial logistic regression to model anti-immigrant attitudes based on social and political factors. Using ESS data, it analyzes how education, economic concerns, and perceived threat influence support for anti-immigrant policies.



Modeling Anti-Immigrant Attitudes Using Discrete Choice Models

Course
Discrete Choice Modeling, Linköping University


Overview
This project explored how anti-immigrant attitudes vary among individuals based on social and political variables using discrete choice models (DCMs). Using data from the European Social Survey (ESS), the aim was to predict and interpret how characteristics such as education, economic attitudes, and perceived threat from immigration influence the likelihood of expressing anti-immigrant sentiments. The focus was on comparing multinomial logistic regression models and interpreting odds ratios.


Dataset
European Social Survey (ESS) dataset with individual-level responses on political preferences, education, income, region, and immigration attitudes.
Tools & Methods

Language: R

Libraries: tidyverse, nnet, sjPlot, stargazer

Techniques:
- Multinomial Logistic Regression
- Model Comparison using AIC and Likelihood Ratio Tests
- Visualization of Odds Ratios and Predicted Probabilities

- 
Main Steps
1. Data preprocessing and recoding of categorical variables
2. Estimating multinomial logistic regression models for anti-immigrant attitudes
3. Visualizing predicted probabilities across education levels and regions
4. Comparing models with and without control variables using Likelihood Ratio Tests
5. Interpreting odds ratios to understand key predictors such as education and economic attitudes

   
Key Findings
- Education was a significant predictor: individuals with higher education were less likely to support anti-immigrant policies.
- Perceived threat from immigration and negative economic attitudes increased the odds of holding anti-immigrant views.
- Model comparisons showed that including immigrant threat variables significantly improved model fit.
- Odds ratios were more interpretable and practical than raw coefficients for understanding categorical outcomes.

- 
Conclusion
The project demonstrated how discrete choice models can be used to model political attitudes and identify influential social predictors. The use of multinomial logistic regression and model evaluation tools provided insights into how demographic and ideological factors affect anti-immigrant sentiment across Europe.
