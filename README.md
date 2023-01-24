# Insurance_Fraud_Detection

In this repo, I have developed an ML classification algorithm to identify and predict insurance fraud/non-fraud claims using the insurance fraud dataset from kaggle, which can be found [here](https://www.kaggle.com/datasets/buntyshah/auto-insurance-claims-data).

Techniques: EDA, Feature Engineering, Outlier detection and removal, scaling, Data Modelling, Model Evaluation.
Tech Stack used: pandas, numpy, python, sklearn, matplotlib, seaborn, etc.

## EDA
The density plot of total claim amount and vehicle claim amount with respect to claim being fraud/non-fraud is shown below. From the plot
- The total claim and the vehicle claim amount graphs are mostly identical, this verifies that they both are highly correlated.
- Claims with very high claim amounts are more likely to be fraudulent.
<p align='center'>
  <img src='https://user-images.githubusercontent.com/60603790/214307562-ef19b309-1947-4c1b-9b54-e9f21e8bbaac.png' width='700' height='300' />
</p>
 
Below is the bar chart of the top 10 most frequent hobbies mentioned by claimers. 
- The hobbies mentioned such as reading, yachting, hiking, and exercise are most prone to being fraudulent claims.
<p align='center'>
  <img src='https://user-images.githubusercontent.com/60603790/214311173-4b4204e4-9cc5-427e-8cfb-f5289a27c1f8.png' width='700' height='300' />
</p>

Incident severity in regards to fraud/non-fraud claim is shown in the below graph.
- Severity of the incident mentioned as major damage tend to be fraudulent than other severity types.
<p align='center'>
  <img src='https://user-images.githubusercontent.com/60603790/214372219-e20a81d0-6eee-4924-8d2b-bf2f5075b66a.png' width='700' height='300' />
</p>

## Modelling and Evaluation
For the purpose of this project, models like Decision Trees, Random Forest and SVC were built on a training set and evaluated on a separate test set. Evaluation metrics used are PRF1. The Confustion of the best model i.e. SVC is shown below.
<p align='center'>
  <img src='https://user-images.githubusercontent.com/60603790/214396862-90195f37-e576-4453-b842-6279d6dd4521.png' width='400' height='500' />
</p>




