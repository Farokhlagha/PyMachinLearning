# PyML42_KNN_ANSUR II
This program uses pandas, numpy, sklearn and matplotlib libraries.

## 1- k-Nearest Neighbors (KNN)
Implement the k-Nearest Neighbors (kNN) algorithm for 3 classes,
 
for example: 🍎 Apple, 🍌 Banana, 🍉 Watermelon.

## 2- K-Nearest Neighbors in ANSUR II dataset

ANSUR II![](https://raw.githubusercontent.com/Farokhlagha/PyMachinLearning/main/PyML42_KNN_ANSUR%20II/output/ANSUR%20II.png)

[Ansur II](https://www.openlab.psu.edu/ansur2/)

[Kaggle](https://www.kaggle.com/datasets/seshadrikolluri/ansur-ii)


Preprocess dateset for converting unit of weight, unit of height and datatype of gender.

Show heights for women and men on same plot.
A. Why is the data of men higher than the data of women?
‌B. Why is the data of men more right than the data of women?

Split dataset to train and test datasets (%80 for train and %20 for test):
```
from sklearn.model_selection import train_test_split
```
Implement and fit your object oriented KNN algorithm on the train dataset.

Evaluate your KNN algorithm on the test dataset with different values of k = 3, 5, 7, ...
and write accuracy results as a table in readme.md.

Calculate confusion matrix for test dataset.

Fit the scikit-learn KNN algorithm on the train dataset:
```
from sklearn.neighbors import KNeighborsClassifier
```
Evaluate the scikit-learn KNN algorithm on the test dataset. Make sure your accuracy is equal to scikit-learn's accuracy.

Calculate confusion matrix using 
[scikit-learn](https://www.w3schools.com/python/python_ml_confusion_matrix.asp)

### How to Install
Run following command:
```
pip install -r requirement.txt
```

### How to Run
execute this command in terminal:
```
python ansur II.ipynb
```

### Result
confusion![](https://raw.githubusercontent.com/Farokhlagha/PyMachinLearning/main/PyML42_KNN_ANSUR%20II/output/ansur_confusion_matrix.png)

hist![](https://raw.githubusercontent.com/Farokhlagha/PyMachinLearning/main/PyML42_KNN_ANSUR%20II/output/ansur_hist.png)



