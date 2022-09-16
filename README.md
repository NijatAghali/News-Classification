# News-Classification


Data Source
------
In this assignment, we are expected to build a model that classifies given news article in Azerbaijani into one of the pre-defined six categories. You will need to train your model on a dataset of 50000 news examples. 
We will need to read the data from data file (news.xlsx). It contains three columns: news category, news title, and the news content. </br>
Category - six different news categories,
Title - news title, 
News_Article - news itself </br>


We are expected to extract features from the news articles using bag-of-words and tf-idf representation techniques.
I use library tools (CountVectorizer, TfidfVectorizer) for this purpose. </br></br>
Evaluated the performance with accuracy score.  </br>
LinearSVC                 0.82126 </br>
LogisticRegression        0.82276 </br>
MultinomialNB             0.77704 </br>

Needed Librares
------
* Pandas, numpy, scipy matplotlib, seaborn, sklearn

