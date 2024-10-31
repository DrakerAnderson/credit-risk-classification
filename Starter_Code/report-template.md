# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
    The purpose of this analysis is to predict loan status.
* Explain what financial information the data was on, and what you needed to predict.
    I needed to single out loan status to run that as my y variable which remains seperate from the rest of the table (X) to compare it with the different tests.
* Describe the stages of the machine learning process you went through as part of this analysis.
    I was able to model and fit classification models, build training and test datasets for the learning analysis, build a confusion matrix and classification report
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).
    I used logisticregression which predicted the probability of a binary outcome, 
    train_test_split which splits the dataset in two subsets one for training and one for testing performance,
    confusion_matrix and classification_report which gives me the rundown of the accuracy of the tests of each model.

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.
*Machine Learning Model 1: 
    Accuracy: 0.99
    Precision:
    Class 0: 1.00
    Class 1: 0.84
    Recall:
    Class 0: 0.99
    Class 1: 0.94
Machine Learning Model 2:
    Accuracy: 0.95
    Precision:
    Class 0: 0.98
    Class 1: 0.75
    Recall:
    Class 0: 0.96
    Class 1: 0.85
Machine Learning Model 3:
    Accuracy: 0.97
    Precision:
    Class 0: 0.99
    Class 1: 0.80
    Recall:
    Class 0: 0.97
    Class 1: 0.88
Machine Learning Model 4:
    Accuracy: 0.96
    Precision:
    Class 0: 0.97
    Class 1: 0.78
    Recall:
    Class 0: 0.95
    Class 1: 0.84
Machine Learning Model 5:
    Accuracy: 0.94
    Precision:
    Class 0: 0.96
    Class 1: 0.70
    Recall:
    Class 0: 0.93
    Class 1: 0.80

as we can see model 1 has the highest accuracy.


* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.
the accuracy of model 1 is very high getting 99% accurate. perfectly accurate at precision in class 0 and very well balanced on recall.
## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best? 
    I recommend using model 1 since it has the highest accuracy. 

* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
    yes. the performance does depend on the problem we are trying to solve. class 0 is great for having high precision and taking out false positives and class 1 is good for identifying true positives which makes recall more important to look at.

If you do not recommend any of the models, please justify your reasoning.
    I don't recommend any of the other models since model 1 has the highest accuracy at this level of analysis.