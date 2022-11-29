### Deploy-ML_Boston-House-Price
<img width="480" src="https://img.gtsstatic.net/reno/imagereader.aspx?imageurl=https%3A%2F%2Fsir.azureedge.net%2F1194i215%2Fqgd9w9a9423emtasy77sep3811i215&option=N&h=472&permitphotoenlargement=false">

### Background Project
##### The main purpose of the Machine Learning Process course is to prepare in applying end to end machine learning workflows into real-world tasks, starting from business problems to service deployments.

### Work Instructions
##### Step 1. Select Dataset
##### Step 2. Statement of Business Problems
##### Step 3. Implement Endo to End Machine Learning Workflow
##### Step 4. Perform and Summary Analysis

### Outcome Project
### * Block data preparation diagram

**Lets check the description of the dataset:**
**print(boston.DESCR):**

.. _boston_dataset:

Boston house prices dataset
---------------------------

**Data Set Characteristics:**  

    :Number of Instances: 506 

    :Number of Attributes: 13 numeric/categorical predictive. Median Value (attribute 14) is usually the target.

    :Attribute Information (in order):
        - CRIM     per capita crime rate by town
        - ZN       proportion of residential land zoned for lots over 25,000 sq.ft.
        - INDUS    proportion of non-retail business acres per town
        - CHAS     Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
        - NOX      nitric oxides concentration (parts per 10 million)
        - RM       average number of rooms per dwelling
        - AGE      proportion of owner-occupied units built prior to 1940
        - DIS      weighted distances to five Boston employment centres
        - RAD      index of accessibility to radial highways
        - TAX      full-value property-tax rate per $10,000
        - PTRATIO  pupil-teacher ratio by town
        - B        1000(Bk - 0.63)^2 where Bk is the proportion of black people by town
        - LSTAT    % lower status of the population
        - MEDV     Median value of owner-occupied homes in $1000's

    :Missing Attribute Values: None

    :Creator: Harrison, D. and Rubinfeld, D.L.

This is a copy of UCI ML housing dataset.
https://archive.ics.uci.edu/ml/machine-learning-databases/housing/

This dataset was taken from the StatLib library which is maintained at Carnegie Mellon University.

The Boston house-price data of Harrison, D. and Rubinfeld, D.L. 'Hedonic
prices and the demand for clean air', J. Environ. Economics & Management,
vol.5, 81-102, 1978.   Used in Belsley, Kuh & Welsch, 'Regression diagnostics
...', Wiley, 1980.   N.B. Various transformations are used in the table on
pages 244-261 of the latter.

The Boston house-price data has been used in many machine learning papers that address regression
problems.   
     
.. topic:: References

   - Belsley, Kuh & Welsch, 'Regression diagnostics: Identifying Influential Data and Sources of Collinearity', Wiley, 1980. 244-261.
   - Quinlan,R. (1993). Combining Instance-Based and Model-Based Learning. In Proceedings on the Tenth International Conference of Machine Learning, 236-243, University of Massachusetts, Amherst. Morgan Kaufmann.

### ![image](https://user-images.githubusercontent.com/103234274/204535867-4b01aad9-e3e8-49e9-b28e-8de42e73c080.png)

![image](https://user-images.githubusercontent.com/103234274/204535555-5fe52676-ad0c-41de-8853-6eae3d2ddb46.png)


## * Block preprocessing diagram
### X_train
![image](https://user-images.githubusercontent.com/103234274/204540025-b58a1749-7257-464b-8fee-d256b512dcb9.png)

### X_test
![image](https://user-images.githubusercontent.com/103234274/204540099-92f50c59-f9f5-4d46-9b54-64459dc3bca8.png)

## * Block diagram features engineering.
![image](https://user-images.githubusercontent.com/103234274/204537061-91fe7bca-d697-4153-be01-072b1c5359fc.png)

##### ![image](https://user-images.githubusercontent.com/103234274/204537150-20ef32e9-b60a-4ff4-827b-e312c00a9f25.png)

##### ![image](https://user-images.githubusercontent.com/103234274/204537293-e54e1a66-5c11-4c83-a677-16156f4c5034.png)

##### ![image](https://user-images.githubusercontent.com/103234274/204537394-3d170787-a05b-42e1-8324-51184e949133.png)

##### ![image](https://user-images.githubusercontent.com/103234274/204537982-ea458db5-2af6-468a-84f2-686ac89984f1.png)

##### ![image](https://user-images.githubusercontent.com/103234274/204538081-77753593-7819-4f18-910d-e8f17614a47d.png)


## * Block diagram modeling and its evaluation
### X_train
![image](https://user-images.githubusercontent.com/103234274/204538995-c68cff04-395a-4876-b72e-a07d08a572e8.png)

### X_test
![image](https://user-images.githubusercontent.com/103234274/204539358-b5afa284-31e3-4607-9550-32d75dabf4d4.png)

## * Format Message to make predictions via API
![image](https://user-images.githubusercontent.com/103234274/204544308-22a6d545-de51-49f1-9d66-8ed7c1c1f621.png)

## * Message response format of API
http://127.0.0.1:5000/predict_api

## * How to run machine learning services on a local computer:
  ## * Retraining model
  ![image](https://user-images.githubusercontent.com/103234274/204542271-95ba6ae6-656b-469b-b4c3-020eac6fda28.png)
  
  ![image](https://user-images.githubusercontent.com/103234274/204545962-92f04841-cf9e-4f2d-8421-aa7723bdab7f.png)

  ## * Running API
  ![image](https://user-images.githubusercontent.com/103234274/204542502-dae59a80-015c-421d-b256-4cf03de2000b.png)


### Software And Tools Requirements

1. [Github Account](https://github.com)
2. [HerokuAccount](https://heroku.com)
3. [VSCodeIDE](https://code.visualstudio.com/)
4. [GitCLI](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line)

Create a new environment

```
conda create -p venv python==3.7 -y
```
