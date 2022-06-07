This was used to predict the housing prices using LinearRegression.

Steps:

1)Features missing more then 50% of the data were removed.

2)Removed values from columns that are not present in both training and testing data.

3)Used Ordinal Encoder to change the data from string to integers eg:- All no's become 1 and all Yes's become 0.

4)Since there are a lot of missing values Simple imputer is used to replace the missing values with the mean value of the feature.

5)LinearRegression is used to predict the prices.

6)Gradiant Desent is used to further improve the accuracy.

7)Finally the created algo is send to the kaggle for evaluation where it achieved top 7% .

