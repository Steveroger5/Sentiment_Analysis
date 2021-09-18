# Sentiment_Analysis
<img src="https://thecxlead.com/wp-content/uploads/2021/04/CXLead-Sentiment-Scoring-Scale2-1024x536.png">
<hr>
<h2>Overview</h2>
<p>
Sentiment Analysis refers to detecting the polarity of any comment whether it is having a positive meaning or negative. It has multiple applications for example in checking review of a newly launched movie , for checking sentiment about any movement like kissan andolan and also for automatic feedback classification and many more.
</p>
<p>
<b>Project Link Online Deployed on Heroku : <a href="https://senti-analysis98.herokuapp.com/">https://senti-analysis98.herokuapp.com/</a></b>
</p>
<hr>
<h2>Dataset and libraries</h2>
<p>
<b>Dataset : </b>NLTK Dataset which containes the positive and Negative fileids<br>
<b>Libraries : </b>Python , Numpy , Pandas, NLTK , Sklearn , Node.js , Express.js.<br>
<b>Frameworks : </b>VScode , jupyter Notebook , Heroku.
</p>
<hr>
<h2>Project Methodology</h2>
<p>
In this project I have developed a machine learning model to classify the polarity of the sentiment or any given text.The steps used in developing the machine learning model are of the one that are used in the natural language processing (NLP).
Below is brief description of every step and technique used by me.<br><br>
<b>Tokenisation :</b> In this step first we break the given text into subsequent words involved.<br>
<b>Stopword Removal :</b>In this step we remove the words that don't play a role in determining the polarity of a sentiment like is,am,are etc.<br>
<b>Building dictionary :</b>In this step we combine every sentiment to get a wholesome dictionary from which we classify the top occuring words which wll further be used to convert the sentiment into a binary vector.<br>
<b>Building Vectorizer :</b>In this step we basically check which words from the previous dictionary are present and absent at the same time. so now we have created a binary dataframe from the words in our dictionary.<br>
<b>Applying the machine learning Models :</b>In this step i applied three machine learning models below are their names and their corresponding accuracy.<br>
1. Naive Bayes Classifier : 79%<br>
2. Logistic Regression : 82%<br>
3. Support Vector Classifier : 84%<br>
as we can see the SVC classifer gave the best Accuracy so i downloaded the SVC model using pickle library and used it in my flask application.
</p>
<hr>
<h2>ScreenShots of the Website Deployed</h2>

