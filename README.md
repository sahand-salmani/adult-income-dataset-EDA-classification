# Adult Income EDA and Classification

## Dataset Overview
This project involves a comprehensive analysis of a dataset with the following columns:

1. `age` - Age of the individual.
2. `workclass` - Type of employment (e.g., Private, Self-Employed).
3. `fnlwgt` - Final weight (a measure for the population the observation represents).
4. `education` - Highest level of education attained.
5. `educational-num` - Number of years of education.
6. `marital-status` - Marital status (e.g., Married, Single).
7. `occupation` - Occupation of the individual.
8. `relationship` - Relationship status (e.g., Husband, Not-in-family).
9. `race` - Race of the individual.
10. `gender` - Gender of the individual.
11. `capital-gain` - Capital gains.
12. `capital-loss` - Capital losses.
13. `hours-per-week` - Hours worked per week.
14. `native-country` - Country of origin.
15. `income` - Income category (<=50K or >50K).

All columns contain 48,842 non-null entries, ensuring a complete dataset for analysis.

## Objectives for Exploratory Data Analysis (EDA)
### Data Overview
1. **Display Dataset**: Preview the first few rows of the dataset.
2. **Missing Values**: Check for missing values and handle them appropriately.
3. **Summary Statistics**: Summarize the statistics for numerical features.

### Univariate Analysis
1. **Numerical Features**: Plot histograms and boxplots.
2. **Categorical Features**: Plot bar charts.

### Bivariate Analysis
1. **Numerical Features vs Income**: Create boxplots and violin plots.
2. **Categorical Features vs Income**: Create bar plots and count plots.

### Multivariate Analysis
1. **Numerical Interactions**: Use pair plots or correlation heatmaps.
2. **Categorical Interactions**: Analyze interactions with the target variable.

### Feature Engineering
1. **Create New Features**: Explore the creation of new features or modification of existing ones.

## Objectives for Principal Component Analysis (PCA)
### Standardization
1. **Standardize Features**: Ensure all numerical features have zero mean and unit variance.

### PCA Implementation
1. **Dimensionality Reduction**: Perform PCA to reduce the number of dimensions.
2. **Explained Variance**: Analyze the explained variance ratio to determine the number of components to retain.

### Visualization
1. **Explained Variance Plot**: Plot the explained variance ratio for each principal component.
2. **Scatter Plots**: Create scatter plots of the first two or three principal components.

### Interpretation
1. **Principal Components**: Analyze the loadings of the original features on the principal components.

## Objectives for Classification Model
### Data Preparation
1. **Encode Categorical Features**: Use one-hot encoding or similar techniques.
2. **Data Splitting**: Split the data into training and testing sets.

### Model Selection
1. **Explore Models**: Test various models like Logistic Regression, Decision Trees, Random Forests, and SVM.

### Model Training
1. **Train Models**: Train the models on the training data and use cross-validation for hyperparameter tuning.

### Model Evaluation
1. **Evaluate Performance**: Use metrics such as accuracy, precision, recall, F1-score, and AUC-ROC to evaluate models.
2. **Compare Models**: Select the best model based on performance metrics.

### Model Interpretation
1. **Feature Importances**: Analyze feature importances or coefficients.

### Model Validation
1. **Validation**: Test the model on a separate validation set or use k-fold cross-validation to ensure generalization.

## Summary of Work Done
In this project, we conducted a thorough exploratory data analysis to understand the structure and distribution of the dataset. We analyzed both individual features and their relationships with the target variable, `income`. Feature engineering was performed to enhance the dataset. We implemented PCA to reduce dimensionality and visualize the data in fewer dimensions. Finally, we trained and evaluated various classification models to predict income, ensuring the models' robustness through cross-validation and comprehensive performance metrics.

## Contributors

- [Sahand Salmani](https://github.com/sahand-salmani)
