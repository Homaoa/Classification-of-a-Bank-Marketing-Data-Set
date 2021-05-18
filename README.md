# Classification-of-a-Bank-Marketing-Data-Set

A model is developed to predict if a client subscribes to a marketing campaign or not. The raw data is obtained from UCI website. 
Data cleaning, model building and evaluating are done on the data.
Logistic regression, K_nearest neighbors, Support vector machine, Kernel SVM, Naive bayes, Decision tree classification, and Random tree classification models are considered.

Data source :  https://archive.ics.uci.edu/ml/datasets/Bank+Marketing

Data cleaning : 

The raw data from UCI was not prepared. I have cleaned the data, defined needed variables, and I have corrected the type of variables too.

EDA : 

I have used histograms, bar charts and pivot tables to gain some insight. Then I have used ANOVA (for numeric variables) and Chi_square (for categorical variables)
to find the variables that have the most correlations with the target variable which is variable Decision.

Model :

After finding the variables with the most correlations, I have started the machine learning phase of the project.
I have split the data to 75% train and 25% test. Then I have scaled the numeric variables.
Logistic regression, K_nearest neighbors, Support vector machine, Kernel SVM, Naive bayes, Decision tree classification, and Random tree classification models have been used.

Model performance : 

I have used confusion matrix and accuracy score to evaluate the performance of the different algorithms.

Kernel SVM model had the best performance and after that, it was Logistic regression model.




