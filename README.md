# Neural_Network_Charity_Analysis
Module 19 of Data Analytics Bootcamp

## Overview
Purpose of this analysis

Using the features in the provided dataset to create a binary classifier that is capable of predicting whether charity applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, we received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization.

Using Pandas and the Scikit-Learn’s StandardScaler(), I preprocessed the dataset in order to compile, train, and evaluate the neural network model. Using TensorFlow, I designed a neural network, or deep learning model, to create a binary classification model that can predict if an Alphabet Soup–funded organization will be successful based on the features in the dataset. Then, I compiled, trained, and evaluated my binary classification model to calculate the model’s loss and accuracy. Finally, using TensorFlow again, I attempted to optimize my model in order to achieve a target predictive accuracy higher than 75%. I was not able to achieve an accuracy higher than 75% in three attempts to do so.


## Results

Data Preprocessing
- What variable(s) are considered the target(s) for your model?
    "IS_SUCCESSFUL" was our target for the model, as we wanted to know if charity applicants were considered successful or not
- What variable(s) are considered to be the features for your model?
    The following variables were all considered as features for my model: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, INCOME_AMT, ORGANIZATION, SPECIAL_CONSIDERATIONS, STATUS, ASK_AMT. Each had to be modified from its original categorical format into integers so the model can process them.
- What variable(s) are neither targets nor features, and should be removed from the input data?
    EID and NAME were both dropped from the dataset as they were not targets nor features

Compiling, Training, and Evaluating the Model
- How many neurons, layers, and activation functions did you select for your neural network model, and why?
- Were you able to achieve the target model performance?
- What steps did you take to try and increase model performance?



## Summary