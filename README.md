# Credit_Risk_Analysis

## Overview of the analysis: 

The purpose of this analysis is well defined (4 pt)
Jill commends you for all your hard work. Piece by piece, you’ve been building up your skills in data preparation, statistical reasoning, and machine learning. You are now ready to apply machine learning to solve a real-world challenge: credit card risk.

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. Jill asks you to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.



## Results: 

Balanced Accuracy Score is how close the predicted number of people to be in either credit clasification is to the *true* number of people in that classification. 

Recall score describes how many people who actually have low or high credit are correctly classified. Each of them is over 0.6, but the BalancedRandomForestClassifier and EasyEnsembleClassifier each had recall scores between 0.7 and 0.9 (Proportion of positives that are picked up). 

Precision tells us how reliable the positive classification of low or high credit risk is. For each, we are quite confident in the clasification of the low risk credit individuals (Proportion of positives that are correct). 


- RandomOverSampler

<img width="397" alt="Screen Shot 2021-07-11 at 10 17 40 PM" src="https://user-images.githubusercontent.com/80495710/125221176-dc5cb600-e295-11eb-9493-7b5b6754e322.png">


  - balanced accuracy score: 0.640
  - recall score: 0.62 (Low_Risk) / 0.66 (High_Risk) / 0.62 (Total)
  - precision score: 1.00 (Low_Risk) / 0.01 (High_Risk) / 0.99 (Total)




- SMOTE

<img width="402" alt="Screen Shot 2021-07-11 at 10 18 26 PM" src="https://user-images.githubusercontent.com/80495710/125221233-eed6ef80-e295-11eb-9c60-bce128c9077c.png">


  - balanced accuracy score: 0.651
  - recall score: 0.69 (Low_Risk) / 0.61 (High_Risk) / 0.69 (Total)
  - precision score: 1.00 (Low_Risk) / 0.01 (High_Risk) / 0.99 (Total)




- ClusterCentroids

<img width="397" alt="Screen Shot 2021-07-11 at 10 18 53 PM" src="https://user-images.githubusercontent.com/80495710/125221279-ff876580-e295-11eb-8e6e-3d285859bbca.png">


  - balanced accuracy score: 0.651
  - recall score: 0.40 (Low_Risk) / 0.69 (High_Risk) / 0.40 (Total)
  - precision score: 1.00 (Low_Risk) / 0.01 (High_Risk) / 0.99 (Total)





- SMOTEENN

<img width="401" alt="Screen Shot 2021-07-11 at 10 19 23 PM" src="https://user-images.githubusercontent.com/80495710/125221327-12019f00-e296-11eb-9d62-c0dce15147fb.png">


  - balanced accuracy score: 0.545
  - recall score: 0.60 (Low_Risk) / 0.64 (High_Risk) / 0.60 (Total)
  - precision score: 1.00 (Low_Risk) / 0.01 (High_Risk) / 0.99 (Total)



- BalancedRandomForestClassifier

<img width="318" alt="Screen Shot 2021-07-11 at 10 20 16 PM" src="https://user-images.githubusercontent.com/80495710/125221482-407f7a00-e296-11eb-9068-7157a29fd21b.png">


  - balanced accuracy score: 0.789
  - recall score: 0.87 (Low_Risk) / 0.70 (High_Risk) / 0.87 (Total)
  - precision score: 1.00 (Low_Risk) / 0.03 (High_Risk) / 0.99 (Total)



- EasyEnsembleClassifier

<img width="320" alt="Screen Shot 2021-07-11 at 10 20 31 PM" src="https://user-images.githubusercontent.com/80495710/125221494-44130100-e296-11eb-9710-bc7952933abc.png">


  - balanced accuracy score: 0.932
  - recall score: 0.94 (Low_Risk) / 0.92 (High_Risk) / 0.94 (Total)
  - precision score: 1.00 (Low_Risk) / 0.09 (High_Risk) / 0.99 (Total)

Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
There is a summary of the results (2 pt)
There is a recommendation on which model to use, or there is no recommendation with a justification (3 pt)

