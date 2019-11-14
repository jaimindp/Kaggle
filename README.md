# Young People Survey Dataset Analysis

Analysis of dataset to explore the opinions of young people using Python and Scikit-learn.

EDA is performed to get an idea about the data contained in the survey. The large majority of the responses are rated on a scale of 1-5, this includes a range of subject matters such as music, fears, lifestyle, moods, spending habits and more.  There is categorical data in the questionaire relating things such as gender, if they're from a village or town, education level, amount of internet usage a day etc.

The demographics of respondents of the survey are investigated to see who they are and what can be inferred at a surface level. 

An investigation into the correlation of musical tastes find interesting results and this is visuallly represented. 

The dataset is then cleaned for machine learning, dealing by imputing missing values. Machine learning is used next to predict things about the respondents. Binary Logistic regression to predict gender is compared to the performance of SVM. Then multiclass logistic regression is done on categorical features and a prediction accuracy is obtained.
