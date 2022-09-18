# Overview

This project will focus on detecting fraudulant transactions charged to credit or debit cards.

Payment fraud occurs "when deceptive methods are used to transfer money against the payor’s will to an illegitimate beneficiary’s account" (2).
Payment fraud typically occurs when an unauthorized party obtains access to the victim's payment information, such as by stealing the victim's credit card information or by using the victim's personal information to open an account.
Over the last several years, data breaches and advances in technology have led to an increase in payment fraud, which can devastate victims.

Financial institutions typically have processes and technology to identify and block potentially fraudulant transactions in real time.
As technology has advanced to make fraud easier to commit, access to data and technological increases have also allowed statisticians to develop a more complex understanding of how to build models that can identify fraudulant transactions.
Statisticians can build models that can use signals such as location of the transaction, frequency of the transaction, profile of the merchant, profile of the customer, and more to identify whether a transaction is fraudulant.
Increased access to data allows statisticians to build more variables into their models than they were able to in the past.

When financial institutions implement fraud detection algorithms in their products, it is essential to get them right.
If a fraudulant transaction is not identified as fraudulant, then the customer loses the money used to make that transaction.
The financial institution must go through processes to identify whether this transaction is in fact fraudulant and then compensate the customer for the transaction, which is money that the financial institution may never recoup.
The consequences of fraudulant payments can be devastating to customers, who may lose significant amounts of money and then have to jump through many hoops to ever get it back.

If a financial institution blocks a non-fraudulant transaction, then this is a poor user experience for the customer because the customer's payment will be declined, which may cause the customer to choose to switch to a different financial institution or otherwise use their account less frequently.
Additionally, fraud detection models and operations are subject to high levels of scrutiny by regulatory bodies.
Further discussion on balancing customer experience and fraud risk in source (9).

# Statistical Methods

Statisticians use many different statistical methods to determine whether a transaction is fraudulant.
Below is a summary on a few of them.
Methods from the list in source (3).

## Neural Networks

Neural Networks are one of the most powerful statistical methods used to detect fraud.
They represent biological learning systems.

"It is structured as a directed graph with many nodes (processing elements) and arcs
(interconnections) between them.
The node computes a weighted sum of its inputs and generates an output.
This output then becomes an input to other nodes in the network.
The process continues until one or more outputs are generated."

I do not currently understand NNs well enough to explain them well and have not looked into sources.

## Rule Induction

Decision trees are made to route datapoints through a list of decisions that will eventually lead to an output.

Source (4) has more information.

## Expert System

Expert systems use artificial intelligence to replicate a human expert's decision making processes.
They use a knowledge base that ties data inputs to a target output and then makes a recommendation based on that knowledge base.

Source (5) has more information.

## Case Based Reasoning

Case based reasoning relies on pulling previous experiences from memory to obtain an output for a new data point.

Source (6) has more information.

## Genetic Algorithm

Similar statistical method to genetics and evolution.
Input variables are optimized to determine what the outcome will be.

Source (7) has more information.

## Inductive Logic Programming

Inductive logic programming uses trends across specific data points to build generalized rules.

Source (8) has more information.


## Regression

Regression takes input variables to make an algebraic calculation of what the outcome variable may be.