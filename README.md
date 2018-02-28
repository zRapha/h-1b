# Machine Learning Engineer Nanodegree - Capstone Project

## Predicting the outcome for H-1B Visa eligibility in the U.S. 

Every year hundreds of thousands of international workers apply for H-1B non-immigrant visas in the United States. In order to be able to qualify for worker H1-B visas, a person needs to have a job offer from a U.S. based company. This is also the kind of visa usually requested by international students pursuing higher education in the country. This study aims to train a classifier based on features of the dataset to be able to predict whether a given request would be granted eligibility to the H-1B program. Given the number of people requesting visas every year - and the likelihood to increase over the next years despite political pressure - it would be interesting to analyze some of the existing data and provide a model that could help to understand successful over non-successful applications. This is handled as a multi-class classification problem as we have to identify one among different solutions, however the number of outputs used will be discussed given the fact that some of these results are more influenced by external factors and do not have a significant impact on the results. To approach this problem three different classifiers are trained and compared to identify the five most important features to tackle this problem. While prevailing wage is the highest weighted features as expected, part-time positions weight stronger than expected and the worksite does not necessarily affects the outcome of the application. Finally, a Logistic Regression classifier proved to be the best option among those analyzed to process this data considering time needed to train and predict as well as output produced.

Code available on Kaggle notebook too: 
https://www.kaggle.com/elraphabr/predicting-outcome-for-h-1b-eligibility-in-the-us 
