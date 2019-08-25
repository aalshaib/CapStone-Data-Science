# CapStone-Data-Science

# Table Of Contents:
Installation
Project Motivation
File Descriptions
Results
Licensing, Authors, and Acknowledgements
# Installation:
No need to install any necessary libraries to perform this project. the code can be run with using Python version 3.6

# Project Motivation:
This project is,  to create a python program that could rate the reviews of  restaurants
based on the number of stars. It could be between 1-5 depending upon the performance of the restaurant. In this 
project the program will be able to classify the reviews that given by a customer on the 'yelp' using a SVM classifier and Random Forest Classifier.

#the goal is see which classifier and approach that can gives us higher accuracy.

# The steps of the program:

1. The program will read the files and import the dataset.
2. It will store the list of text reviews  in texts list and star rating in stars list
3. It will store the ngrams as the user desire.
4. It will call the  balance_dataset method that will balance the data according to the least number of reviews for 
    any star rating.
5. It will break the words into single tokens and tri-grams then it will vectorize them.
6. It will build up the vocabulary from all the reviews and turns each individual text into a matrix of numbers
7. then, the SVM classifier and Random Forest Classifier model are created to be trained on 80% of the data.
8. The classifier model is then checked and run on remaining test data.

# the task approaches are:
1. Scenario 1 : consider each star rating individually. 
2. Scenario 2: consider star rating 1 & 2 as negative and 4 & 5 as positive  and 3 as neutral
3. Scenario 3: consider star rating 1 & 2 as negative and 3 &4 & 5 as positive
4. Scenario 4: consider star rating 1 & 2 & 3 as negative and 4 & 5 as positive
5. Scenario 5: consider star rating 1 & 2 as negative and 4 & 5 as positive  and get rid of rating star 3



# File Descriptions:
there are one python notebook and one yelp.csv that has 10000 rows and 2 columns that can be perform on these classification and approaces.

# Results:
getting the results of  these five Scenarios  can help us to commit and relay in one approach that can classify reviwes as a positive or negative.

Scenario 4: was the best one. it gives me the highest accuracy among all the 5 approaches. it was 88%
also, SVM performs better than Random Forest classifier in all the approaches.

# Licensing, Authors, Acknowledgements:
must give credit to Omkar Sabnis and Kaggle for the dataset. here is the link of the data: https://www.kaggle.com/omkarsabnis/yelp-reviews-dataset, also we can find the description of the data.

feel free to use the code as you like
