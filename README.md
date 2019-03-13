# Otto-Group-Product-Classification

## A Kaggle Competitions of Otto Group

**Description:** Otto Group is one of the world’s biggest e-commerce companies, with subsidiaries in more than 20 countries, including Crate & Barrel (USA), Otto.de (Germany) and 3 Suisses (France). They are selling millions of products worldwide every day, with several thousand products being added to their product line.

This competition has a dataset with 93 features for more than 200,000 products. The objective is to build a predictive model which is able to distinguish between main product categories. 

#### Approach to build a predictive model:

* Exploratory Data Analysis
* Features selection using `PermutationImportance`, it helped to extract important features
* Model building using `RandomForestClassifier` 
* Used `GridSearchCV` to make the process of finding the best hyperparameters of model simpler (though it's computationally expensive)
* Calibration of predicted probabilities of model using `CalibratedClassifierCV`


**Evaluation metric:** multi-class logarithmic loss; **Scored:** 0.47640 (Top 30%)
