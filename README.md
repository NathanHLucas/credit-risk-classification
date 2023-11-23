# credit-risk-classification

# Module 20 Report

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

    The purpose of this analysis is to create a machine learning algorithm that can sort through credit applications to determine which should be approved and declined. The first step is to read and clean the data, then split the data into training and testing sets. At this point, you can either fit the regression model to the training data and then test it using the test set, or rebalance the training data and then fit and test.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models. Helpful Link:https://www.statology.org/sklearn-classification-report/

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
        Accuracy: 95.2%
        Precision: 85%
        Recall: 91%


* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
        Accuracy: 99.3%
        Precision: 84%
        Recall: 99%

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best? 
    They both perform differenly, but I would say that the first model (without rebalancing) performs better based on the false positive ratio.
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? ) 
    Yes, performance does depend on the problem at hand. In this example, it depends one what the profit and revenue numbers look like. Some follow-up questions to ask would be "What is the loss per account that is approved that should not have been?" and "What is the revenue that the firm lost out on from accounts that should have been approved but were not?"

If you do not recommend any of the models, please justify your reasoning.
    It is really hard to say without more revenue/loss information. 

