# Young People Survey Dataset Analysis

Jupyter Notebook containing an analysis of the Kaggle dataset 'young people survey' using Python.

The goal is to explore at the survey response data to uncover interesting phenomena and to see if accurate predictions can be made about survey respondents based on their questionare answers. To do this, the data is explored, visualised and statistical measures obtained. Machine learning algorithms are used to make predictions on selected variables to see the accuracy with which factors about respondents can be predicted.

The analysis performed:
1. Exploration of data including analysis of demographics (height, weight and age) 
2. Correlation between musical genres
3. Predict of age using linear regression
4. Prediction of gender using binary Logistic Regression and Support Vector Machine algorithms
5. Prediction of survey categorical responses using categorical logistic regression


## Results

The correlation of height and weight was an interesting study, notably how splitting by gender significantly affected the correlation coefficient.

![Image description](https://github.com/jaimindp/Kaggle-young-people-survey/blob/master/figures/music_corr.png)

An analysis of Music taste allowed positive and negative correlations between music genres to be visualised. In addition, variation of responses with increasing age allows phenomena such as engagement with elections as of the voting age to be observed.

Machine learning was used to make predictions by dividing the data up into training and test sets. Linear regression gave a reasonably good prediction of age. Both Binary Logistic Regression and SVM to predict gender was very accurate.

![Image description](https://github.com/jaimindp/Kaggle-young-people-survey/blob/master/figures/roc.png)

Multiclass classification through Logistic regression proved to be less successful. This was attributed to the nature of the survey questions requiring vague and subjective responses.

There are many interesting features to this dataset and I have only begun to scratch the surface of what can be analysed. It is interesting to see how inferences can be made relating to individuals who took the survey. The predictions which are made using Machine Learning are powerful and this goes to show how simple data collection can be such a powerful tool. An interesting future study may be to investigate people's spending habits and what factors influence them most or look at the largest factors influencing belief in God.
