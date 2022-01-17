# Credit_Risk_Analysis
Supervised Machine Learning

# index
* Overview of project

* Deliverables (looking ahead)
 - Deliverable 1
 - Deliverable 2
 - Deliverable 3
 
* Beginning of Project
 - Deliverable 1
 
# Overview of Project
Jill commends you for all your hard work. Piece by piece, you’ve been building up your skills in data preparation, statistical reasoning, and machine learning. You are now ready to apply machine learning to solve a real-world challenge: credit card risk.

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. Jill asks you to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

# Deliverables (looking ahead)

# Deliverable 1: Use Resampling Models to Predict Credit Risk
* An accuracy score for the model is calculated (7.5 pt)
* A confusion matrix has been generated (7.5 pt)
* An imbalanced classification report has been generated (15 pt)
 
# Deliverable 2: Use the SMOTEENN Algorithm to Predict Credit Risk
* An accuracy score for the model is calculated (5 pt)
* A confusion matrix has been generated (5 pt)
* An imbalanced classification report has been generated (5 pt)

# Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk

* The BalancedRandomForestClassifier algorithm does the following:

- An accuracy score for the model is calculated (2.5 pt)

- A confusion matrix has been generated (2.5 pt)

- An imbalanced classification report has been generated (5 pt)

- The features are sorted in descending order by feature importance (5 pt)

* The EasyEnsembleClassifier algorithm does the following:

- An accuracy score of the model is calculated (2.5 pt)

- A confusion matrix has been generated (2.5 pt)

- An imbalanced classification report has been generated (5 pt)

# Deliverable 4: A Written Report on the Credit Risk Analysis (README.md)

* There is a title, and there are multiple sections (2 pt)
* Each section has a heading and subheading (2 pt)
* Links to images are working, and code is formatted and displayed correctly (2 pt).
* The purpose of this analysis is well defined (4 pt)
* There is a bulleted list that describes the balanced accuracy score and the precision and recall scores of all six machine learning models (15 pt)
* There is a summary of the results (2 pt)
* There is a recommendation on which model to use, or there is no recommendation with a justification (3 pt)


# Beginning of Prtoject

# Deliverable 1
Using your knowledge of the imbalanced-learn and scikit-learn libraries, you’ll evaluate three machine learning models by using resampling to determine which is better at predicting credit risk. First, you’ll use the oversampling RandomOverSampler and SMOTE algorithms, and then you’ll use the undersampling ClusterCentroids algorithm. Using these algorithms, you’ll resample the dataset, view the count of the target classes, train a logistic regression classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report.

- An accuracy score for the model is calculated (2.5 pt)

 ![image](https://user-images.githubusercontent.com/89880015/149815770-4570d558-53cc-43bf-9e56-f9a6fa4cc87e.png)
 
- A confusion matrix has been generated (7.5 pt)

![image](https://user-images.githubusercontent.com/89880015/149815906-0f811f02-3de5-4aa8-8c71-89beacce2869.png)

- An imbalanced classification report has been generated (15 pt)

![image](https://user-images.githubusercontent.com/89880015/149816098-39850d3a-9384-4894-ad94-b3dc98a30d8c.png)

# Deliverable 2

An accuracy score for the model is calculated (5 pt)

![image](https://user-images.githubusercontent.com/89880015/149816537-65374739-7ac0-4dc8-b0ad-c9acce6b8649.png)

A confusion matrix has been generated (5 pt)

![image](https://user-images.githubusercontent.com/89880015/149816805-3d62a112-5e8e-4d09-9b45-be6827b50e09.png)

An imbalanced classification report has been generated (5 pt)

![image](https://user-images.githubusercontent.com/89880015/149816975-1ba95d1c-7877-48e8-9323-8f1c134ea0d8.png)

# Deliverable 3

- An accuracy score for the model is calculated (2.5 pt)

![image](https://user-images.githubusercontent.com/89880015/149817198-7aa4cafa-b9e1-4fb7-9f73-b35694c963c6.png)

- A confusion matrix has been generated (2.5 pt)

![image](https://user-images.githubusercontent.com/89880015/149817426-b000e61f-4891-4573-b812-245fad063a4d.png)

- An imbalanced classification report has been generated (5 pt)

![image](https://user-images.githubusercontent.com/89880015/149817498-ced0bf7e-6076-4383-b7f5-8db409560f94.png)

- The features are sorted in descending order by feature importance (5 pt)

* The EasyEnsembleClassifier algorithm does the following:

- An accuracy score of the model is calculated (2.5 pt)

![image](https://user-images.githubusercontent.com/89880015/149817588-4f883fa9-4e64-4bdb-9836-79919d11e02c.png)


- A confusion matrix has been generated (2.5 pt)

![image](https://user-images.githubusercontent.com/89880015/149817632-5b83c001-a91c-432d-a249-841e030b430c.png)


- An imbalanced classification report has been generated (5 pt)

![image](https://user-images.githubusercontent.com/89880015/149817668-a849bc38-10a5-4660-8bb9-ffc79f846548.png)

