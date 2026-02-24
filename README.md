📊 Income Prediction using Machine Learning

This project builds a machine learning model to predict whether an individual earns more than $50K per year using demographic and employment data.

The model is trained on census-based data and demonstrates the complete ML workflow: data preprocessing, exploratory data analysis, model training, and performance evaluation.

🚀 Project Overview

Income classification is an important socio-economic prediction problem.
This project applies machine learning techniques to classify income levels based on factors such as education, occupation, working hours, and marital status.

🧠 Features

✔ Data cleaning and preprocessing

✔ Handling missing values

✔ Encoding categorical variables

✔ Explorative Data Analysis (EDA)

✔ Feature scaling and train-test split

✔ Logistic Regression model training

✔ Performance evaluation using metrics

📂 Dataset

The dataset is derived from the Adult Census Income dataset, which includes demographic and employment-related attributes.

Key Features:

Age

Workclass

Education

Marital Status

Occupation

Relationship

Race

Sex

Capital Gain & Loss

Hours per Week

Native Country

🎯 Target Variable:

Income

>50K → High income

<=50K → Low income

🛠️ Technologies Used

Python

Pandas & NumPy

Matplotlib & Seaborn

Scikit-learn

🔄 Machine Learning Workflow

1️⃣ Data Preprocessing

Removed missing values

Converted categorical data to numeric format

Scalled features for improved model performance

2️⃣ Exploratory Data Analysis

Income distribution analysis

Gender & income comparison

Correlation heatmap

Outlier detection using boxplots

3️⃣ Model Training

Logistic Regression classifier

Train-test split (70/30)

4️⃣ Evaluation Metrics

Accuracy Score

Confusion Matrix

Precision, Recall, F1-score

📈 Results

The Logistic Regression model successfully classifies income levels based on demographic features.

Evaluation metrics used:

Accuracy

Precision & Recall

F1-score

Confusion Matrix

📊 Sample Insights

Education level strongly influences income.

Working hours and occupation impact earning potential.

Capital gain is highly correlated with high-income classification.

📌 Future Improvements

Implement advanced models (Random Forest, XGBoost)

Hyperparameter tuning

Deploy model using Flask or Streamlit

Add feature importance visualization

Improve accuracy using ensemble methods
