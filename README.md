# Deep-Neural-Network
Predicting Credit Card Fraudulent Transactions 

Credit Card Fraud Detection
Deep Learning Technique and detection
Fraud detection is really an important to any e-commerce store, and companies put a lot of money to prevention so single fraud can cost them a lot of money as well.
Today we are going to see how AI is trying to help solve this problem

Case Study
We are going to use out transaction history to build a fraud detection system.
We use a publicly available data set for these real credit card transactions that have been anonymized. This data contains over 300000 rows of transactions, all with their corresponding labels.
We have only numbers in the columns, as it has been anonymized, that means we don’t know which of the transactions attributes, such as the user’s IP location, how long he’s been one of our users…instead, we have numerical values that represent the same information.

OUR OBJECTIVE: is to build that classifier that given a new transaction, can tell us if it is fraudulent or not with a correspondent confidence. We are going to build both a deep learning network to try to do so, and apply more traditional ML algorithms such as Random Forest.

Which are our classes : ie “0” label , “1” label (classifier Is fraudulent)

ML and DL techniques complement each other…in our case we will be doing AB testing to see which mode performs best…so once we cover our deep neural network, we are going to start using machine learning using the sckit learn library  	

One of the biggest issues with this problem is that the vast majority of users will not be fraudulent.
This will make it harder for us to detect the underlying patterns in the information available. This will cause our dataset to be highly imbalanced, so we need to use different sample techniques and use different metrics.
It is estimated that only 0.1% of online transactions are fraudulent, but given the volume of transactions that occur every day, that means a lot of money 


