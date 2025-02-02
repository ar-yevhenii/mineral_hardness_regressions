# Regression Analysis for Mineral Hardness

This project involves a detailed regression analysis to predict the hardness of minerals based on various atomic and elemental properties. The analysis is performed using Python and several machine learning libraries.

## Analysis Steps
1. **Data Import**: Load the training and test datasets.
2. **EDA and Data Preprocessing**: Perform exploratory data analysis and preprocess the data by handling outliers and missing values.
3. **Correlation Analysis**: Analyze the correlation between features and the target variable.
4. **Data Splitting**: Split the data into training and validation sets using `train_test_split` and `KFold` cross-validation.
5. **Model Training and Evaluation**: Train and evaluate various regression models including Linear Regression, Ridge, Lasso, and ElasticNet.
6. **Regularization**: Analyze the impact of L1 and L2 regularization on model performance.
7. **Polynomial Features**: Experiment with polynomial features to improve model performance.

## Key Findings
- **Data Quality**: The dataset does not contain missing values, and most features have a small percentage of outliers.
- **Correlation**: Features like `allelectrons_Average`, `atomicweight_Average`, and `density_Average` show strong correlation with the target variable `Hardness`.
- **Model Performance**: Ridge regression with an optimal regularization coefficient provides the best performance. Lasso regularization tends to degrade model accuracy.
- **Polynomial Features**: Using polynomial features of degree 2 improves model performance, but higher degrees lead to overfitting.
