# Project4

# Shine Bright like a diamond 

## TABLE OF CONTENTS:
- PURPOSE OF PROJECT
- METHODS
- FINDINGS
- WHAT ELSE COULD WE HAVE DONE
- CHALLENGES AND CONCLUSIONS

## PURPOSE OF PROJECT

- CAN WE PREDICT A PRICE OF A DIAMOND BASED ON IT’S PROPERTIES SUCH AS THE CARAT?​
- WHAT KIND OF MODEL CAN PREDICT THE PRICE OF THE DIAMOND THE BEST

### DATA SOURCES

- The dataset utilised for the analysis contains the prices and other attributes of over 54,000 different diamonds.​
- The dataset is derived via a CSV download from Kaggle: (https://www.kaggle.com/datasets/ulrikthygepedersen/diamonds?resource=download

## METHOODS

- Data Extraction and Cleaning – Python Pandas
- Data Model Testing – Linear Regression Model
- Data Model Testing – Neural Network 
- Data Model Testing – Random Forest Regression
- Database Construction – SQL (pgAdmin)

### FINDINGS: Linear Regression Model:

### FINDINGS: Neural Network:

NEURAL NETWORK (WITH THE SPECIFICATIONS SHOWN) PERFORMED POORLY.

R2 SCORE WAS USED TO EVALUATE THE PERFORMANCE OF THE RECRESSION BASED MODEL.

THE MEAN SQUARED ERROR WAS USED TO CALCULATE THE DIFFERENCE BETWEEN A PREDICTED VALUE AND THE ACTUAL ONE.

THERE WASN'T A SPECIFICATION THAT STOOD OUT, HOWEVER THE MODEL THAT USED THE SCALED DATA AND DEPTH AS A SPECIFICATION.

![image](https://user-images.githubusercontent.com/105055655/232855755-5e7cc5ea-a316-4d1d-b968-9e3493495bd5.png)

### FINDINGS: Random Forest Regression

RANDOM FOREST MODEL (WITH THE SPECIFICATIONS SHOWN) PREDICTED PRICE WITH AN EXTREMELY GOOD ACCURACY. IT ALSO SHOWED THAT THE CARAT WAS BY FAR THE MOST IMPORTANT FACTOR WHEN DETERMINING PRICE 

![image](https://user-images.githubusercontent.com/105055655/232856146-6c092819-099b-4baa-9831-2d9c98827099.png)

## WHAT ELSE COULD WE HAVE DONE

- Ideally, we could have looked into the dataset's quality. Through tableau we could have analysed the data from a different.​

  - Especially since one of the most common issues faced within machine learning is the quality of the data.​

  - Ideally we could have found an API that connected directly to the source of the research to avoid intermediary issues.​


- Another possible activity we could have done to improve our presentation could have been building an website interactive website where we could have showcased different specifications of diamonds.

  - An example could have been: "what are the most common diamonds and what is their price?"

## CHALLENGES AND CONCLUSIONS

The dataset was not suitable for neural networks despite using linear regression as the outcomes are not as straightforward as binary information. It is often quite hard to predict the carat or price of a diamond since every attribute contribute to its value.​

However, Random Forest Regression suits continuous variables and is comfortably able to handle large datasets. The Random Forest Regression, in addition does not need normalisation, which is ideal for a dataset such as ours.​

Due to the complicated and complex, trying to import the CSV into SQL(pgAdmin) was a challenge.


