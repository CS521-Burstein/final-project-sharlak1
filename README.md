CS521- Project:
<br/>
Topic: Housing Prices(Linear Regression)
<br/>
Names: Lakshitaa Sharma, Nishka Doddamani, Rajat Chawla
<br/>
We started by loading the dataset into our environment using pandas and storing it in a dataframe. 
<br/>
Steps to reproduce results:

1) Run the download_dataset.ipynb script
2) Run every cell in project_analysis.ipynb file to reproduce results


Furthermore, we are going to do exploratory analysis and make visualizations to build understanding of our data and importance of different variables. Also, we will study relationship between variables (correlation) in the second deliverable
We started by reading the dataset and storing it in a dataframe using pandas. We found out that there exists various NaN values in our data. Our response variable is going to be Sale Price, so we removed the rows that had NaN values for sale price whereas we converted NaN values of variables with 0 and none, depending upon the nominal and ordinal features which would later be used for dummifying our categorical variables to use it for regression model. 

Also, we built visualizations by forming KPI's and generated useful insights. 

Further, we would use some machine learning algorithms such as k-means clustering, linear regression for prediction etc.
We saw there are 1460 properties wherein we had sale price without any outliers and NaN values from which NAmes had the highest sale price (either we can say most populated area or most expensive area)

April 27 Deliverable-
We started by extensive data exploration to find out the most useful and least useful columns (variables) in our dataset. We spent major time on preprocessing our data which is later used to build our machine learning models. 

Built various visualizations to find out outliers and to determine the levels in categorical variables such as sale condition column had two six levels from which partial had the highest median sales price whereas others showed similar median sale prices. This helped us to convert categorical variables into encoded variables (numeric) which are necessary for running any ML Algorithm. 

We performed label encoding for categorical variables to convert the variables into binary. 

Dealt with numeric variables using correlation technique. We kept the top performing variables that correlated strongly or moderately with Sales Price. 

Finally, we started with Data partitioning followed by performing K-means clustering algorithm which gave us optimum numbers of groups to be segmented in our dataset on the basis of similarities between attributes in columns. 

For the last deliverable, we are going to build another ML algorithm (random forest classifier to derive the feature importance in data. Also, we will build linear regression model for predictions followed by studying the summary statistics (R-squared, RMSE, Accuracy) and we will test our model on test (validation) set. We will make multiple regression models with improvements in predictions and accuracy. 

We ran 4 MLR models by selecting different features based on random forest classification feature results and by creating new features. We chose model 2 as the most reliable one with a R squared of 0.80 and RMSE of 35436.58. We also made new features such as age (age from year built and year of renovation), total basement score, total garage score, total exterior score. 


