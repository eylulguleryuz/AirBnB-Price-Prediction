# AirBnB Price Prediction
A project that explores AirBnB data, refines it and then creates an ANN model to predict the price of a given listing with an accuracy of up to 99.54%.

## The dataset
The dataset is acquired from: https://www.kaggle.com/datasets/arianazmoudeh/airbnbopendata
It originally contained numeric (integer and real) and categorical values and consisted of 26 columns and 102599 rows.

## Steps taken
```
Missing values, cardinality problems, and outlier problems were fixed in the first part.
```
```
Later, data was plotted, and grouped and histograms were created to find possible correlations.
```
```
In the second part, an Artificial Neural Network model was created and trained to predict the price of a given listing. 
A 10-fold cross-validation method was applied to determine the average performance of the model.
```

Initial architecture of ANN was as follows:
![image](https://github.com/eylulguleryuz/AirBnB-Price-Prediction/assets/20710032/7140820a-d787-4950-ae84-8db8219d488d)

And finally, some measures were taken to increase the average performance of the model. These measures included:
```
Changing learning rate
Changing activation function
Changing ANN structure
```
And the results are as follows:
![image](https://github.com/eylulguleryuz/AirBnB-Price-Prediction/assets/20710032/0d8fe469-9f85-4cd0-ad0a-f6e83983e758)

