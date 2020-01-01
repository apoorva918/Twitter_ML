# Twitter Sentiment Analysis

#### Python code developed using pandas, numpy, nltk libraries in jupyter notebooks.

### Description
training_set.csv
- 31962 labeled tweets
- label 1 for negative
- label 0 for positive

testing_set.csv
- 17197 non-labeled tweets

Techniques used for feature extraction:
- Bag-of-words
- TF-IDF

Machine Learning models used:
- Gaussian Naive Bayes
- Gradient Boosting Machine
- Logistic Regression
- Random Forest

Metrics used for comparison:
- F1 score
- Accuracy

To execute:
Run Final_twitter.ipynb

Steps performed:
- preprocessing of data
- training set split into training and validation set
- feature extraction using both techniques
- all four models are fit onto both features
- maximum accuracy achieved using Random forest with TFIDF features, so test data is labeled with this model

Data visualization done using word clouds and graphs. It is displayed on webpages. 
