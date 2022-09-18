# Overview

There are two main categories of datasets I ran into:
* *True datasets that had super opaque variables:* in these cases, the data represented true transactions.
However, the variables were masked to protect consumer privacy.

* *Synthetic datasets with super clear variables*
In these cases, the data was generated synthetically.
The variables appeared easy to work with.
However, due to the synthetic nature of the data, many of the comments on the Kaggle discussion pages stated that the data was unrealistic.

I am using the IEEE-CIS dataset for the following reasons:
* This is a real dataset, which means that it will imitate actual behavior.
* It has a lot of variables, which can be used for multivariate analysis.
* The variables were more clearly labeled than the other real data set I encountered (which only used PCA vectors).

The tradeoffs are the following:
* The input variables are somewhat opaque, which the organization did intentionally to protect consumer privacy.


# Datasets Deep Dive

## Machine Learning Group Credit Card Anonymized Data

This dataset has a total of 284,807 transactions, of which 492 were fraudulant.
The transactions took place over two days in Europe in September 2013.

The input variables are vectors from a PCA algorithm.
The source states that they cannot provide further information due to privacy reasons.

This feels like not a great dataset to use.

More info in source (a).

## Synthetic Financial Data Sets for Fraud Detection

This dataset is synthetically built to address the lack of open source datasets in the Fraud Detection space.
The dataset contains 6,353,307 synthetic transactions.
There are 11 input variables about both the sender and recipient of the transaction.

This data could be fun to play with because it is clear what all of the variables are.
It is, however, synthetic data and it has a small number of input variables.

More info in source (c).

## Credit Card Fraud

This dataset contains 1,000,000 records with some information on how the transaction compares to the user's base behavior (ex: distance from home, how does it compare to previous transactions) in addition to some basic metadata on the transaction (ex: did the card use a chip).

It is unclear where this data came from, which makes it suspect, and there is a limited number of variables.
The Kaggle space has several discussions about how the fact that this is likely a synthetic dataset makes it so that the models they create are unrealistically good.
But the variables are clear.

More info in source (d).

## IEEE-CIS Fraud Detection

This dataset contains information on transactions and on the associated accounts.
There are several hundred input variables that are not very meaningful.
Combined, there are around ~700k records (they are divided into a training and test set).

This is real data with tons of variables, which could be useful for doing multivariate analysis.
The only downside is that the input variables are not super clear.
