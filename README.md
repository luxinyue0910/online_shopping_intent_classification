# online_shopping_intent_classification
This is the ML classification project to explore ways to predict if a potential shopper will eventually make purchase, based on a few features

## Topic discussion

Online shopping is one of the most important aspects of revenue generation of a e-commerce company, like Amazon/Ebay. Company typically has lots of data of user footprint, including user personal information and user behavior pattern, and they want to use those info to predict if a user can eventually make a shopping event, which brings cash income to company.

The goal is to utilize features available to e-commerce, to predict if a shopping can happen or not. This question is essential since it will help online shopping companies to know which factors are most important to lead potential customers to spend money, and thus shopping companies can tune their marketing strategy. They can even use the prediction to allocate their merchantise/inventory before the shopping events happen, in order to optimize the delivery time and reduce transportation cost.

This question is by nature a `classification` problem, because the target variable we are interested in, is a binary (whether or not a user ends up with a shopping).

The data source comes from UC Irvine ML repository.
https://archive.ics.uci.edu/dataset/468/online+shoppers+purchasing+intention+dataset

Sakar,C. and Kastro,Yomi. (2018). Online Shoppers Purchasing Intention Dataset. UCI Machine Learning Repository. https://doi.org/10.24432/C5F88Q.

In this project, I would use **logistic regression** to predict the classification, while also explore hyper-parameter tuning and skewed dataset analysis.
