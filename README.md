# Notebook #4: Scikit Learn with Housing Dataset

For this notebook, you are going to demonstrate how to use the scikit-learn library (https://scikit-learn.org) to perform machine learning experiments. 
## The Data :bar_chart: 
You will use a new dataset that deals with housing prices in the Boston neighborhood that was collected in 1978. (available as 'HousingData.csv' in the "Datasets" section of the blackboard website.) 

The goal for this machine learning exercise is to use the scikit-learn library implementation of **k-Nearest-Neighbors** and **Decision Trees** to make predictions on the 'MEDV' (median value in $1,000's) target variable based on the learning examples. 

There are 14 attributes in each case of the dataset. They are:
* CRIM - per capita crime rate by town
* ZN - proportion of residential land zoned for lots over 25,000 sq.ft.
* INDUS - proportion of non-retail business acres per town.
* CHAS - Charles River dummy variable (1 if tract bounds river; 0 otherwise)
* NOX - nitric oxides concentration (parts per 10 million)
* RM - average number of rooms per dwelling
* AGE - proportion of owner-occupied units built prior to 1940
* DIS - weighted distances to five Boston employment centres
* RAD - index of accessibility to radial highways
* TAX - full-value property-tax rate per $10,000
* PTRATIO - pupil-teacher ratio by town
* B - 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
* LSTAT - % lower status of the population
* MEDV - Median value of owner-occupied homes in $1000's

## The Exercises:
**Part 0: [1 point]** Is your name at the top of your submission? Is it submitted in the proper Notebook 3 repository in github?

**Part 1: [1 point]** Clean and normalize the data (use the StandardScalar from sklearn). Replace any null values with the average of the columns. Verify that there are no null values by printing out the results of `housing_data.isna().any()`

**Part 2: [3 points]** You must run at least 6 variations of the algorithms and display their results using an appropriate regression metric (again, use the scikit-learn modules). I will be looking for the following to be included in your comparison:
* k-Nearest-Neighbor with a small value of k
* k-Nearest-Neighbor with a large value of k
* weighted k-Nearest-Neighbor with a small value of k (the same one you used for the unweighted version)
* weighted k-Nearest-Neighbor with a large value of k (the same one you used for the unweighted version)
* a decision tree with default parameter values
* a decision tree, setting some kind of parameter that results in a smaller tree 

**Part 3: [1 point]** Use a Markup cell to answer the following questions:
* What algorithm performed better? kNN or Decision Trees? Why do you think this was the case?

## Rubric :ballot_box_with_check:

## :white_check_mark: Grading: 
I will update the following rubric with your grade after you have completed the assignment.
### Rubric:
| Exercise #  | Points Awarded (out of 1)  | Notes |
| --------- | ------------------- | --------- |
| 0: name? repo?            |        |    |
| 1: normalized and cleaned |        |    |
| 2.1: kNN                  |        |    |
| 2.2: wKNN          |        |    | 
| 2.3: Decision Tree |        |    |
| 3: Conclusions     |        |    |
| <b>Total           |    /6 | </b>   |
