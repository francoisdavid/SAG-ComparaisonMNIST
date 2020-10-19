# Francois David - Student ID: 20181906
# Bernouilli Naive Bayes Classifier

In order to run the code, you only need to run the BernouilliNaiveBayes.py file.
If one wants to change the proportion of the training / validation set, they can change the proportion on line 139:

```
# Needed to split the data into the training data and validation data.
proportionOfTrain = 0.80000
```

There are two classes defined in the program, one for the bag of word :bagOfWords and one for the Naive Bayes Classifier: BayesClassifier. 

Some components required for the Naive Bayes Classifier are in the main method. For example: Calculation of Priors, the conditional likelyhood.  

The predictions are put into a CSV file called naiveSubmission.csv. This binary classifier had 76.8 on the validation data set that we could prior to the end of the competition.

Most if not all of the important statements or methods are commented. 
