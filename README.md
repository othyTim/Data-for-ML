# Car Insurance Claim Behavour and Predictions
## Analysing Care Insurance claims to predict claim probabilities

**Author**: Timothy Lingeveldt

### Business problem:
- Identify Customer with high risk of claims:

### Stakeholders
- Marketers, Sales, Risk Assesssments for new customers


### Data Source
- Kaggle: Car Insurance Data https://www.kaggle.com/datasets/sagnik1511/car-insurance-data

### Data Description:
- Info on dataset: Annual car insurance data.

- Features: 19 features, 1000 rows.

- Target: Outcome (The outcome column indicates 1 if a customer has claimed his/her loan else 0)

## Exploratory Data Analysis

### Number of Vehicle ownership and Outcome status
The below chart implies that having vehicle ownership is associated with a lower likelihood that a customer will claim

![Vehicle ownership](https://github.com/othyTim/Data-for-ML/assets/138816378/88e1779b-6f23-452d-b2ed-a3e11b7c09b7)


#### Outcome Distribution amongst Income Classes
The graph below shows us that there is a trend in regard to the income classes and there loan claim status.
The higher the class the less claimed loans. it shows us that the only class that has more claimed loans than non claimed is the poverty class. it also shows us the higher the class the greater the proportional gap of the claimed and non claimed loans.

![Income distribution](https://github.com/othyTim/Data-for-ML/assets/138816378/495870be-4917-4253-855a-b10bda17450a)

## Machine Learning Model (best Model)
- Default Logistic Regression Model (Testing Set):
  - Precision = 0.775714
  - Recall = 0.698842
  - F1 Score = 0.735274
  - Accuracy = 0.843600
  
The model provided the Best:
- Accuracy - which indicates the model predicts 84% the risk of probable customer claims
- Regarding type 2 error which i believe is what we want to decrease to ensure we predict "positive" outcomes corrrectly, Score is at 69%, i would consider room for improvement but it was best recall score amongst other models tested.

## Recommendations
 - Vehicle ownership a has negative impact on the outcome and should be factored into decision-making in the risk assessment.
 - Review your market strategy and target market. based on the income class, the data indicates majority of the customer base is upper class customers, this indicates room for opportunity to increase customer base amongst the other income classes by potentially marketing more competitively however still keeping the risk assessment in mind.
