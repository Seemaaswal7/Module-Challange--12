
# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
In this analysis we are trying to figure out the creditworthiness of borrowers

* Explain what financial information the data was on, and what you needed to predict.
We had loan status, total debt and if there were any derogatory remarks or not

* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
loan status= Y variable and Rest of the table columns = X variable

* Describe the stages of the machine learning process you went through as part of this analysis.
Data Pre-processing step.
Fitting Logistic Regression to the Training set.
Predicting the test result.
Test accuracy of the result(Creation of Confusion matrix)

* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).
Logistic regresion is being used for statistical analysis method to predict the binary outcome

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.using orginal data

                   pre       rec       spe        f1       geo       iba       sup

          0       1.00      0.99      0.91      1.00      0.95      0.91     18765
          1       0.85      0.91      0.99      0.88      0.95      0.90       619

avg / total       0.99      0.99      0.91      0.99      0.95      0.91     19384


* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.Using oversampled data
  
    pre       rec       spe        f1       geo       iba       sup

          0       1.00      0.99      0.99      1.00      0.99      0.99     18765
          1       0.84      0.99      0.99      0.91      0.99      0.99       619

avg / total       0.99      0.99      0.99      0.99      0.99      0.99     19384


## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
Both the model gave a precision of 1 for for healthy loan and little bit descrepany on the high risk loan for oversampled it's 84% which is 1% less than orginal sample.

* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
I think it is important to predict both. logistic regression predicts the probability of an event or class that is dependent on other factors. Thus the output of logistic regression always lies between 0 and 1

If you do not recommend any of the models, please justify your reasoning.