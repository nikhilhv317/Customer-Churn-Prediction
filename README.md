# Customer-Churn-Prediction
This case requires trainees to develop a model for predicting customer churn at a fictitious wireless telecom company and use insights from the model to develop an incentive plan for enticing would-be churners to remain with company.
Data for the case are available in csv format.
The data are a scaled down version of the full database generously donated by an
anonymous wireless telephone company.
There are still 7043 customers in the database, and 20 potential predictors.
Candidates can use whatever method they wish to develop their machine learning model.
The data are available in one data file with 7043 rows that combines the calibration and
validation customers. “calibration” database consisting of 4000 customers and a
“validation” database consisting of 3043 customers.
Each database contained (1) a “churn” variable signifying whether the customer had left
the company two months after observation, and (2) a set of 20 potential predictor
variables that could be used in a predictive churn model.
Following usual model development procedures, the model would be estimated on the
calibration data and tested on the validation data.
This case requires both statistical analysis and creativity/judgment. I recommend you
spend much time on both fine-tuning and interpreting results of your machine learning
model.

YES(1) or NO(0)

Final Conclusions
Expectations from the Candidates:
Your task is to execute the multistage process for proactive churn management. Please
answer the following questions:
1. Data cleaning including missing values, outliers and multi-collinearity. Describe your
predictive churn model. How did you select variables to be included in the model?
2. Demonstrate the performance of the model.
3. What are the key factors that predict customer churn? Do these factors make sense?
4. What offers should be made to which customers to encourage them to remain with
company?
5. Assuming these actions were implemented, how would you determine whether
they had worked?


1. Data cleaning including missing values, outliers and multi-collinearity. Describe your
predictive churn model. How did you select variables to be included in the model?

:-Churn was a clean data set there was no missing values and variables are co related as shown in above describe function

i take two vairables such as x and y and y target taken as churn and remaining variables taken as x without TotalCharges beacuase it has more difference in total charges and it affects the accuracy

2. Demonstrate the performance of the model.

:- I have used logistic regression it is best model it shows 82% accuracy more than any other models which i have used
   and support vector machine i get the accuracy score is 79%, xgboost accuracy score is 77% and random forest accuracy score      is 80% approximately and i have used dimensionlity reduction but none of the model accuracy increases so i leave that and 
   random search cv should i have used in google colaboratory in my local host it was taking lot of time so i left that
   
   
   3. What are the key factors that predict customer churn? Do these factors make sense?

:- yes it make sense i have taken all the factors without total charges and customer id
   
   
   4. What offers should be made to which customers to encourage them to remain with
company?

:- percentage of the customers stayed with the company should be extend more by giving offers
    paperless billing should be increased
   * one year contarct is very less that should be increased lot
   * online backup is not there in most of the customers that affects more churn
   * online security, device protection, streaming movies should be increased
   * multiple lines should be increased
   * technical support should be given more
   * other payment modes should be encouraged
 
 5. Assuming these actions were implemented, how would you determine whether
they had worked?

:- yes is if above actions are implemented it reduces the churn and it will increase in the business
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
