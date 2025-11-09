# Telecom Customer Churn Prediction

## Project Overview
This project aims to develop machine learning models to predict customer churn in the telecom industry. By analyzing customer data and usage patterns, the models help identify customers who are likely to churn, enabling telecom companies to take proactive retention actions.

## Dataset
The dataset includes features such as payment method, tenure, subscribed services, total minutes, state, area code, international plan, and usage metrics (day and night minutes). The target variable is churn status (retained or churned).

## Models Evaluated
- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest
- K-Nearest Neighbors (KNN)
- Naive Bayes

## Model Performance Summary

| Model                 | Accuracy |
|-----------------------|----------|
| Random Forest         | 0.917    |
| Naive Bayes           | 0.827    |
| Support Vector Machine| 0.799    |
| Logistic Regression   | 0.696    |
| K-Nearest Neighbors   | 0.656    |

Random Forest achieved the highest accuracy and demonstrated robust performance in identifying customers likely to churn. Naive Bayes and SVM also performed reasonably well, while Logistic Regression and KNN lagged behind.

## Key Insights
- Random Forest's ability to capture complex feature interactions makes it the best performing model.
- Naive Bayes provides a strong baseline with balanced precision and recall.
- Models generally perform better at identifying retained customers than churners, highlighting the challenge of predicting the minority class.
- Improving recall for churn is critical to minimize missed churn cases, guiding efforts to tune models or use ensemble methods.

## Project Structure
- Data preprocessing scripts
- Exploratory data analysis notebooks
- Model training and evaluation scripts
- Visualizations and performance reports

## Getting Started
1. Clone the repository.
2. Install required packages listed in `requirements.txt`.
3. Run data preprocessing and feature engineering scripts.
4. Train models using training scripts.
5. Evaluate models and review performance metrics.

## Dependencies
- Python 3.x
- pandas
- scikit-learn
- matplotlib
- seaborn

## Contact
For questions or contributions, please open an issue or submit a pull request.

---

This README provides a comprehensive overview suitable for sharing on GitHub to document your telecom churn prediction project clearly and professionally.
