# sentiment-analysis-on-twitter-dataset
we have downloaded a kaggle dataset whose link is: https://www.kaggle.com/youben/twitter-sentiment-analysis/data This datset is having train and test csv files that contains around 400k tweets. In this Dataset-  0  ->  negative tweet   1  ->  positive tweet  for easy computing, i have taken only 40k dataset from train csv file and perfrom the machine learning algorithm over that and found out the accuracy. we have also performed gridsearch for tuning the parameters for increasing accuracy.

various steps that are required to perform sentiment analysis on tweets can be:

1. import all the required libraries
2. import the dataset
3. remove the unnecessary columns if any and limit the dataset to 40k tweets
4. visualize the dataset
5. spilitting the dataset into train and test
6. clean the dataset and prepare for it NLP
7. prepare bag of words model and then TFIDF model
8. initialize the machine learning classifier and fit the train datset into it
9. evaluate the test dataset and make predictions and find out the accuracy
10. identify the parameters that tune will tune the model
11. perform grid search and re fit the train dataset into it
12. evaluate the tuned model and make predictions and find out the accuracy
13. compare the previous and new accuracy
