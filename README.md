# Young People Survey Dataset Analysis

Jupyter Notebook containing an analysis of the kaggle dataset young people survey using Python.

The goal is to explore at the survey response data to uncover interesting phenomena and to see if accurate predictions can be made about survey respondents based on their questionare answers. To do this, the data is explored, visualised and statistical measures obtained. Machine learning algorithms are used to make predictions on selected variables to see the accuracy with which factors about respondents can be predicted.

The analysis performed:
1. Exploration of data including analysis of demographics (height, weight and age) 
2. Correlation between musical genres
3. Predict of age using linear regression
4. Prediction of gender using binary Logistic Regression and Support Vector Machine algorithms
5. Predict of survey categorical responses using categorical logistic regression

## Results

1. 
Exploratory Dataset Analysis initially gives a view the survey questions and responses. The large majority of responses are rated on a scale of 1-5, this includes a range of subject such as music, fears, lifestyle, moods, spending habits and more. Other responses are categorical relating things such as gender, if they're from a village or town, education level, amount of internet usage a day and so on.

2.
An investigation into the correlation of musical tastes find interesting results and this is visuallly represented. 

The dataset is then cleaned for machine learning, dealing by imputing missing values. Machine learning is used next to predict things about the respondents. Binary Logistic regression to predict gender is compared to the performance of SVM. Then multiclass logistic regression is done on categorical features and a prediction accuracy is obtained.
