# R-Projects
Personal projects done in R

1) Classification comparison - HR Analytics:
    
    In this project, performance of the following classification models was compared on original, undersampled, and oversampled versions of the HR Analytics data set, with the goal of modeling which individuals were most liekly to be promoted within an organization:<br/>
        -Logistic Regression<br/>
        -Random Forest<br/>
        -XGBoost<br/>
        -SVM<br/>
     After determining the model with the best overall performance, the data was split by department since promotion rates and criteria differed significantly amongst departments.
     
     The data can be found at: https://datahack.analyticsvidhya.com/contest/wns-analytics-hackathon-2018-1/

1) df.profile_report replica:

    This script is meant to mimic the df.profile_report() function from the pandas_profiling package in python. 

    The function will report the following for all variables:<br/>
      -Missingness<br/>
      -Mean / median / variance<br/>
      -Potential outliers<br/>
      -Percent of unique values<br/>
      -Percent of values equal to 0<br/>
      -Histogram of variable distributions<br/>
  
    Correlation report to be added soon, stay tuned!
    

