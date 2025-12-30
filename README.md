# credit_risk_modelling
About the Project

This project is an end-to-end credit risk modeling exercise built on a real-world U.S. banking dataset with over 460,000 customer records and 75 features. The goal was to understand customer credit behavior, identify what drives loan defaults, and build a reliable model to estimate the Probability of Default (PD).

The project follows the same workflow typically used in banks and financial institutions, with a strong focus on interpretability, stability, and regulatory-friendly modeling techniques.

What I Did

I started with exploratory data analysis (EDA) to get a solid understanding of the data—looking at missing values, outliers, variable distributions, and how different customer attributes relate to default behavior.

To improve model reliability:

Multicollinearity was addressed using correlation analysis and VIF

Features were transformed using Weight of Evidence (WOE)

Predictive strength of variables was evaluated using Information Value (IV)

Based on these insights, I built a Logistic Regression model to predict the probability that a customer will default on a loan. Logistic regression was chosen for its transparency and widespread use in credit risk modeling.

Model Performance & Validation

The final model shows strong performance and stability:

ROC-AUC: 0.87

F1-Score: 0.75

To ensure robustness and compliance with credit risk standards, the model was further validated using:

KS Statistic

Gini Coefficient

These metrics confirm that the model effectively separates good and bad borrowers while remaining interpretable and suitable for real-world credit decisioning.

Why This Project Matters

Demonstrates practical use of WOE & IV, commonly used in banking

Shows experience working with large, real-world financial datasets

Balances model performance with explainability, which is critical in regulated environments

Reflects an industry-aligned credit risk modeling workflow

Tools & Libraries

Python

Pandas, NumPy

Scikit-learn

Statsmodels

Matplotlib, Seaborn
