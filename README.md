# Implementation-of-Decision-Tree-Regressor-Model-for-Predicting-the-Salary-of-the-Employee

## AIM:
To write a program to implement the Decision Tree Regressor Model for Predicting the Salary of the Employee.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm:
1. Import the standard libraries.
2. Upload the dataset and check for any null values using .isnull() function.
3. Import LabelEncoder and encode the dataset.
4. Import DecisionTreeRegressor from sklearn and apply the model on the dataset.
4. Predict the values of arrays.
5. Import metrics from sklearn and calculate the MSE and R2 of the model on the dataset.
6. Predict the values of array.
7. Apply to new unknown values.
## Program:
```
/*
Program to implement the Decision Tree Regressor Model for Predicting the Salary of the Employee.
Developed by: DHARSHAN D
RegisterNumber: 212223230045

import pandas as pd
data=pd.read_csv("spam.csv",encoding='Windows-1252')
data.head()
data.tail()
data.info()
data.isnull().sum()
x=data['v2'].values
y=data['v1'].values
y.shape
x.shape
from sklearn.model_selection import train_test_split
x_train,x_test,y_train,y_test=train_test_split(x,y,test_size=0.2,random_state=0)
x_train.shape
y_train.shape
x_test.shapefrom sklearn.feature_extraction.text import CountVectorizer
cv = CountVectorizer()
x_train = cv.fit_transform(x_train)  
x_test = cv.transform(x_test)
x_train.shape
from sklearn.svm import SVC
svc=SVC()
svc.fit(x_train,y_train)
y_pred=svc.predict(x_test)
y_pred
x_train.shapex_train.shape
*/
```

## Output:
## HEAD:
![Screenshot 2024-10-29 135211](https://github.com/user-attachments/assets/4eb89322-5372-4b72-a34e-179aea7dda14)

## MSE:
![Screenshot 2024-10-29 135256](https://github.com/user-attachments/assets/fc016a96-17a3-433a-9c70-70185849b281)

## R2:
![Screenshot 2024-10-29 135341](https://github.com/user-attachments/assets/2b661047-5a8d-4dbc-a683-2c028e3ec59f)

## Predicted:
![Screenshot 2024-10-29 135347](https://github.com/user-attachments/assets/994d2d3b-9181-4a9d-af0c-1cecefa875f2)


## Result:
Thus the program to implement the Decision Tree Regressor Model for Predicting the Salary of the Employee is written and verified using python programming.
