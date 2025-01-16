# Customer-Churn-Prediction

## Technologies Used

*   **Programming Language:** Python
*   **Machine Learning Libraries:** scikit-learn, pandas, numpy
*   **Data Visualization:** matplotlib, seaborn
*   **Preprocessing:** Label Encoding
*   **Model Selection & Tuning:** Grid Search CV
*   **Trend Analysis:** Subburst analysis

## Model Development

1.  **Data Exploration and Analysis:** Includes trend analysis by examining subbursts of the data (e.g., analyzing churn rates within specific time periods. This helped identify patterns and potential drivers of churn.
2.  **Data Preprocessing:** Handled missing values, and used **Label Encoding** to convert categorical features into numerical representations suitable for machine learning models.
3.  **Model Selection:** Trained and evaluated various ML models .
4.  **Hyperparameter Tuning:** Used **Grid Search CV** to systematically search for the optimal combination of hyperparameters for the chosen model, maximizing performance through cross-validation. This ensures a robust and well-tuned model.
5.  **Model Evaluation:** Used metrics like accuracy, precision, recall, F1-score, AUC-ROC.

## Key Findings

*   Overall churn rate was 26%.
*   Trend analysis revealed a significant increase in churn during the last quarter of the year.
*   Churn rate among customers with month-to-month contracts and fiber optic internet increased sharply in the past 3 months. This is a key subburst to focus on.
*   Older customers with long-term contracts showed very low churn across all time periods.

## Model Performance

Accuracy = 80%.
Sencitivity = 35%.
Specificity = 96%.
