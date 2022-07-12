## Project Name
## Telecom Churn Prediction

Telecommunication industry, customers tend to change operators if not provided with attractive schemes and offers. It is very important for any telecom operator to prevent the present customers from churning to other operators. As a data scientist, your task in this case study would be to build an ML model which can predict if the customer will churn or not in a particular month based on the past data.

## General Information

## Introduction 

The main goal of the case study is to build ML models to predict churn. The predictive model that you’re going to build will the following purposes: It will be used to predict whether a high-value customer will churn or not, in near future (i.e. churn phase). By knowing this, the company can take action steps such as providing special plans, discounts on recharge etc. It will be used to identify important variables that are strong predictors of churn. These variables may also indicate why customers choose to switch to other networks. Even though overall accuracy will be your primary evaluation metric, you should also mention other metrics like precision, recall, etc. for the different models that can be used for evaluation purposes based on different business objectives. For example, in this problem statement, one business goal can be to build an ML model that identifies customers who'll definitely churn with more accuracy as compared to the ones who'll not churn. Make sure you mention which metric can be used in such scenarios. Recommend strategies to manage customer churn based on your observations.

## Business Problem Statement

- Predict whether a high-value customer will churn or not, in near future
  By knowing this, the company can take action steps such as providing special plans, discounts on recharge etc. and for this purpose best model is Logistic Regression ehich can be used to explain the result for all the customers.
- Identify important variables that are strong predictors of churn
- Overall accuracy of the models will be your primary evaluation metric, you should also mention other metrics like precision, recall etc.
- Predict highest acuuracy as overall accuracy is primary evaluation metric in Kaggle.
- Recommend strategies to manage customer churn based on your observations

## Business Goal
   Model will only be able to achieve one of the two goals:
- To predict customers who will churn.
- Build another model with the main objective of identifying important predictor attributes which help the business understand indicators of churn. 
Good choice to identify important variables is a logistic regression model or a model from the tree family. 

## Steps:
- Data Understanding, Preparation, and Pre-Processing 
- Exploratory Data Analysis
- Feature Engineering and Variable Transformation 
- Model Selection, Model Building, and  Prediction

## Technologies Used
Python Notebook: One Python notebook with the whole linear model, predictions, PCA and evaluation.
Python, Numpy, Pandas, SkLearn, matplotlib, LinearRegression, seaborn, Tree, Classifiers libraries

## Acknowledgements
- This project will help for Telecommunication industry, customers tend to change operators if not provided with attractive schemes and offers. 


## Dataset characteristics

Train_dataset.csv
Test_dataset.csv
Data_Dictionary.csv
Solution.csv

## License

Use of this dataset in publications must be cited to the following publication:
Please refer the Kaggle website

## Conclusions

### 7.1 Model 1: For interpretation
	1. Maximum factors which are effecting churn are for month August.
	2. Churn rate is high when Total incoming and ougoing minutes for voice calls in August is lower. Thus if no of incoming and outgoing calls are decreasing for a particular customer there is high change he may be switching to another network.
	3. Lower Service schemes with validity equivalent to a month for 3G in August also indicates higher probability of churn. If network condition in a place is good, customers will use data early thus there will more no. of recharges and thus less chances of churn, however if network is poor then data will not be 	consumed and thus no. of monthly recharges will be less, leading to churn.
	4. If incoming calls are high and outgoing calls are less then customer may be finding the services very costly and may switch to network where incoming and outgoing services are in less/reasonable according to him/her.
#### 7.2 Model 2: For purpose of accurate prediction
	Final Model for Submission is XGBoosting model with test accuracy of 94.58%.

Created by- @Rohitcnith & @GiridharTarare
