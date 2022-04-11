# Neural Network Charity Analysis

---

# Overview

The purpose of this analysis is to provide information about optimizing which charities to donate that as a whole are more impactful within their respective goals and communities.

---

# Results
  * Data Processsing
  
    * IS_SUCCESSFUL column is considered to be the target for the model
    * APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT are considered featured for the model
    * EIN and NAME are neither targets nor features, ergo are removed from the dataset
  * Compiling, Training, and Evaluating the Model
  
    * Model containes two hidden layers each with 80 and 30 neurons, respectively
    * 43 features and 25,724 samples
    * Only achieved 73.32% accuracy in comparison to the target model
    * Organized the dataset in intervals and applied ASK_AMT, was not able to produce an image of higher optimization. 

---

# Summary

The optimization model did not achieve anything greater than the accuracy prior to attempting to optimizing the model. A suggestion may be to switch to a supervised machine learning considering that the data does contan an output where one can choose any of the methods, and more preferably using the Easy ADA Forest Classifier method.
