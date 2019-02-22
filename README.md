<b>Objective:</b> Given a review, determine whether the review is positive or negative.

<b>DataSource:</b>https://www.kaggle.com/snap/amazon-fine-food-reviews

Dataset is available in two forms:
1.	csv file
2.	SQLite Database file

We have taken Sqlite file with 5000 reviews and consider score >3 as positive rating and score <3 as negative reviews. Then we have done <b>Exploratory Data Analysis</b>
<strong>i.</strong>	Data Cleaning
<strong>ii.</strong>	Text Processing on Text Column

Then I perform Featurization:
<strong>i.</strong>	Bag of Words
<strong>ii.</strong>	Bi-Grams and n-Grams
<strong>iii.</strong>	TF-IDF
<strong>iv.</strong>	Word2Vec
<strong>v.</strong>	Avg W2v
<strong>vi.</strong>	TFIDF Weighted W2v

Applied TSNE on Review text BOW vectors
Applied TSNE on Review text TFIDF vectors
Applied TSNE on Review text Avg W2v vectors
Applied TSNE on Review text TFIDF W2v vectors

TSNE is Applied to check that we can classify the positive and negative reviews to some extend. 
