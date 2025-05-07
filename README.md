# Anjanexp4
from sklearn.model_ selection import train_test_split
x_train 

from sklearn.preprocessing import standardScaler

sclaer = StandardScaler()
x_train = scaler.fit_transform(x_train)
x_test

from sklearn import linear_model
model= linear_model.LinearRegression()
model fit (x_train, y_ train)

y_pred= model_ predict (x_test)

plt.scatter(y_pred, y_test)
