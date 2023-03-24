# Module-Challange-12

## Write a Credit Risk Analysis Report

For this section, you’ll write a brief report that includes a summary and an analysis of the performance of both machine learning models that you used in this challenge. You should write this report as the `README.md` file included in your GitHub repository.

Structure your report by using the report template that `Starter_Code.zip` includes, and make sure that it contains the following:

1. An overview of the analysis: In this analysis we are trying to figure out the creditworthiness of borrowers

2. The results: Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of both machine learning models.
a) Balanced accurecy score for original and oversampled is almost similar but the oversampled data seems to be more accuracy with Accuracy score 1: 0.9938093272802311 as compared to Original sample which is 0.9520479254722232
b) High Risk loan (1) looks identical for precision which is 0.85 for oversampled data and original data is 0.84.Recall number seems to be little bit higher in the original which is 0.99 as compared to oversampled data which 0.91.
c) The healthy loan "0" is identical for both the oversampled and original data using the logistic regression model. Precision, Recall and f1 values are the same.


3. A summary: Summarize the results from the machine learning models. Compare the two versions of the dataset predictions. Include your recommendation for the model to use, if any, on the original vs. the resampled data. If you don’t recommend either model, justify your reasoning.
I think both the data seems to be almost same but oversampled data seems to provide more accurate result.
