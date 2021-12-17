# Bootcamp Challenge-14 Machine Learning Trading Bot

A financial advisor at one of the top five financial advisory firms in the world, constantly competes with the other major firms to manage and automatically trade assets in a highly dynamic environment. 


Alphabet Soup’s business team receives many funding applications from startups every day. The goal is to create a model that predicts whether applicants will be successful if funded by Alphabet Soup.

The input is a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. The goal is to create a binary classifier model that will predict whether an applicant will become a successful business. The CSV file contains a variety of information about these businesses, including whether or not they ultimately became successful.

## Technologies 
<br/>
The project is written in python and uses the sklearn and tensorflow modules.
<br/>


## Installation Guide  
<br/>
To install the program, download the git repo and run the Jupyter notebook
<br/>

<br/>

## Results
<br/>
There are four models that are used for analysis. <br/>
* SVC Model <br/>
* LogisticRegression <br/>
* KNeighborsClassifier used with resampled data<br/>
* BalancedRandomForestClassifier used with resampled data <br/>


### SVC Model


### Logistic Regression Model


### KNN Model


### Balanced Random Forest Model


<br/>
### Summary
| Model  |  Resampling |  Train Accuracy |  Test Accuracy |  Ranking Based on Cum Returns| 
|---|---|---|---|---|
|  SVC | N  | 64%  | 55%  | 55%  | 2 |
|  Logistic Regression| N  | 66%  | 52%  | 3  |
|  KNN | Y  | 80%  | 51%  | 1  |
| Balanced Random Forest| Y | 100%  | 51%  | 4 |
<br/>

## Contributors 
<br/>
Author: Sumeet Vaidya
<br/>
Contributors: BootCamp for providing the base code.
<br/>


## License 
<br/>
When you share a project on a repository, especially a public one, it's important to choose the right license to specify what others can and can't with your source code and files. Use this section to include the license you want to use.

