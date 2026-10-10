# Online Shopping Purchase Prediction 🛒

### Machine Learning | Python | Data Analytics

A machine learning project completed as part of my Data Mining & Machine Learning coursework at the National College of Ireland.

## Project Overview

This project explores how machine learning can be used to predict whether an online shopper will complete a purchase based on their browsing behaviour.

I worked with a dataset containing 12,330 records and 18 columns, exploring customer behaviour and comparing different machine learning models to predict purchasing intention.

## Tools & Technologies

- Python
- Pandas & NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

## Data Preparation

Before training the models, I explored the dataset, checked for missing values and removed 125 duplicate records.

I also analysed relationships between features, converted categorical variables into numerical values and split the data into training and testing sets.

## Machine Learning Models

I trained and compared three classification models:

- Logistic Regression
- Random Forest
- Gradient Boosting

## Results

| Model | Accuracy | F1-score |
|---|---|---|
| Logistic Regression | 88.9% | 0.541 |
| Random Forest | 90.8% | 0.669 |
| Gradient Boosting | 90.7% | 0.681 |

*F1-scores refer to the purchasing class.*

Random Forest achieved the highest accuracy, while Gradient Boosting achieved the highest F1-score and recall for customers who completed a purchase. I selected Gradient Boosting as the preferred model because identifying purchasers was an important part of the project.

## What I Learned

This project helped me develop my understanding of data preparation, classification models and performance evaluation.

One of my biggest takeaways was learning why accuracy alone isn't always the best way to judge a model, especially when working with imbalanced datasets.

I also gained more practical experience working with Python, analysing data and comparing machine learning models.

## Project Files

- **Jupyter Notebook:** Contains the data exploration, preprocessing, model training and evaluation.
- **CSV Dataset:** The original online shopping dataset used in the project.
- **Outputs:** Generated visualisations, model comparison results and saved model files.
