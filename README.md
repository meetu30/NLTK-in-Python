# NLTK-in-Python
Purpose - to learn the use of NLTK packageand text analytics in Python
Text Analytics in Python
Dataset - reviewsAll_Apple.csv
Columns - ReviewerID, ProductId(asin), Make, Ttle, reviewerName, Helpful, ReviewText, Overall, Summary, reviewDate
Columns of Interest - reviewText and Overall (rating from 1-5)
Business Problem - to predict the High/Low rating (or sentiment) based on reviewText
Various steps - 
Read the dataset using pandas
Clean the data - remove punctuations, remove stop words, stemming and lemmetizing operations on Text data
Vectorize the data to prepare it for building the model using countVectorizer and Tf-idf Vecorizer
Feature Engineering (optional)
Applying Machine Learning algorithms - Random Forest classifier(cross validation. hold out method and Grid search method)
