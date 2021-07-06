# Sentiment Analysis for Movie Reviews
## Installation
#### Importing Libraries
* numpy
* pandas
* matplotlib
* sklearn
* CountVectorizer
* TfidfVectorizer

### Introduction To Sentiment Analysis
Sentiment analysis (or opinion mining) is a natural language processing technique used to determine whether data is positive, negative or neutral. Sentiment analysis is often performed on textual data to help businesses monitor brand and product sentiment in customer feedback, and understand customer needs.

#### Dataset
The Rotten Tomatoes movie review dataset is a corpus of movie reviews used for sentiment analysis, originally collected by Pang and Lee.
The dataset that can be downloaded from this Kaggle link (https://www.kaggle.com/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews). If you download the dataset and extract the compressed file, you will see a CSV file. The file contains 50,000 records and two columns: review and sentiment. The review column contains text for the review and the sentiment column contains sentiment for the review. The sentiment column can have two values i.e. `"positive" `and `"negative"` which makes our problem a binary classification problem.<br>
Total number of records are: 50,000.<br>
Number of Positive Sentiment:  25000 <br>
Number of Negative Sentiment:  25000


