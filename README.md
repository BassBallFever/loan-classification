# Predicting Loan Defaults

We have been asked to come up with a model that will predict whether or not a loan will be paid in full and not defaulted on or charged off. We were given data on 50,000 loans that were issued by the bank.

The first thing we did was prepare the data, keeping just the loans that were paid off, defaulted on, or charged off. We removed variables that would have no effect on the outcome of the loan and variables that were redundant.

We used logistic regression to develop a model that could be used to predict whether a loan would be good or bad. This model was accurate in 78% of the cases it was tested on, including getting 98% of the good loans right. However, it only caught about 10% of the bad loans.
Predicting based on a model is a balancing act. The way to change the balance of our prediction is to modify the classification threshold. Basically, the classification threshold is used to determine whether a loan will be good or bad. By changing the threshold, we can change the accuracy of the prediction.

It turns out that our original threshold of 0.5 was the most accurate, but by changing the threshold to 0.7, we were able to increase the accuracy of predicting bad loans up to 48%, though the overall accuracy fell to 73%. The profits, however, reached their maximum with this threshold. This produced a 184% increase in profits over not using any model and a 52% increase over the most accurate model.

![](/images/loan1.jpg)
