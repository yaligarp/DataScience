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
* [AWS Certified Machine Learning Specialty - Udemy](https://www.udemy.com/certificate/UC-FUI1JTZ8/){:target="_blank"}
* [Understanding Google Charts-Udemy](https://www.udemy.com/certificate/UC-6a2afbf6-caa5-4a4c-aaea-269fbe4c4a9e){:target="_blank"}
* [Azure BigData Certification - Udemy](https://www.udemy.com/certificate/UC-ec060c19-77d7-415a-ba97-63d9a6e71460){:target="_blank"}
* [Apache Kafka - Udemy](https://www.udemy.com/certificate/UC-KR0AR60O){:target="_blank"}

### External resources:
* [H2o-Automl](https://github.com/h2oai/h2o-tutorials/tree/master/h2o-world-2017/automl){:target="_blank"} and [H2o quickstart](https://www.bitbook.io/h2o-ai-quick-start-tutorial-for-just-about-anyone/){:target="_blank"}
* [Choosing right structure for your Data Team](https://www.montecarlodata.com/blog-how-to-choose-the-right-structure-for-your-data-team/){:target="_blank"}
* [Practical Deep Learning for Coders-fastai](https://course.fast.ai/){:target="_blank"}
* [Feaure Selection For Machine Learning](https://machinelearningmastery.com/feature-selection-with-real-and-categorical-data/){:target="_blank"}
* [Data Transformation - Standardization vs Normaliation](https://www.kdnuggets.com/2020/04/data-transformation-standardization-normalization.html){:target="_blank"}
* [Transition from pandas -> PySpark](https://databricks.com/blog/2020/03/31/10-minutes-from-pandas-to-koalas-on-apache-spark.html#:~:text=A%20Koalas%20Series%20can%20be,way%20as%20a%20pandas%20Series.&text=A%20Koalas%20DataFrame%20has%20an,by%20passing%20a%20pandas%20DataFrame.){:target="_blank"} using [Koalas](https://koalas.readthedocs.io/en/latest/getting_started/install.html){:target="_blank"}
* [Leverage In-Database ML with MPP Database](https://www.vertica.com/product/database-machine-learning/){:target="_blank"} and the [Python API](https://www.vertica.com/python)
* [Microsoft Learn AI Fundamentals Exercises](https://github.com/MicrosoftDocs/ai-fundamentals){:target="_blank"}
* [Microsoft Azure AI Fundamentals Exercises](https://github.com/MicrosoftLearning/mslearn-ai900){:target="_blank"}
* [Open Source Platform for ML lifecycle Management](https://mlflow.org/){:target="_blank"} 
* [LAMA - An Automatic Model Creation Framework](https://analyticsindiamag.com/hands-on-python-guide-to-lama-an-automatic-ml-model-creation-framework/){:target="_blank"}
* [Deploying the model on Kubernetes](https://www.kubermatic.com/blog/deploy-your-deep-learning-model-on-kubernetes-1/){:target="_blank"}
* [Azure ML Studio](https://www.youtube.com/watch?v=VcbMFy05h54&list=PL8eNk_zTBST_WSR_KUBex8TDnQ21GetSG&index=2){:target="_blank"}
* [PyArrow for Parquet Files](https://mungingdata.com/pyarrow/parquet-metadata-min-max-statistics/){:target="_blank"}
* [7 Mistakes in Using Apache Kafka](https://blog.softwaremill.com/7-mistakes-when-using-apache-kafka-44358cd9cd6){:target="_blank"}
* [Event Driven Microservices with Kafka](https://www.confluent.io/resources/event-driven-microservices/?utm_medium=display&utm_source=google&utm_campaign=ch.display_tp.rmkt_tgt.content-remarketing_rgn.india_lng.eng_dv.all_con.event-driven-microservice-whitepaper&utm_term=&creative=edma-snsd-7Days&device=c&placement=www.guru99.com&gclid=EAIaIQobChMInK7WgoHY7gIVyB3VCh1H2AFQEAEYASAAEgJSxPD_BwE){:target="_blank"}
* [Good Bad Ugly of Spark](https://thenewstack.io/the-good-bad-and-ugly-apache-spark-for-data-science-work/){:target="_blank"}
* [Spark Best Practices for Datascience](https://www.kdnuggets.com/2020/08/5-spark-best-practices-data-science.html){:target="_blank"}
* [PCA with AWS Sagemaker, algorithms and tradeoff](https://aws.amazon.com/blogs/machine-learning/running-principal-component-analysis-in-amazon-sagemaker/){:target="_blank"}
* [t-Distributed Stochastic Neighbor Embedding](https://www.datacamp.com/community/tutorials/introduction-t-sne){:target="_blank"}
* [Scalars - when to use what](https://scikit-learn.org/stable/auto_examples/preprocessing/plot_all_scaling.html){:target="_blank"}
* [Gradient Descent Optimiers](https://ruder.io/optimizing-gradient-descent/){:target="_blank"}
* [ROC - AUC](https://www.datasciencecentral.com/profiles/blogs/roc-curve-explained-in-one-picture){:target="_blank"}

VIDEOS
* [Statistical Learning with Big Data](https://www.youtube.com/watch?v=0EWJZIC4JxA){:target="_blank"}
* [Decision Trees](https://www.youtube.com/watch?v=WOOTNBxbi8c){:target="_blank"}
* [Ensembles](https://www.youtube.com/watch?v=Yvn3--rIdZg){:target="_blank"}
* [Gradient Boosting Machine Learning](https://www.youtube.com/watch?v=wPqtzj5VZus){:target="_blank"})
* [MIT Introduction to Deep Learning](https://www.youtube.com/watch?v=5v1JnYv_yWs&feature=youtu.be){:target="_blank"}
* [MIT CNN](https://www.youtube.com/watch?v=H-HVZJ7kGI0){:target="_blank"}
* [MIT RNN](https://www.youtube.com/watch?v=_h66BW-xNgk&feature=youtu.be){:target="_blank"}
* [GANs for Good - Panel Discussion](https://www.youtube.com/watch?v=9d4jmPmTWmc&feature=youtu.be){:target="_blank"}
* [Nuts and Bolts of Deep Learning](https://www.youtube.com/watch?v=F1ka6a13S9I){:target="_blank"}
* [Transfer Learning](https://www.youtube.com/watch?v=yofjFQddwHE){:target="_blank"})
* [Amazon Sagemaker Deep Dive](https://www.youtube.com/watch?v=uQc8Itd4UTs&list=PLhr1KZpdzukcOr_6j_zmSrvYnLUtgqsZz){:target="_blank"})
* [Train custom models on Sagemaker](https://www.sicara.ai/blog/amazon-sagemaker-model-training){:target="_blank"}
* [HyperParameter tuning for Deep Learning in AWS](https://aws.amazon.com/blogs/machine-learning/the-importance-of-hyperparameter-tuning-for-scaling-deep-learning-training-to-multiple-gpus/){:target="_blank"}
* [SageMaker Studio](https://youtu.be/wiDHCWVrjCU){:target="_blank"}
