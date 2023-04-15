# CS5710 - Machine Learning 
<h3> (In-class Programming Assignment # 5) </h3>
Repo for Assignment 5 of Machine learning course - CRN23922



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
Video link: - https://drive.google.com/file/d/1fB8zPIpJlyrT1JYa4RSe68Rwmuk6gAAz/view?usp=sharing
</h3>


# Question 1 – 
Source code git link: https://github.com/Maruthi-UCM/CS5710-ML-Assignments/blob/main/Assignment-5/Que-1.ipynb

First we read the "CC GENERAL.csv" file using the inbulit function of pandas. Next we drop the "CUST_ID" column from the input dataset and replace all the null values present in the data with mean value of the column.

Now we initialize Principal Component Analysis component from scikit-learn inbuilt module with initializing principal components to 2. now we fit the model using the dataset we had previously.

now we apply Kmeans algorithm on the resultant dataset after applying PCA, with cluster number initialized to 2. Now we fit the classifier with the data and get the silhouette score after the doing the prediction. we obtained Silhouette score:  0.598017029765804.

Next we take the raw input dataset and perform scaling of the data and apply PCA on the data, next we apply Kmeans algorithm on the result dataframe after applying PCA. Now we get the silhouette score after the doing the prediction. 
we obtained Silhouette score: 0.46475556288778747.
 

# Question 2 – 
Source code git link: https://github.com/Maruthi-UCM/CS5710-ML-Assignments/blob/main/Assignment-5/Que-2.ipynb

First we read the "pd_speech_features.csv" file using inbuilt function of pandas. 

Now we perform scaling on the input dataframe. Next we drop the class column from the input dataframe. Next we initialize Principal Component Analysis component from scikit-learn inbuilt module with initializing principal components to 3. now we fit the model using the dataset we had after performing scaling.

Now we split the data into training and test data, next we initialize the SVM classifier and fit the model using train data. Next we find the accuracy of the model -  Accuracy as per SVM model is: 75.77092511013215


# Question 3 & 4 – 
Source code git link: https://github.com/Maruthi-UCM/CS5710-ML-Assignments/blob/main/Assignment-5/Que-3,4.ipynb

We read the "Iris.csv" file using inbuilt function of pandas. we initialize the LDA classifier and fit the model using the data.

Next we initialize PCA and do the same with the input data and we can identify differences between the LDA and PCA.

# The major difference between PCA and LDA is PCA is an unsupervised learning algorithm while LDA is a supervised learning algorithm. 
# Both LDA and PCA rely on linear transformations and aim to maximize the variance in a lower dimension. 
# However, unlike PCA, LDA finds the linear discriminants in order to maximize the variance between the different categories while minimizing the variance within the class