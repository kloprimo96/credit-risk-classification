# credit-risk-classification

In this section, describe the analysis you completed for the machine learning models used in this Challenge. 

The purpose of this analysis was to take loan application data and use autmoated prediction models to determine the ratio of healthy to non-healthy loans within the data set. It was also important to see the precision rate of the two prediction models we used in this exercise.
The value counts found within the analysis were the rows of data predicted or in this case loan applications which were ran through these prediction models. These values were then used in the machine learning process which went through labeling (or determing which data from the dataset to use), using the labeling with train_tes_split to classify the data values and categories, and using prediction models to make predictions on categories. I found the resampling (RandomOverSampler) regression model the mot interesting due to the model being able to make more predictions on arrays of data based on the original trends found. I thought this was particualrly useful in this data set being that the models categorized most loan applications as healthy loans therfore creating a bias or underrepresented data array. Both the liner regression model and regression model fit with resmpling hit a 99% average accuracy rate. 


