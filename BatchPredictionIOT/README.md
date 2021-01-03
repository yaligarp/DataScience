## Problem Statement
Data is being recorded from various condition monitoring sensors in a manufacturing plant. 
There are hundreds of such sensors which may be impacting the quality of final product which is getting manufactured.
Each row of data set refers to a batch of the process and a data collected for 55 sensors at different intervals of time.

Given the past data, task is to predict the target variable (could be an efficiency factor - though is it not explicitly mentioned)

Modelling was done with different approaches to feature engineering and different models and comparison done.

RESULTS: Comparison

MODEL                                 PLAIN Model      With Reduced Observation    With feature Drops
ElasticNet (alpha=1.0, l1_ratio=0.5)  0.24             0.26                        0.25
GradientBoostingRegressor             0.27             0.28                        0.25
LGBMRegressor                         0.24             0.24                        0.25
Ridge      (alpha=0.5,0.7,0.2)        0.18             0.18                        0.2
RandomForestRegressor                 0.03             0.03                        0.16
Lars                                  0.17             0.03                        0.16
LarsCV                                0.25             0.25                        0.25
LassoLars                             0.00             0.00                        0.00
LassoLarsCV                           0.26             0.26                        0.27
CatBoostRegressor                     0.38             0.39                        0.34
HuberRegressor                        0.24             0.21                        0.19
RANSACRegressor                       0.21             -6.69                       6.43
TheilSenRegressor                     0.27             -0.2                        0.13
PassiveAggressiveRegressor            0.11             -3.95                       -7.43
BaggingRegressor                      0.08             0.01                        0.05
AdaBoostRegressor                     0.04             0.07                        0.05
SVR                                   0.03             0.01                        0.01

NOTES: 
In general removel of features either by EDA or through RFECV did not bring about much changes in the model performances.
CatBoostRegressor outclassed other models in all the cases
Removal of outliers (miniscule values that were power of -11) did not help. In fact that affeceted negetively
NEXTSTEPS: Understand the models from fundamentals and decipher why there was - no effect, negetive effect,positive effect with differing techniques.
    
