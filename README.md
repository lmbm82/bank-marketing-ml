# Bank Marketing Prediction with Optimized Random Forest

## Project Description
This final Machine Learning project aims to predict whether a customer will accept a bank offer using real marketing campaign data from OpenML (Bank Marketing, ID: 1461). The goal is to identify potential customers more likely to respond positively, improving the efficiency of marketing campaigns.

## Objective
- Predict customer acceptance of a bank offer.
- Analyze customer data to identify key factors influencing acceptance.
- Compare different ML models and select the best performing one.

## Methodology
1. **Data Exploration (EDA)**: Analyze data types, missing values, and target distribution.
2. **Data Preprocessing**: Encode categorical variables (One-Hot), standardize numerical features.
3. **Model Training**: Test Logistic Regression, Decision Tree, and SVM classifiers.
4. **Model Optimization**: Choose Random Forest and adjust hyperparameters to improve minority class detection.
5. **Evaluation**: Compare models and analyze metrics such as accuracy, precision, recall, and F1-score.

## Tools & Libraries
- **Python**: Core language for ML.
- **Pandas & NumPy**: Data manipulation.
- **Matplotlib & Seaborn**: Data visualization.
- **Scikit-learn**: ML models, preprocessing, and evaluation.
- **OpenML**: Dataset retrieval.

## Results
- Initial models (Logistic Regression, Decision Tree, SVM) had ~87–90% accuracy.
- Random Forest improved detection of minority class (customers likely to accept) from **39% recall → 74% recall**.
- Optimized Random Forest balances precision and recall effectively.

## Conclusion
The project demonstrates the importance of **iterative model testing and hyperparameter tuning** in Machine Learning, particularly when dealing with **imbalanced datasets**.  
Optimized Random Forest proved to be the best model for identifying customers likely to accept bank offers.

## Files
 - 'bank_marketing_ml.ipynb' 
