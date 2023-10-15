# Bankruptcy-Risk-Analysis-SAS

## Objective:
The aim of this project was to develop a predictive model that combines various econometric measures to foresee the financial conditions of a firm.

## Data Source:
Utilized a training dataset from Kaggle containing 10,000 rows.
The dataset comprised 64 predictors and 1 target variable, focusing on financial indicators.

## Tools and Technologies:
Leveraged SAS Enterprise Miner (SAS EM) for predictive modeling and data mining on large datasets.
Conducted exploratory data analysis (EDA) to gain insights into the data distribution and characteristics.

## Model Development:
Built baseline models incorporating feature selection techniques, particularly employing neural networks.
Observed that a neural network without feature selection yielded superior ROC, misclassification rates, and fewer false negatives, indicating the importance of all variables in accurate predictions.

## Data Partitioning:
Partitioned the data into a 70% training set and a 30% validation set to evaluate model performance.

## Model Comparison:
Explored various models and observed that an ensemble model, combining logistic regression, gradient boosting, and neural networks, achieved the highest ROC score (94%).

## Evaluation Metrics:
Emphasized ROC curve and AUC for assessing model performance in imbalanced datasets, providing a nuanced evaluation of the model's effectiveness.

## Business Impact:
The developed predictive model enables the assessment of a company's financial condition and future prospects, essential for making informed decisions regarding its long-term operation in the market.
