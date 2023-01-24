# Datacollection-and-Pre-processing

# 1.Data Standardization
What is standardization
In statistics and machine learning, data standardization is a process of converting data to z-score values based on the mean and standard deviation of the data.

The resulting standardized value shows the number of standard deviations the raw value is away from the mean.

Basically each value of a given feature of a dataset will be converted to a representative number of standard deviations that it’s away from the mean of the feature.

This will allow us to compare multiple features together and get more relevant information since now all the data will be on the same scale.

The standardized data will have mean equal to 0 and the values will generally range between -3 and +3 (since 99.9% of the data is within 3 standard deviations from the mean assuming your data follows a normal distribution).

Let’s take a look at the z-score formula:







# 2.In the Handling of dataset
We have two types of method.
1. Imputation
2. Dropping

# Imputation
In the imputation method we control the data and also we assume data here we have three types of method.
1. Mean
2. Mode
3. Median 

# Dropping
This method we used for large no. of dataset let we have 20000 line of data and we find in 10000 line having NaN Values so we drop the all NaN values. 

# 3.Label Encoding
 
Breast Cnacer Data Labeling 
In this we have two types of dependecies of daignosics
B- Benign(early stage) it is converting as 0 because in alphabet B is frist 
M- Malignan(last stage) it is converting as 1 because in alphabet M is second

In the Label encoding we have some data in (variable LabelEncoder) we have converted as target variable and all are changes into 0 and 1

Iris Data Labeling 
In this we have three types of dependecies of Species
Iris-setosa- it is converting as 0 because in alphabet setosa is frist  
Iris-versicolor- it is converting as 2 because in alphabet versicolor is second
Iris-virginica- it is converting as 3 because in alphabet virginica is third

In the Label encoding we have some data in (variable LabelEncoder) we have converted as target variable and all are changes into 0, 1 and 2

