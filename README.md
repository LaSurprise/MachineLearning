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

We tried to build three models : 
* Two with CARET package using RPART and NB.
* One with TREE package using RPART.

## Prediction
A prediction was done with TREE, but associated weights were too low.   
With CARET/RPART, this was not possible.      
With CARET/NB, it is still a challenge.     


## Evaluation

1. Fork this repo on your computer : a directory named MachineLearning will be created with all files used in this project       
2. Set Working Directory with a proper path in RStudio : setwd("C:/Users/YourPrompt/MachineLearning/Project/")        
2. Open an run HAR.Rmd with RStudio         