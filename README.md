# Bank-Reviews-Complaints-Analysis
### BUSINESS PROBLEM :
Central banks collecting information about customer satisfaction with the services provided by different bank. Also collects the complaints.Bank users give ratings and write reviews about services on central bank websites. These reviews and ratings help to banks evaluate services provided and take necessary to action improve customer service. While ratings are useful to convey the overall experience, they do not convey the context which led a reviewer to that experience. 
If we look at only the ratings, it is difficult to guess why the user rated the service as 4 stars. However, after reading the review, it is not difficult to identify that the review talks about good "service" and "expectation".

## OBJECTIVE :
The objective is to analyze customer reviews and predict customer satisfaction with the reviews.
1) Data preprocessing.
2) Key possitive words/negative words (most frequent words).
3) Classification of reviews into positive, negative and neutral.
4) Identify key themes of problems (using clustering, topic modeling).
5) Predicting star ratings using reviews.
6) Perform intent analysis.
## DATA AVAILABILITY: 
The data is detailed dump of customer reviews/ complaints (~500) of different services at different banks.
1) Date : Day the review was posted.
2) Stars : 1-5 ratings for the business.
3) Reviews : Review text.
4) BankName : Name of the bank.
## Data Prepration
* Exploring Dataset.
* Generating New Festures(word count, unique word count,Letter count,word density,punctuation count,upper case word count,lower case word count,Title case word count,Number of stopwords,average word length,number of numerics,number of  alphanumeric,number of alphabetic)
* Splitting Data
* Tokenization
* Pos-Tagging
* Disambiguation
* Cleaning up of non-textual data
* Removing Stop Word
* Lemmatization
* Vectorization for train only
* EDA
* WordCloud
* Classifying reviews to positive,negative and neutral using TextBlob utility.
* Clustering(Kmeans)
* Elbow analysis
* PCA
* N-gram level tf-idf
* Character level tf-idf
* Topic Modeling(LDA)
## Machine Learning model
* Naive Bayes
* Predicting Star Rating
