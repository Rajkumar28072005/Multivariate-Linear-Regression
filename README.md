# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
<br>

### Step2
<br>

### Step3
<br>

### Step4
<br>

### Step5
<br>

## Program:
```
'''
developed by:MOHAMED FAROOK S
REGISTER NUMBER:2314058
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
![image](https://github.com/MOHAMEDFAROOK2005/Multivariate-Linear-Regression/assets/150319482/3465038b-5a2c-4455-8fa4-72844e1ef9af)



## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
