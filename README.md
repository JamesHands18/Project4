# Project4

# Shine Bright Like A Diamond 

![Clarity Chart](https://user-images.githubusercontent.com/112433621/232899353-2ab1aa5d-e240-42fb-b6c7-eb06f8d6108f.jpg)


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

## METHODS

- Data Extraction and Cleaning – Python Pandas
- Data Model Testing – Linear Regression Model
- Data Model Testing – Neural Network 
- Data Model Testing – Random Forest Regression
- Database Construction – SQL (pgAdmin)
## Data Cleaning 
<img width="792" alt="Reading n cleaning" src="https://user-images.githubusercontent.com/112433621/232897617-d640c5cc-51de-4052-a92d-9849e2668dd5.png">
## Scaling the Data
<img width="941" alt="Scaling the Data" src="https://user-images.githubusercontent.com/112433621/232898871-acc1f311-9c84-42bd-95ad-98e7be17beea.png">

### FINDINGS: Linear Regression Model:
The Linear Regression Model used the scaled_df dataframe to create a model that would predict the price of a diamond based on how many carats the diamond had.
<img width="440" alt="Lin Regress" src="https://user-images.githubusercontent.com/112433621/232873189-133c3153-fc3b-4e87-8318-2126fceb2910.png">
- As part of building the model, we split the data into two sets. One set for training the model and the second set was for testing the model's perfomance.
<img width="414" alt="the model" src="https://user-images.githubusercontent.com/112433621/232879809-78d50d30-5a2e-49c0-9cc5-ff88301f15cd.png">

- The following image (below) shows results of our models performance . The mean Squared error is 0.09% which is a decent result for our model.
<img width="548" alt="Final outcomes" src="https://user-images.githubusercontent.com/112433621/232880456-ce386f05-20bd-4230-a170-800deece5c19.png">
 Another way to visualise the result is to create charts. We created a chart to see if any of the variables have an effect on price, and we noticed that carat had a direct effect on price. 

<img width="536" alt="carat vs price" src="https://user-images.githubusercontent.com/112433621/232893015-51e5d213-1599-4bf8-abb0-60b236e7c2e7.png">

In conclusion for this model, it would be great to maybe learn new ways of tweaking the data to enable more tests with several variables regardless of their datatype as this would help paint a clearer picture of just how functional and applicable the model can be. It would also help make comparisons between feature variables and their effect on our models perfomance and outcomes. 
### FINDINGS: Neural Network:

NEURAL NETWORK (WITH THE SPECIFICATIONS SHOWN) PERFORMED POORLY.

R2 SCORE WAS USED TO EVALUATE THE PERFORMANCE OF THE REGRESSION BASED MODEL.

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


- Another possible activity we could have done to improve our presentation could have been building an interactive website where we could have showcased different specifications of diamonds.

  - An example could have been: "what are the most common diamonds and what is their price?"

## CHALLENGES AND CONCLUSIONS

The dataset was not suitable for neural networks despite using linear regression as the outcomes are not as straightforward as binary information. It is often quite hard to predict the carat or price of a diamond since every attribute contribute to its value.​

However, Random Forest Regression suits continuous variables and is comfortably able to handle large datasets. The Random Forest Regression, in addition does not need normalisation, which is ideal for a dataset such as ours.​

Due to the complicated and complex, trying to import the CSV into SQL(pgAdmin) was a challenge.

