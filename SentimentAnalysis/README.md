# Problem Statement:¶
The notebook presents the solution and approaches and comaparisons there of for a sentiment prediction problem. Various vectorization methods and machine learning models are compared.

# Data Description:
## TRAIN.csv
It contains the training data with review details as described below

## Data Dictionary:
Variable Description

* Id - Unique identifier for each tuple

* category - The reviews have been categorized into two categories representing positive and negative reviews. 0 represents positive reviews and 1 represents negative reviews.

* text - Tokenized text content of the review

## TEST.csv
It has review details for which to predict whether category would be positive or negative

## RESULTS:

### RESULTS with TFvectorizer:

* PassiveAggressiveClassifier:

 ('accuracy', 0.9942307692307693)
  ('F1 Score = ', 0.9385221674876847)

* MLPClassifier:

 ('accuracy', 0.9942307692307693)
 ('F1 Score = ', 0.9385221674876847)

* SGDClassifier:

 ('accuracy', 0.9942307692307693)
 ('F1 Score = ', 0.9385221674876847)  

* LogisticRegressionCV:               [same result with all-solver{‘newton-cg’, ‘lbfgs’, ‘liblinear’, ‘sag’, ‘saga’}, default=’lbfgs’]

 ('accuracy', 0.9942307692307693)
 ('F1 Score = ', 0.9385221674876847)

* RidgeClassifierCV:

 ('accuracy', 0.9923076923076923)
 ('F1 Score = ', 0.9146981627296588)

* LinearSVC :

 ('accuracy', 0.9903846153846154)
 ('F1 Score = ', 0.8888461374032748)

* KNeighborsClassifier:

 ('accuracy', 0.9903846153846154)
 ('F1 Score = ', 0.8888461374032748)

* RidgeClassifier:

 ('accuracy', 0.9903846153846154)
 ('F1 Score = ', 0.8888461374032748)

* GradientBoostingClassifier:

  ('accuracy', 0.9884615384615385)
  ('F1 Score = ', 0.8720472440944882)

* BaggingClassifier:

 ('accuracy', 0.9865384615384616)
 ('F1 Score = ', 0.856551724137931)

* DecisionTreeClassifier:

 ('accuracy', 0.9826923076923076)
 ('F1 Score = ', 0.8403765476312288)

* ExtraTreesClassifier:

 ('accuracy', 0.9846153846153847)
 ('F1 Score = ', 0.8142525450973388)

* RandomForestClassifier:

 ('accuracy', 0.9826923076923076)
 ('F1 Score = ', 0.758750451054178)

* LogisticRegression:

 ('accuracy', 0.9730769230769231)
 ('F1 Score = ', 0.49317738791423)

* BernoulliNB:

 ('accuracy', 0.9730769230769231)
 ('F1 Score = ', 0.49317738791423)

* MultinomialNB:

 ('accuracy', 0.9730769230769231)
 ('F1 Score = ', 0.49317738791423)


### Results with CountVectorizer:

* PassiveAggressiveClassifier:

 ('accuracy', 0.9923076923076923)
 ('F1 Score = ', 0.9146981627296588)

* MLPClassifier:

 ('accuracy', 0.9923076923076923)
 ('F1 Score = ', 0.9146981627296588)

* SGDClassifier:

 ('accuracy', 0.9884615384615385)
 ('F1 Score = ', 0.8898927159796726)
 

* LogisticRegressionCV:               [same result with all-solver{‘newton-cg’, ‘lbfgs’, ‘liblinear’, ‘sag’, ‘saga’}, default=’lbfgs’]

('accuracy', 0.9942307692307693)
('F1 Score = ', 0.9385221674876847) [ Same for tfidf and count, and same as LogisticRegression]

* RidgeClassifierCV:

 ('accuracy', 0.9942307692307693)
 ('F1 Score = ', 0.9385221674876847)

* LinearSVC :

 ('accuracy', 0.9923076923076923)
 ('F1 Score = ', 0.9211045364891519)

* KNeighborsClassifier:

 ('accuracy', 0.9730769230769231)
 ('F1 Score = ', 0.49317738791423)

* RidgeClassifier:

 ('accuracy', 0.9730769230769231)
 ('F1 Score = ', 0.49317738791423)

* GradientBoostingClassifier:

 ('accuracy', 0.9826923076923076)
 ('F1 Score = ', 0.7999230473258946)

* BaggingClassifier:

 ('accuracy', 0.9807692307692307)
 ('F1 Score = ', 0.7678156813716734)

* DecisionTreeClassifier:

('accuracy', 0.9807692307692307)
('F1 Score = ', 0.8283828382838283)

* ExtraTreesClassifier:

 ('accuracy', 0.9846153846153847)
 ('F1 Score = ', 0.7960784313725491)

* RandomForestClassifier:

 ('accuracy', 0.9769230769230769)
 ('F1 Score = ', 0.619140625)

* LogisticRegression:                     

 ('accuracy', 0.9942307692307693)
 ('F1 Score = ', 0.9385221674876847)

* BernoulliNB:

 ('accuracy', 0.9730769230769231)
 ('F1 Score = ', 0.49317738791423)

* MultinomialNB:

 ('accuracy', 0.9826923076923076)
 ('F1 Score = ', 0.8591676446691342)    
