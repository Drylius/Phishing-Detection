# WEB URL Phishing Detection Project
This is a project for detecting a phishing website base on the URL.

## Dataset
The dataset used in this project was obtained from [Mendeley Data](https://data.mendeley.com/datasets/h3cgnj8hft/1). It is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/ ).

**Citation**
Tan, Choon Lin (2018), “Phishing Dataset for Machine Learning: Feature Evaluation”, Mendeley Data, V1, doi: 10.17632/h3cgnj8hft.1

### Dataset Modification
- Impute Missing values with the mean.

## Code
For this model I use the approach of combining three machine learning model such as logistic regression, random forest, and SVM using an ensemble method like voting classifier.

I used soft voting where unlike hard voting which instead of just counting votes, soft voting looks at how confident each model with their prediction.

## Result
Through this approach I achieved a prediction of 96.9% accuracy.