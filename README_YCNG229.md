**ABOUT THE PROJECT**

The purpose of this project was to perform sentiment analysis(natural language processing) on stock market news/headlines and to see how it would affect stock price.  Another goal of the project was to explore and compare certain nlp tools such as Vader and Transformers.

**DATA USED**

Dataset found on kaggle was used reflecting the DOW JONES index.  The dataset showed the top newslines and staple stock info ( open, close, volume, etc). A label represented whether stock price increased(1) or decreased(0) following the news. A new label was created in order to fully represent the price affect.

Data also webscraped off of FinViz

**MODELS & RESULTS**

Once data was cleaned and sentiment scores were obtained, models were implemented to try to predict the correct label corectly. Models used: Linear Discriminant Analysis, SVM Classification, SGDClassifier, and Random Forest Classifier. SVM had the greatest accuracy with ~ 55% while SGD had the poorest at ~51% .

**COMPARISON BETWEEN NLP TOOLS**

Just to see I compared polarity scores between TextBlob and Vader.  And compared whether Vader and Pegasus produced similar polarity classification(if they both said a statement was positive or they both said it was negative).

**FINVIZ**

In both parts minor visualization was performed in order to see the correlation between the closing price change and the compound score of the sentiment analysis. In order to compare, price data was obtained via yahoo finance API.

**THOUGHTS**

The project taught me many things.  I was not familiar with NLP tools before this course/project.  I had never webscraped before on Python so that was interesting as well.

**MOVING FORWARD**

What I would like to do to improve this project is obtain Reddit and/or twitter API keys to webscrape data (user's thoughts).  This would give ALOT of recent opinions which would give a better idea on how the retail investors' sentiments affect or the market prices.  