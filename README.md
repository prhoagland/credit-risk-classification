# Module 20 (Credit Risk Classification) Report

## Overview of the Analysis

The purpose of this analysis was to assess how well the logistic regression model classifies loans. Loans
which were classified as either "healthy" or "high-risk" were used to train the model. 75% of the loans were
used to train the model while the remaining 25% were used to test the model. The results of the test were then
compared to the actual loan classifications to assess how well the logistic regression model was trained.

## Results

* The model identified "healthy" loans with 100% precision and 99% recall for a perfect 1.00 F-Score
* The model indentified "high-risk" loans with 85% precision and 91% recall for an F-Score of 0.88
* The data set included 18,765 "healthy" loans and 619 "high-risk" loans
* Overall the model had 99% accuracy

## Summary

The numbers show that the model was nearly perfect at identifying "healthy" loans, with and F-Score of 1.00. However,
15% of the loans that the model identified as "high-risk" were actually "healthy" loans, which is not an acceptable
percentage. This is most likely due to the model being trained with far fewer "high-risk" loans than "healthy" ones
(18765 to 619). I therefore would not recommend using this model unless it is trained with a dataset that includes
substantially more "high-risk" loans to raise the precision at identifying those loans above 90%.