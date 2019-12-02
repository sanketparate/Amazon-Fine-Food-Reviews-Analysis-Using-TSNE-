<b>Objective:</b> Given a review, determine whether the review is positive or negative.

<b>DataSource:</b>https://www.kaggle.com/snap/amazon-fine-food-reviews

Dataset is available in two forms:
1.	csv file
2.	SQLite Database file

We have taken Sqlite file with 5000 reviews and consider score >3 as positive rating and score <3 as negative reviews. Then we have done <b>Exploratory Data Analysis</b><br>
<strong>i.</strong>	Data Cleaning<br>
<strong>ii.</strong>	Text Processing on Text Column<br>

Then I perform Featurization:<br>
<strong>i.</strong>	Bag of Words<br>
<strong>ii.</strong>	Bi-Grams and n-Grams<br>
<strong>iii.</strong>	TF-IDF<br>
<strong>iv.</strong>	Word2Vec<br>
<strong>v.</strong>	Avg W2V<br>
<strong>vi.</strong>	TFIDF Weighted W2v<br>

<li>Applied TSNE on Review text BOW vectors</li><br>
<li>Applied TSNE on Review text TFIDF vectors</li><br>
<li>Applied TSNE on Review text Avg W2v vectors</li><br>
<li>Applied TSNE on Review text TFIDF W2v vectors</li><br>

TSNE is Applied to check that we can classify the positive and negative reviews to some extend. 
