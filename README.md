# Churn Prediction in Telecom Industry

## Project Overview

This project focuses on predicting customer churn in the telecom industry using machine learning techniques. The goal is to identify customers who are likely to leave the telecom service, enabling companies to take proactive measures to retain them.

## Dataset

The dataset consists of records for **7,043 telecom customers**, including various attributes related to customer demographics, account information, and service usage.
*Source*: [https://www.kaggle.com/datasets/blastchar/telco-customer-churn]

## Methodology

1. **Exploratory Data Analysis (EDA):** Conducted to understand the distribution of data, identify missing values, and detect any anomalies.
2. **Data Preparation:**
   - **Handling Missing Values:** Missing data were appropriately managed.
   - **One-Hot Encoding:** Categorical variables were converted into a format suitable for machine learning models.
   - **MinMax Scaling:** Features were scaled to ensure all variables contribute equally to the model.
3. **Model Training:**
   - **Model Used:** Logistic Regression.
   - **Train-Test Split:** The dataset was split into 70% for training and 30% for testing.
   - **Feature Selection:** Recursive Feature Elimination (RFE) was used to optimize the selection of features.

## Results

- **Model Accuracy:** The logistic regression model achieved an overall accuracy of **0.80**.
- **Performance Metrics:** While the model showed decent accuracy, it had **low recall and precision**, indicating a need for further model tuning and optimization.

## Future Work

- **Feature and Model Optimization:** Further work can focus on refining feature selection and tuning the logistic regression model.
- **Model Comparison:** Evaluating the performance of other machine learning models (e.g., Decision Trees, Random Forest, SVM) to improve churn prediction accuracy.

## Ethical Considerations

Based on the goals of this research, an ethical assessment was conducted, and no significant ethical issues were identified.

## Conclusion

This project demonstrates the potential of using machine learning for churn prediction in the telecom industry. Despite the current model's limitations, there is significant scope for improvement through future research and optimization.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

Feel free to explore the repository and contribute!

