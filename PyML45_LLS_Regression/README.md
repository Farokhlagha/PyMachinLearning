# PyML45_LLS_Regression
This program uses pandas, numpy, sklearn and matplotlib libraries.

## 1- train_test_split

Implement the train_test_split function from scratch.

## 2- Tehran House Price 🏠
[ House Price Prediction](https://www.kaggle.com/code/soheiltehranipour/tehran-divar-ir-house-price-prediction)

Show the address of the 5 most expensive houses

Use all possible features for X_train

Split your dataset to train and test with train_test_split function

Fit the LLS model on your training dataset

Evaluate your model on your test dataset using MAE, MSE and RMSE loss functions. Why the MSE metric is a very large number?

Compare your result with Scikit-Learn's results
```
from sklearn.linear_model import LinearRegression
from sklearn.linear_model import RidgeCV  # Linear least squares with l2 regularization
```

## 3- Dollar Rial Price 💰
Divide dataset to Ahmadinejad, Rouhani and Raisi's presidency

Show the highest dollar price in Ahmadinejad, Rouhani and Raisi's presidency respectively

Show the lowest dollar price in Ahmadinejad, Rouhani and Raisi's presidency respectively

Split each dataset to train and test with train_test_split function

Fit the LLS model on each training dataset

Evaluate each model on test dataset using MAE loss function in Scikit-Learn
```
from sklearn.metrics import mean_absolute_error
```

### How to Install
Run following command:
```
pip install -r requirement.txt
```

### How to Run
execute this command in terminal:
```
dollar_rial.ipynb
```

### Result
Ahmadinejad![](https://raw.githubusercontent.com/Farokhlagha/PyMachinLearning/main/PyML44_LinearLeastSquares_LLS/output/performance.png)

Rouhani![](https://raw.githubusercontent.com/Farokhlagha/PyMachinLearning/main/PyML44_LinearLeastSquares_LLS/output/performance.png)

Raisi![](https://raw.githubusercontent.com/Farokhlagha/PyMachinLearning/main/PyML44_LinearLeastSquares_LLS/output/performance.png)
