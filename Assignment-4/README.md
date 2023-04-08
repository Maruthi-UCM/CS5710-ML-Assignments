# CS5710 - Machine Learning 
<h3> (In-class Programming Assignment # 4) </h3>
Repo for Assignment 4 of Machine learning course - CRN23922



<h3>
NAME: - Maruthi Pavan Surya Kande
</h3>
<h3>
Program: - MS in computer science
</h3>
<h3>
course - CS5710 MACHINE LEARNING
</h3>
<h3>
Professor: - Muhammad Zubair Khan
</h3>
<h3>
700#: - 700747215
</h3>
<h3>
CRN: - CRN23922
</h3>
<h3>
Video link: - https://drive.google.com/file/d/1p-zgu3qfz7QrKakfSEG1lgB7pN9E7ZW5/view?usp=sharing
</h3>


# Question 1 – 
Source code git link: https://github.com/Maruthi-UCM/CS5710-ML-Assignments/blob/main/Assignment-4/Que-1.ipynb

We read given 'data.csv' file using pandas inbulit function read_csv() function. next to get the statistical description of the data we can use pandas inbuilt function '.describe()' function.
To find if there any null values are present in the dataframe. we can replace the null values with mean of the column data we can use '.fillna()' function of pandas.
To get the aggregate of the data we can inbuilt functions: min, max, mean, count.
Next to filter the data frame using a condition we give the filtering condition in '[]' and assign it to new variable.
Next to remove a column from the dataframe we can use .drop() function.
To convert datatype of the column we can use '.astype()' inbuilt pandas function.
To generate the scatter plot using the data we can use matplot function using'.scatter()' function and passing dataframe as parameter to it.
 

# Question 2 – 
Source code git link: https://github.com/Maruthi-UCM/CS5710-ML-Assignments/blob/main/Assignment-4/titanic.ipynb

We read given 'titanic.csv' file using pandas inbulit function read_csv() function.

To Find the correlation of the data in the dataframe we can use '.corr()' function. We got correlation between surivived and sex columns is '-0.54' We can drop this feature.

To get visualizations for the correlation data we can use inbuilt functions from seaborn module to generate graphs with the data we found previously.

Now to do classification using Naive bayes classifier we can use scikit-learn module. First we read the train data and test data.
Next we classify data using 'GaussianNB()' method, we have get the lables and classify the train and test data and pass the train data to classifier function to train the model.

Now to get classification report, confusion matrix and accuracy score we can use scikit learn module's functions for the same.

# Question 3 – 
Source code git link: https://github.com/Maruthi-UCM/CS5710-ML-Assignments/blob/main/Assignment-4/glass.ipynb

We read given 'glass.csv' file using pandas inbulit function read_csv() function.

To Find the correlation between the columns dataframe we can use '.corr()' function.
To get visualizations for the correlation data we can use inbuilt functions from seaborn module to generate graphs with the data we found previously.

Now to do classification using Naive bayes classifier we can use scikit-learn module. we have to classify the data from glass dataframe into training and testing data. Next we classify data using 'GaussianNB()' method, we have get the lables and classify the train and test data and pass the train data to classifier function to train the model.

Now to get classification report, confusion matrix and accuracy score we can use scikit learn module's functions for the same.

Now we can do the classification using LinearSVM classifier using the inbuilt method for the same from scikit-learn module.we can use the lables and classify the train and test data and pass the train data to classifier function to train the model.

Now to get classification report, confusion matrix and accuracy score we can use scikit learn module's functions for the same.

We got the accuracy for naivebayes classifier as '0.83' and for LinearSVm classifier is '0.69'. the accuracy is better achieved while using Naivebayes classifier.