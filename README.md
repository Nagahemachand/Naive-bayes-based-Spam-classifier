# Naive-bayes-based-Spam-classifier

In this project, we'll focus on the data mining aspects by applying Naive Bayes as classifier for spam classication.

Datasets for experimentation: spam.csv

The dataset contains 5,574 messages tagged according to ham (legitimate) or spam. In this experiment, we will learn about text features, how to convert them into matrix form, and the Naive Bayes algorithm.

Answer the following questions:
1. How many records are there? What's the distribution of the “label” class? Is it skewed?
2. How many unique SMS messages are there in the dataset? What is the SMS message that occurs most frequently, and what is its frequency?
3. What is the maximum and minimum length of SMS messages present in the dataset? Plot the histogram of the length of SMS messages with bin sizes 5,10,20,50,100,200. What do you perceive after examining the plots?
4. Plot the histogram of the length of SMS messages for each label separately with bin sizes 5,10,20,50 i.e., histogram of the length of all ham SMS messages and histogram of the length of all spam SMS messages. What do you perceive after examining the plots?
5. In the Bag of words approach, we convert all strings into lower cases. Why did we do that, and why is it important? Can we convert all strings into the upper case and still fulfill our original goal?
6. What does CountVectorizer achieve? What will happen if we set stop words = "english"? Give five examples of stop-words in English.
7. Given a dataset, how do we generate a document-term matrix? Do we first generate a document-term matrix and then separate the matrix into train/test, or first separate the data into train/test and then generate a document-term matrix based on the training dataset and afterward generate a matrix for the test set? Explain your reasoning.
8. Using the bag of words approach, convert documents = ['Hi, how are you?', 'Win money, win from home. Call now.', 'Hi., Call you now or tomorrow?'] to its document-term matrix.
9. How many features are created while making a document-term matrix for the SMS dataset? Can you think of a method to reduce the number of features? List the pros and cons of the method.
10. For our input dataset, which Naive Bayes model should we use, Gaussian Naive Bayes or Multinomial Naive Bayes? Explain your reasoning. Report accuracy, precision, recall, and F1 score for the spam class after applying the Naive Bayes algorithm.
 
The solutions for these questions can be found in the folder: Solutions_Naive Bayes_Spam Classification
