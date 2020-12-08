# Compare RandomForest with DecisionTree by using Kaggle tutorial
This notebook compares RandomForest with DecisionTree in the points below
- Accuracy of the validation
- Precision, Recall, and F1 Score
- Important features
- ROC Curve and AUC
- Model Tree

## Use this in Kaggle notebook
- Run the command below in notebook
```
!pip install pydotplus
```
- Change the path of data
```
./data/train.csv -> /kaggle/input/titanic/train.csv
./data/test.csv -> /kaggle/input/titanic/test.csv
```

## Use this in your own PC
This notebook uses graphviz and pydotplus to visualize the decision tree<br>
To install this, run the commands below in shell
```
$ brew install graphviz
$ pip install graphviz pydotplus
```
