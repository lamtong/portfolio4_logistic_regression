# Customer Spending Analysis at Fresco Supermarket

Refer to Refer to [portfolio_task4.ipynb](./portfolio_task4.ipynb) or [portfolio_task4.html](./portfolio_task4.html) for detailed analysis.

## Part A: Executive Summary

### Introduction
This study analyzes customer spending behavior at Fresco Supermarket based on a 26-week dataset. The objective is to predict whether a customer's shopping basket value falls into one of two categories: low spender (£50 or less) or high spender (greater than £50). The analysis examines patterns in gender, age, shopping frequency, store type, and product consistency to develop a predictive model.

### Methods
A classification model was used to predict customer spending behavior. The analysis included:
- **Data Cleaning & Preprocessing:** Handling missing values and ensuring data consistency.
- **Exploratory Data Analysis (EDA):** Identifying trends and correlations.
- **Feature Engineering:** Selecting relevant variables.
- **Model Selection:** Evaluating logistic regression and decision trees.
- **Model Evaluation:** Assessing performance using accuracy and precision metrics.

### Key Findings
- Shopping frequency and store type significantly impact spending behavior.
- High spenders are more likely to shop at superstores and purchase premium products.
- Logistic regression performed well in classifying customer segments with reasonable accuracy.

### Recommendations
- Target high spenders with personalized promotions at superstores.
- Develop loyalty incentives for low spenders to increase basket value.
- Optimize online shopping recommendations based on spending patterns.

---

## Part B: Technical Report

### Data Preparation
- The dataset was examined for missing values and inconsistencies.
- Data was encoded for categorical variables (gender, store type, product category).
- Shopping basket value was converted into a binary target variable (low vs. high spender).

### Exploratory Data Analysis (EDA)
- Descriptive statistics revealed that the average shopping basket value was skewed towards lower amounts.
- Correlation analysis showed a strong relationship between shopping frequency and spending category.

### Model Selection and Evaluation
#### Logistic Regression
- Used to estimate the probability of a customer being a high spender.
- Key coefficients indicated a positive impact of shopping frequency and store type on spending.
- Model accuracy: **94.7%**

#### Decision Tree Model
- Provided an intuitive decision rule for classifying customers.
- Higher depth improved accuracy but risked overfitting.

### Model Interpretation
- Logistic regression coefficients suggested that increasing shopping frequency significantly raised the probability of being a high spender.
- Decision tree analysis highlighted critical decision points in customer behavior.

### Conclusion
The analysis successfully classified customer spending behavior using logistic regression. Findings suggest that marketing strategies should focus on engaging high spenders at superstores while encouraging low spenders to increase basket value.
This study provides actionable insights for Fresco Supermarket’s marketing team to enhance customer engagement and optimize promotional strategies.

