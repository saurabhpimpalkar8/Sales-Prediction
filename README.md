# Sales-Prediction
 To pre-categorize the lead quality and as result, expecting significant increase in sales effectiveness.

### Business Case:
1. FicZon Inc is an IT solution provider with products ranging from on-premises products to SAAS based solutions. FicZon major leads generation channel is digital and through their website
2. FicZon business is majorly dependent on the sales force effectiveness. As the market is maturing and more new competitors entering the market, FicZon is experiencing the dip in sales.
3. Effective sales is dependent on lead quality and as of now, this is based on manual categorization and highly depended on sales staff.
4. Though there is a quality process, which continuously updates the lead categorization, it’s value is in for post analysis, rather than conversation.
5. FicZon wants to explore Machine Learning to pre-categorize the lead quality and as result, expecting significant increase in sales effectiveness.

=======================================================================================

We have the Past data of Sales which shows the performance of all the Sales Agents viz. Their performance and capability to do Sales work.
On Visualizing Univariate and Bivariate Analysis, we will come to know the factors affecting the company's performance
First we will load the data from given Db host by using sqlalchemy library in python:

### Database details:
DB Name: project_sales

Table Name: data

Host: 18.136.157.135

Port: 3306

Username: dm_team2

Password: DM!$Team&27@9!20!

========================================================================================

As the data contains object variables so no feature selection process will be there, as this process only applicable for continuous variables where we check the pearson's correlation between the numerical features.

Also there is no need to check the outliers as all the features is of categorical type

Here, we need to convert the categorical features into numerical features by applying Encoding Techniques.

Nominal Order: If a feature contains categorical data of nominal order then we will go for OneHotEncoding, Binary Encoding, Label Encoding,etc

Ordinal Order: If a feature is of Ordinal type categorical data then we will apply Ordinal Encoding

Here, Our Target Variable is 'Status' so we will have to categorize all entries into 'High potential' and 'Low Potential'

As this will be of Classification between High potential and Low potential, we will go for Logistic Regression, Decision tree Classifier, RandomforestClassifer.

You can also go for KNN, SVM, XGboost techniques

At the end we will apply Hyperparameter Tunning to increase the accuracy of model and at final stage we will come to conclusion


We got accuracy-
1. Logistic Regression : 64.49%
2. Decision Tree : 69.42%
3. Random Forest : 65.33%

### Conclusion:

1. The customers belonging to that location must be aware of trending products and supplies hence have to arrange promotional campaign.
2. The Agents must have training sessions according to their progress report to improve their convincing skills
3. Agents have to be given a region of sale according to their languages known so that customers feels them as a familiar person
4. Delivery mode must be quick and fast as the customer feels trust and faith on the company service.
