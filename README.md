### Deploy-ML_Boston-House-Price

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
![image](https://user-images.githubusercontent.com/103234274/204536227-feab7afe-1546-4ad0-876f-bcff5251ce82.png)

## * Block diagram features engineering.
![image](https://user-images.githubusercontent.com/103234274/204537061-91fe7bca-d697-4153-be01-072b1c5359fc.png)

##### ![image](https://user-images.githubusercontent.com/103234274/204537150-20ef32e9-b60a-4ff4-827b-e312c00a9f25.png)

##### ![image](https://user-images.githubusercontent.com/103234274/204537293-e54e1a66-5c11-4c83-a677-16156f4c5034.png)

##### ![image](https://user-images.githubusercontent.com/103234274/204537394-3d170787-a05b-42e1-8324-51184e949133.png)

##### ![image](https://user-images.githubusercontent.com/103234274/204537982-ea458db5-2af6-468a-84f2-686ac89984f1.png)

##### ![image](https://user-images.githubusercontent.com/103234274/204538081-77753593-7819-4f18-910d-e8f17614a47d.png)


## * Block diagram modeling and its evaluation
![image](https://user-images.githubusercontent.com/103234274/204538995-c68cff04-395a-4876-b72e-a07d08a572e8.png)

## * Format Message to make predictions via API


## * Message response format of API


## * How to run machine learning services on a local computer:
  ## * Retraining model
  
  
  ## * Running API


### Software And Tools Requirements

1. [Github Account](https://github.com)
2. [HerokuAccount](https://heroku.com)
3. [VSCodeIDE](https://code.visualstudio.com/)
4. [GitCLI](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line)

Create a new environment

```
conda create -p venv python==3.7 -y
```
