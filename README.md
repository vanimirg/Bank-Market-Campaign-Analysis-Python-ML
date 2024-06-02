# Bank-Market-Campaign-Analysis-Python-ML

# Bank Marketing Campaign Analysis

## Project Overview

This project analyzes a bank marketing campaign dataset to predict whether a client will subscribe to a term deposit. The dataset includes various attributes related to the bank's clients and their interactions during the marketing campaigns. The goal is to identify key factors that influence the success of the marketing campaign and provide actionable insights to improve future campaigns.

## Data Source

## Methodology

### Data Collection

The dataset was sourced from a bank's marketing campaign records, including attributes such as age, job, marital status, education, and contact details.

### Data Preprocessing

Data preprocessing steps included handling missing values, encoding categorical variables, and normalizing numerical features. The 'duration' attribute was dropped as it is highly correlated with the target variable and is not known before the call is made.

### Exploratory Data Analysis (EDA)

EDA was conducted to understand the distribution of features and their relationships with the target variable. Visualizations were created using libraries such as Seaborn and Plotly.

### Model Building

Several machine learning models were built and evaluated to predict whether a client will subscribe to a term deposit. Models used include:
- Decision Tree Classifier
- Gradient Boosting Classifier

### Model Evaluation

Models were evaluated using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC. The Gradient Boosting Classifier showed the best performance with high accuracy and ROC-AUC.

## Results

Key findings from the analysis include:
- Age and job are significant factors influencing the likelihood of subscribing to a term deposit.
- Clients with personal loans are less likely to subscribe.
- The duration of the call positively correlates with the subscription rate, suggesting the importance of engaging conversations.

## Conclusion and Future Work

The analysis provides valuable insights into factors affecting the success of the bank's marketing campaigns. Future work could focus on deploying the model to assist in real-time decision-making and further refining the model with additional data.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

