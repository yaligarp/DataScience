# DataScience
Repository containing portfolio of data science projects completed by me, presented in the form of iPython Notebooks.
Some of the interesting repositories that highlight my interests, exposure and proficiency.

# Portfolio:

* ## [BatchPredictionIOT:](https://github.com/yaligarp/DataScience/tree/main/BatchPredictionIOT) 

Data is being recorded from various condition monitoring sensors in a manufacturing plant. 
There are hundreds of such sensors which may be impacting the quality of final product which is getting manufactured.
Given the past data, task is to predict the target variable (could be an efficiency factor - though is it not explicitly mentioned)

Modelling was done with different approaches to feature engineering and different models and comparison done.

------
* ## [FlightPrices:](https://github.com/yaligarp/DataScience/tree/main/FlightPrices)

The price of an airline tickets is predicted based on the past data for several airlines. 
Effect of combination of various features like - Date of Journey, Route, Start city,Destination City,Airline etc are modelled.
Various models and encoding techniques for catagorical data have been tried.

------
* ## [PricePrediction:](https://github.com/yaligarp/DataScience/tree/main/PricePrediction)

A rental company aggregates rental providers and offers service to the customers to estimate/negotiate rental value for their potential listing.
Various property attributes for the current listings have been provided as the past data.
Task is to predict the rental value for the target.

Correlated features have been identified and removed.
Different labelling techniques have been tried.
New feature 'distance from city center' derived from latitude,longitude value is added and tested.

------
* ## [SentimentAnalysis:](https://github.com/yaligarp/DataScience/tree/main/SentimentAnalysis)

Sentiment analysis of text data based on the input dataset is done.
Various vectorization methods and machine learning models are compared.
There are two notebooks: one uses TfidfVectorizer,CountVectorizer and other uses Word2Vec with Nuera Network using Keras.

------
* ## [netGainClassification:](https://github.com/yaligarp/DataScience/tree/main/netGainClassification)

Given the results of previous ad-compaigns need to predict(classify) there would be net gain in running the campaign.
Various classification algorithms have been tried.
LogisticClassfier model with parameter class_wight='balanced' set had the best resuts on the training data:
However SVC model (with 'rbf' kernel) had the best resuts on test data:

------
* ## [RetailPricePediction:](https://github.com/yaligarp/DataScience/tree/main/RetailPricePediction)

Given the retail billing data like InvoiceNo,StockCode,Description,Quantity,UnitPrice,CustomerID,Country, the problem is to estimate the retail price on the test data.

------
* ## [InsuranceCostPrelim:](https://github.com/yaligarp/DataScience/tree/main/InsuranceCostPrelim)

Predict Insurance cost based on past Insurance Claim Data. Initial Exploratory Analysis and Modelling done to arrive at model selections based on experiments with pipelines and gridsearch; 
Also using comet.ml for running experiments and hyperparameter tuning.

 * The original Notebook is [here](https://www.kaggle.com/pyaligar/notebook0325f93125){:target="_blank"}
 * And the comet model is [here](https://www.comet.ml/yaligarp/saturday-codealong-medical-insurance-costs-predict/e961de32e76047cf8e487f252c24ae85?experiment-tab=chart&showOutliers=true&smoothing=0&transformY=smoothing&xAxis=wall){:target="_blank"}

------
# Other Repositories:

## Visualizations:

* [Matplotlib-Plotly-Dash](https://github.com/yaligarp/visualizations)

## Primers:

* [Numpy-Pandas](https://github.com/yaligarp/primers/)


## Deployments:

* [heroku-from-github](https://github.com/yaligarp/heroku-from-github)
* [heroku-cli](https://github.com/yaligarp/ga-dash-heroku)

------
## About Me
A passionate engineering professional with wide range of experience in architecture, data engineering/ingestion, data warehousing, Machine Learning, predictive modelling including Bigdata and cloud technologies.

### Profile: 
* [linkedin](https://www.linkedin.com/in/prakash-y-2327a6a/){:target="_blank"}

### Publications:
* [PREDICTING STRENGTH DEVELOPMENT BY CEMENT ADMIXTURE BASED ON WATER CONTENT](https://trid.trb.org/view/504288){:target="_blank"}
* [A Simplified Method for Assessment of Volume Change Behavior of Rockfill Material," Geotechnical Testing Journal, Vol. 21, No. 2](https://www.astm.org/DIGITAL_LIBRARY/JOURNALS/GEOTECH/PAGES/GTJ10753J.htm){:target="_blank"}

### Certifications:

* [Python for Data Science and Machine Learning-Udemy](https://www.udemy.com/certificate/UC-9JB3KRLR){:target="_blank"}
* [AWS SageMaker Hands-on-Training Udemy](https://www.udemy.com/certificate/UC-09bb3aa6-584d-4931-8425-2b2c48028470){:target="_blank"}
* [AWS Certified Big Data Professional](https://www.certmetrics.com/amazon/public/badge.aspx?i=8&t=c&d=2020-05-25&ci=AWS00996243){:target="_blank"}
* [Understanding Google Charts-Udemy](https://www.udemy.com/certificate/UC-6a2afbf6-caa5-4a4c-aaea-269fbe4c4a9e){:target="_blank"}
* [Azure BigData Certification - Udemy](https://www.udemy.com/certificate/UC-ec060c19-77d7-415a-ba97-63d9a6e71460){:target="_blank"}

### External resources:
* [H2o-Automl](https://github.com/h2oai/h2o-tutorials/tree/master/h2o-world-2017/automl){:target="_blank"}
* [Practical Deep Learning for Coders-fastai](https://course.fast.ai/){:target="_blank"}
