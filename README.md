# Credit_Risk_Analysis

## Overview of the analysis
In 2019, more than 19 million Americans had at least one unsecured personal loan. That's a record-breaking number! Personal lending is growing faster than credit card, auto, mortgage, and even student debt. With such incredible growth, FinTech firms are storming ahead of traditional loan processes. 

#### Purpose:
Use Python to build and evaluate several machine learning models to predict credit risk. 

## Results

**_The following resampling methods were used to predict credit risk:_**

Naive Random Oversampling
> **from** imblearn.over_sampling **import** RandomOverSampler

![naive_random_oversampling](https://user-images.githubusercontent.com/78178900/126879758-9d72d782-5f66-4a18-ac14-dc644c68f8e6.png)


SMOTE Oversampling
> **from** imblearn.over_sampling **import** SMOTE

![smote_oversampling](https://user-images.githubusercontent.com/78178900/126879848-64828ee0-987d-43e8-ad3e-a696301d5019.png)


ClusterCentroids Undersampling
> **from** imblearn.under_sampling **import** ClusterCentroids

![clusterCentroids_undersampling](https://user-images.githubusercontent.com/78178900/126879896-5cb8dfb9-6695-4552-ba31-7481f7a2319c.png)


**_The SMOTEENN method was used to predict credit risk:_**

SMOTEENN Combination (over and under) Sampling
> **from** imblearn.combine **import** SMOTEENN

![smoteenn_combination_sampling](https://user-images.githubusercontent.com/78178900/126879930-0792fd44-0574-42eb-9cae-1126988d7b2a.png)


**_Ensemble classifiers were used to predict credit risk:_**

Balanced Random Forest Classifer
> **from** imblearn.ensemble **import** BalancedRandomForestClassifier

![balanced_random_forest_classifier](https://user-images.githubusercontent.com/78178900/126887599-23a15426-237b-4d7b-ba77-79ffda0c08b5.png)


Easy Ensemble AdaBoost Classifier
> **from** imblearn.ensemble **import** EasyEnsembleClassifier

![easy_ensemble_classifier](https://user-images.githubusercontent.com/78178900/126887656-0ce68ede-109b-4764-b50b-df201faa5e8d.png)


## Summary

#### Recomendations:
