# Data_Mining
Data Mining Course CSCE5380


These assignments are completed in due with the course CSCE# 5380 ( Data Mining). 
Assign2_Task1 - 

Classification algorithms--Naïve Bayes (NB) and Random Forest (RF)--on the Image Segmentation data.

Sub task1: Cross-validation

Naïve Bayes classifier by 3 different numbers of folds (3 different runs by 6, 9, 14 folds in each run respectively).

Random Forest classifier by selecting the same number of folds selected for the Naïve-Bayes classsifer (used 6, 9, 14 folds for Naïve-Bayes, use the same 3 numbers for Random Forest).

    Do the number of folds have any correlation with the number and percentage of correctly classified instances within the same model (For example, 6 folds and 9 folds in NB and RF respectively)? Explain the results.

    Do the same number of folds when applied to different models have any effect on the number and percentage of correctly classified instances (For example, 6 folds and 9 folds in NB and RF)? Explain the results.

    Select 1 set of results generated for each classifier. For example, if you performed a test by selecting 9 folds, select the results you obtained for 9 folds for both–NB and RF. Considering all classes in the dataset; calculate the accuracy and error rate for the results of NB and RF. Show the formula and explain the steps in calculating the accuracy and error-rate. Hint: compute the values of the confusion matrix first.

Problem 2: Percentage Split

Run the NB classifier by selecting 3 different percentages of training data (for example, run 3 different runs by selecting a testing-training split of 42%-58%, 54%-46%, 65%-35%, etc. in each run).

Run the RF classifier by selecting the same set of training set ratios selected for the NB classifier. Does the percentage of training data affect the classifier accuracy?

    Does the percentage of training data affect the classifier accuracy? How and why?

    If the same percentage of testing data is used for both classifiers (e.g. 42% for both NB and RF, does the classification accuracy vary from one classifier to another? Why?

    Select any one set of results generated for each classifier. For example, if you performed a test by selecting 42% training data, select the results you obtained for 42% for both – NB and RF. Considering all classes in the dataset, calculate the accuracy and error rate for the results of NB and RF. Show the formula and explain the steps in calculating the accuracy and error-rate.

Assign2_Task2 -

Run two classification algorithms--Naïve Bayes (NB) and Random Forest (RF)--on the Thyroid disease records.
Problem 3: Cross-validation

Run each of the NB and RF classifier once by a certain value for number of folds for cross-validation (e.g. 6 folds).

For the results obtained, generate a ROC curve for the class “primary-hypothyroid” for both the classifiers.
Problem 4: Percentage Split

Run each of the NB and RF classifier once by selecting a certain percentage of training data (e.g. 42%).

For the results obtained, generate a ROC curve for the class “secondary-hipothyroid” for both the classifiers.


Assign2_Task3 -

Run the Decision Tree classifier on Horse Colic database, Pima Indians Diabetes Database, and Thyroid disease records with a 70% and 30% split of training and test data respectively.
Problem 5:

Calculate and report the error-rate and accuracy for each of the datasets. Which of the 3 datasets has the highest number of correctly classified instances?

Which of the three datasets has the smallest and largest decision trees? Explain why you think the size of the decision trees varies.
