# DataScience

Summary:

BatchPredictionIOT: 

Data is being recorded from various condition monitoring sensors in a manufacturing plant. 
There are hundreds of such sensors which may be impacting the quality of final product which is getting manufactured.
Given the past data, task is to predict the target variable (could be an efficiency factor - though is it not explicitly mentioned)

Modelling was done with different approaches to feature engineering and different models and comparison done.

FlightPrices:

The price of an airline tickets is predicted based on the past data for several airlines. 
Effect of combination of various features like - Date of Journey, Route, Start city,Destination City,Airline etc are modelled
Various models and encoding techniques for catagorical data have been tried.

PricePrediction:

A rental company aggregates rental providers and offers service to the customers to estimate/negotiate rental value for their potential listing.
Various property attributes for the current listings have been provided as the past data.
Task is to predict the rental value for the target.

Correlated features have been identified and removed.
Different labelling techniques have been tried.
New feature 'distance from city center' derived from latitude,longitude value is added and tested

SentimentAnalysis:

Sentiment analysis of text data based on the input dataset is done
Various vectorization methods and machine learning models are compared.
There are two notebooks: one uses TfidfVectorizer,CountVectorizer and other uses Word2Vec with Nuera Network using Keras.

netGainClassification:

Given the results of previous ad-compaigns need to predict(classify) there would be net gain in running the campaign.
Various classification algorithms have been tried.
LogisticClassfier model with parameter class_wight='balanced' set had the best resuts on the training data:
However SVC model (with 'rbf' kernel) had the best resuts on test data:

RetailPricePediction:

Given the retail billing data like InvoiceNo,StockCode,Description,Quantity,UnitPrice,CustomerID,Country, the problem is to estimate the retail price on the test data.
