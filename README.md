# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
import panda<br>
### Step2
import linear mode; from sklearn<br>

### Step3
Read the file cars.csv<br>

### Step4
Assign the values for x and y as required<br>

### Step5
Create the linearRegression model and predict the output<br>

## Program:
```
'''
developed by: Dhandeeswaran selvakumar
REGISTER NUMBER:23006838
'''
import pandas as pd 
from sklearn import linear_model

df = pd.read_csv("cars(1).csv")
x=df[['weight','volume']]
y=df['co2']
regr=linear_model.linearregression()
regr.fit(x,y)
print('coefficients:',regr.coef_)
print('intercept:',regr.intercept_)
predictedco2=regr.predict([[3300,1300]])
print('predicted co2 for the corresponding weight and volume',predictedco2)






```
## Output:
![Screenshot 2023-12-28 224824](https://github.com/dhandeeswaran2005/Multivariate-Linear-Regression/assets/147139188/bc622126-cf5f-4dd6-88a3-4d89ff59a5b6)



## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
