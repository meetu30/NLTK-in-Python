# NLTK-in-Python
Purpose - to learn the use of NLTK package and text analytics in Python
Text Analytics in Python
Dataset - reviewsAll_Apple.csv - contains Amazon reviews for Apple products
Columns - ReviewerID, ProductId(asin), Make, Title, reviewerName, Helpful, ReviewText, Overall, Summary, reviewDate
Columns of Interest - reviewText and Overall (rating from 1-5)
# Business Problem - To predict the High/Low rating (or sentiment) based on product reviews (Text data)
# Steps - 
1. Read the dataset using pandas
2. Clean the data - remove punctuations, remove stop words, stemming and lemmetizing operations on Text data
3. Vectorize the data to prepare it for building the model using countVectorizer and Tf-idf Vecorizer
4. Feature Engineering (optional)
5. Applying Machine Learning algorithms - Random Forest classifier(cross validation. hold out method and Grid search method)
