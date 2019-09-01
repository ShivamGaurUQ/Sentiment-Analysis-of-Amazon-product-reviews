# Product review and sentiment analysis


The project uses opinion mining to analyse customer reviews about mobile phones sold on Amazon.com. The objective is to develop a prediction system that can be used to classify an input customer review of a mobile phone as a good review or a bad one.


The prediction system uses Ensemble Classifier to classify the input reviews. We tried to other classification models such as SVM, Logistic Regression, Multinomial Naïve Bayes, Bernoulli NB, Decision Tree and k-NN but found out that Ensemble Classifier had the best accuracy. The dataset used consists of more than 400,000 reviews from amazon’s unlocked mobile phone category and is available at www.kaggle.com.

Set up Guide for Project

1. CountVector_Step_By_Step_Implementation.ipynb: This file demonstrates step by step implementation of the various steps involved in implementing the project. The text transformation uses Count Vectorization Technique.
2. TFIDF_Step_By_Step_Implementation.ipynb: This file demonstrates step by step implementation of the various steps involved in implementing the project. The text transformation uses TFIDF Technique.
The objective of the above two files is to explain the process flow of various stages in the software execution and the code used to implement those steps.
3. Sentimental_Analysis_OfCustomerReviews_System_Using_Count_Vectorization_Technique.ipynb: This file consists of the code to run the software and uses Count Vectorization Technique for text transformation. The software consists of GUI for easy usability and allow users to predict the rating of new review, analyze and compare different classification models based on their accuracy, precision, recall and f-measure.
4. Sentimental_Analysis_OfCustomerReviews_System_Using_TFIDF_Technique.ipynb: This file consists of the code to run the software and uses TFIDF Technique for text transformation. The software consists of GUI for easy usability and allow users to predict the rating of new review, analyze and compare different classification models based on their accuracy, precision, recall and f-measure.
