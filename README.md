Machine Learning Project
========================
The goal of this work was to build a prediction model and then use this model to predict 20 test cases.       
Data used for this purpose comes from http://groupware.les.inf.puc-rio.br/har and was downloaded from Coursera website.      
 
## Processing data

In order to get suitable data for modeling, some transformations have been made :       
* Select and check outcome and predictor variables in training and testing data.            
* Transform training and testing data.       
* Preprocess for Prinicpal Components.      
* Remove variables with NA values.    


## Building Model

We tried to build two models : 
* One with CARET package using RPART.
* One with TREE package using RPART.

## Prediction

Prediction have been done with model from CARET package and written in text files.       
    

## Evaluation

1. Fork this repo on your computer : a directory named MachineLearning will be created with all files used in this project.       
2. Visualize this file : "../MachineLearning/Project/HAR.html".        
      