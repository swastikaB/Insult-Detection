#Insult-Detection
This project demonstrates how Machine Learning can be used in conjucntion with Natural Language Processing to detect insults in social Commentary. This is part of an academic course project and is limited in scope.

Graph Lab create tool has been used for this project to visualize the data. Scikit, Numpy and NLTK libraries are required to run the programs. Each file is a standalone program. 

All the programs follow the same steps of
-- Loading the training data file and test data file. ( 2 separate files have been used. Cross validation is performed on the training data. The learned model is then tested on a completely new set of test data.)
-- Preprocessing: Applying tokenization, removing punctuation and stop words and, stemming. 
-- Feature Extration: Bag of words(unigrams, bigrams, n- grams) is the feature used in files Logistic Regression, SVM and Naive Bayes. "GoodBadWrdRatio" program makes use of the ratio of good words and ratio of bad words as features. Logistic regression and SVM have been applied on this data.
-- Cross Validation: I have used scikit's crossval function to calculate the cross validation accuracy on the training data.
-- Test accuracy: The learned model is then fit on the test data (different from training data file) and its accuracy is calculated.
