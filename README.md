# Machine Learning Classification of Variables Needed to Determine Gender Inequality Index (GII). 
## Abigail Parakoyi 

# Overview 
This project takes a data set from the Kaggle [gender inequality index](https://www.kaggle.com/datasets/gianinamariapetrascu/gender-inequality-index) and applies three regression machine learning models (Multiple regression, decision tree, and neural network) and a bagged ensemble model to determine which feature variables drive the gender inequality index (GII). 

# Description

## Getting Started
### Dependencies 
* Run on R version 4.2.2
* Code done on Mac
  
### Installing 
The below packages are necessary to run this code: 
* gsheet
* tidyverse
* caret
* MASS
* rpart
* gmodels
* Cubist
* neuralnet
  
### Executing Program 
To execute this code ensure that the line of code that reads the Kaggle [gender inequality index](https://www.kaggle.com/datasets/gianinamariapetrascu/gender-inequality-index) is reading from the right [Google Sheets link](https://docs.google.com/spreadsheets/d/1UT-mkzliF3sEXNllI4rzRWlM4P6jjbqH9FJXZIPMGgI/edit?usp=sharing). The below chunk of code indicates the specific line of interest.  

```
GIdata <-gsheet2tbl("https://docs.google.com/spreadsheets/d/1UT-mkzliF3sEXNllI4rzRWlM4P6jjbqH9FJXZIPMGgI/edit#gid=1292094241")

```
