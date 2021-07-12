# Credit_Risk_Analysis

## Overview of the analysis: 

The purpose of this analysis is well defined (4 pt)
Jill commends you for all your hard work. Piece by piece, you’ve been building up your skills in data preparation, statistical reasoning, and machine learning. You are now ready to apply machine learning to solve a real-world challenge: credit card risk.

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. Jill asks you to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.



## Results: 

- RandomOverSampler

<img width="141" alt="Screen Shot 2021-07-11 at 10 12 01 PM" src="https://user-images.githubusercontent.com/80495710/125220633-1083a700-e295-11eb-80b9-7a16e70bc4f2.png">

  - balanced accuracy score: 
  - recall score(TPR):
  - precision score:

- SMOTE

<img width="138" alt="Screen Shot 2021-07-11 at 10 12 36 PM" src="https://user-images.githubusercontent.com/80495710/125220687-23967700-e295-11eb-832d-6a419bee4486.png">

  - balanced accuracy score: 
  - recall score:
  - precision score:

- ClusterCentroids

<img width="133" alt="Screen Shot 2021-07-11 at 10 13 49 PM" src="https://user-images.githubusercontent.com/80495710/125220880-5476ac00-e295-11eb-9759-5a493188ecda.png">

  - balanced accuracy score: 
  - recall score:
  - precision score:

- SMOTEENN

<img width="135" alt="Screen Shot 2021-07-11 at 10 14 34 PM" src="https://user-images.githubusercontent.com/80495710/125220930-67897c00-e295-11eb-8e89-cda683978bba.png">

  - balanced accuracy score: 
  - recall score:
  - precision score:
- BalancedRandomForestClassifier

<img width="136" alt="Screen Shot 2021-07-11 at 10 09 52 PM" src="https://user-images.githubusercontent.com/80495710/125220474-c8648480-e294-11eb-82a8-39bc7de01fa7.png">

  - balanced accuracy score: 
  - recall score:
  - precision score:

- EasyEnsembleClassifier

<img width="141" alt="Screen Shot 2021-07-11 at 10 10 47 PM" src="https://user-images.githubusercontent.com/80495710/125220517-e16d3580-e294-11eb-9830-9640bd9228cc.png">

  - balanced accuracy score: 
  - recall score:
  - precision score:

Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
There is a summary of the results (2 pt)
There is a recommendation on which model to use, or there is no recommendation with a justification (3 pt)

