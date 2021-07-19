# Adult income dataset_prediction_multiclass classification problem 

The training set and testing set come from a modified version of the dataset found in the following UCI repository: https://archive.ics.uci.edu/ml/datasets/adult. More information can be found there, including papers that have used this data set.

Instead of traditional binary classification problem, three classes are available for prediction.

Listing of attributes (Target Variables): >100K, 50-100K, <=50K.

The Order of work in this project are listed below,

1. Data Cleaning - Handling missing values, NaN values and outliers 
2. Exploratory Data Analysis - Univariate, Bivariate and multi-variate analysis
3. Feature selection - PCA technique to reduce the dimension of the input features
4. Model Implementation - five different models such as Logistic regression, SVC, Decision Tree, Random forest, KNN methods were used using 10 fold cross validation.
5. Model Fine tuning - Grid search CV is used for fine tuning the models generated above.
6. Model Testing - Testing the test dataset with the best model after fine tuning.


