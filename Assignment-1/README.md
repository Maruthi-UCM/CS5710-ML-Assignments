# CS5710 - Machine Learning 
<h3> (Assignment # 1) </h3>
Repo for Assignment1 of Machine learning course - CRN23922



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
Video link: - https://drive.google.com/file/d/1jIYHiKTECZw0pIOizM3_Zf5FKTf_vjS4/view?usp=sharing
</h3>


# Question 1 – 
Source code git link: https://github.com/Maruthi-UCM/CS5710-ML-Assignments/blob/main/Assignment-1/Que-1.ipynb

Initialize the list ‘ages’ as given, ages = [19, 22, 19, 24, 20, 25, 26, 24, 25, 24]
 
To sort the given array, we can use inbuilt function ‘sorted()’ on the list we initialized previously
 
Next, to find the minimum age and maximum age among the list. We can use ‘min()’ and ‘max()’ functions on the list.
 
Next to find the Median of the list and Average age of the list, we can import Statistics module and use ‘statistics.median()’ and ‘statistics.mean()’ methods on the list to find median and average respectively.

Next, to find the range of the list we can use the previously found minimum and maximum values of the list.
 

# Question 2 – 
Source code git link: https://github.com/Maruthi-UCM/CS5710-ML-Assignments/blob/main/Assignment-1/Que-2.ipynb

First, we create an empty dictionary ‘dog’ using the empty curly braces ‘{}’ or inbuilt function ‘dict()’ with no arguments. Then to add different key-value pairs for ‘name, color, breed, legs, age’ to the dictionary we assign them using ‘=’ operator.
 
Now to create a ‘student’ dictionary with ‘first_name, last_name, gender, age, marital status, skills, country, city and address’ as keys for the dictionary. We can initialize it using curly braces ‘{}’ and key values separated by colon ‘:’ between the braces.
We can use inbuilt ‘len()’ function to find the length of the dictionary.
 
To value of the key ‘skills’ from the student dictionary we can use square brackets ‘[]’ and give the specific key in the square braces. 
To find the data type of a variable we can use inbuilt function ‘type()’.
To modify the value of a key in the dictionary we can use ‘=’ operator and assign it to the new value. Here since the value of key “skills” is a list we can use ‘.append()’ method for adding one item at a time. To add multiple values to the list we can use ‘+’ operator.
 
To get the list of keys and values from a dictionary, we can use ‘.keys()’ and ’.values()’ methods. They return the iterable object of types ‘dict_keys’,’dict_values’ respectively. To convert them into a list we use inbuilt function ‘list()’.
 

# Question 3 – 
Source code git link: https://github.com/Maruthi-UCM/CS5710-ML-Assignments/blob/cf4ef06b3f1c187f61e7ff8ee5eb1b43bf5e11dc/Assignment-1/Que-3.ipynb

To initialize a tuple, we can use parenthesis ‘()’ and give values inside the braces separated by ‘,’. Even if there is only one value, we need to give a comma’,’ after the value. Here we have initialized two tuples ‘brothers’, ‘sisters’
 
Next to create a tuple ‘siblings’ by combining the previous two tuples, we can use ‘+’ operator and assign it to the variable. To find number of siblings i.e., no of items in tuple ‘siblings’ we can use ‘len()’ function.
 
To create ‘familiy_members’ tuple with ‘father, mother and siblings’, we can use previously created siblings tuple and use ‘+’ operator with the new values father and mother with in ‘()’ braces.
 


# Question 4 – 
Source code git link: https://github.com/Maruthi-UCM/CS5710-ML-Assignments/blob/cf4ef06b3f1c187f61e7ff8ee5eb1b43bf5e11dc/Assignment-1/Que-4.ipynb

First, we initialize the given sets ‘it_companies, A, B’ and list ‘age’. We can create a set using curly braces ‘{}’ or we can use ‘set()’ function. To create a list we can use square braces ‘[]’ or ‘list()’ function.
Next to find the length of the set ‘it_companies’, we can use ‘len()’ function. To add single value to the set, we can use ‘.add()’ method of the set with value given in ‘()’ braces.
To add multiple values at the same time we can use ‘.update()’ method or ‘|’ operator. To remove a value from the set we can use ‘.remove()’ method or ‘.update()’ method on the set.
 
Difference between ‘remove()’ method and ‘discard()’ method:
Both the methods ‘remove()’ and ‘discard()’ are used to remove a specific object from a set. When we use ‘remove()’ function to remove a specific object, the function will raise a 'key error' exception if that object is not present in the set, whereas the ‘discard()’ method will not raise an exception.
Next to join sets A & B, we can use ‘.union()’ method on either of sets by passing other as parameter for the method or ‘|’ operator between the sets. To get intersection sets A & B, we can use ‘.intersection()’ method on either of sets by passing other as parameter for the method or ‘&’ operator between the sets.

To find if set A is a subset of set B, we can use ‘.issubset()’ method on set A by passing set B as parameter. It returns a Boolean value.

To check if sets A & B are disjoint sets, we can use ‘.isdisjoint()’ method on one the set and passing the other as parameter to the method. The method returns a Boolean value.
 
To find symmetric difference between two sets A & B, we can use ‘.symmertic_difference()’ on the sets by passing one as parameter to other’s method or we can ‘^’ operator to get the same.
To delete a set we can ‘del()’ function and pass the set as parameter to it.
 
To convert a list into a set we can using ‘set()’ function and pass the list as the parameter to it. In a set, duplicates are not allowed so if there are any duplicates they will be removed. 
Here also since the list ‘age’ has some duplicates we have difference in lengths when it is a set and list. 
The difference here is 3 (since values ‘24, 25’ are repeated in the list).


# Question 5 – 
Source code git link: https://github.com/Maruthi-UCM/CS5710-ML-Assignments/blob/cf4ef06b3f1c187f61e7ff8ee5eb1b43bf5e11dc/Assignment-1/Que-5.ipynb

First we initialize a variable ‘radius’ by assigning the input provided by the user to it.
To read the input we can use ‘input()’ function in python. 
This will read the given input as a string to change it to any required data type we need to perform type casting.
 
Next, to find the area of the circle (Pi*radius*radius) we can use the mathematical operators and assign it to a variable ‘area’.
 
Similarly, we can use mathematical operators and find the circumference of the circle and assign it to a variable.
 

# Question 6 – 
Source code git link: https://github.com/Maruthi-UCM/CS5710-ML-Assignments/blob/cf4ef06b3f1c187f61e7ff8ee5eb1b43bf5e11dc/Assignment-1/Que-6.ipynb

First, we initialize the given string and assign it to a variable. After that to find the number of words present in the given string we use ‘.split()’ method of the string and split using space character as a delimiter.
This will give us an iterable object with all the words present in the string. We can use ‘list()’ function and type cast the object into list type.
Now, to get the number of unique words present in the string we can use ‘set()’ function on the list we had previously and find the length of the set using ‘len()’ function on the set.

 

# Question 7 – 
Source code git link: https://github.com/Maruthi-UCM/CS5710-ML-Assignments/blob/cf4ef06b3f1c187f61e7ff8ee5eb1b43bf5e11dc/Assignment-1/Que-7.ipynb

Here first we initialize the string and assign it to a variable. We can use double quotes (“”) for creating a string. 
Now to achieve the format specified we need to escape sequences in the string. To achieve a tab space, we can give ‘/t’ escape sequence and to achieve a new line we can use’/n’ escape sequence in the string.
Whenever the complier reads a ‘/’ it assumes it as an escape sequence and instead of printing the character as it is it does the required action associated to the escape sequence.

 

# Question 8 – 
Source code git link: https://github.com/Maruthi-UCM/CS5710-ML-Assignments/blob/cf4ef06b3f1c187f61e7ff8ee5eb1b43bf5e11dc/Assignment-1/Que-8.ipynb

First, we initialize the value for radius, next we calculate the area of circle using the mathematical operators and assign it to the variable ‘area’.
Now, to print the output in the given format we make use of string method ‘.format()’. Whenever we need to print some values of non-string datatype variables in a string we can make use of this method.
Here we can use ‘{}’ curly braces as place holders for the variable values and pass the variables in order to the format method. 
We can also specify the position of the variable need to be used in the curly braces like ‘e.g.: {1}’ this will take second variable passed to the method and place it in that position in string.
 


# Question 9 – 
Source code git link: https://github.com/Maruthi-UCM/CS5710-ML-Assignments/blob/cf4ef06b3f1c187f61e7ff8ee5eb1b43bf5e11dc/Assignment-1/Que-9.ipynb

First, we read the number of students present from the user as an input and assign it to a variable ‘N’ using ‘input()’ function.
Now, we initialize an empty list ‘weights_lb’ to store weights of N students.
Next, we read N inputs from the user for the weights of the students in lbs and add them to the empty list we had previously by using ‘.append()’ method and reading input using ‘input() function.
 
Now to store the weights in kgs we initialize another empty list ‘weights_kg’.
Next by using a for loop and iterating over each element in ‘weights_lb’ list we can access the values in the list. In the loop we can do mathematical conversion of the weight from lbs to kgs by multiplying the value by ‘0.45359237’ using ‘*’ operator. 
To store these values (in kgs) to the list ‘weights_kg’ we can make use of ‘.append()’ method and store each value respectively after conversion from pounds to kilos.
 

# Question 10 –
![image](https://user-images.githubusercontent.com/123269364/214142590-66b270b8-725c-480b-88f5-fc4cb252f6e3.png)


Given data set and the respective labels are as following:
Data = [1,2,3,6,6,7,10,11]
Labels = [0,0,1,1,1,0,0,0] let’s assume ‘dots’ as ‘class 0’ & ‘X’ as ‘class 1’

1.	Now, lets divide the data in to two equal parts one for training and one for testing.
Training_data = [1,3,6,7]
Test_data = [2,6,10,11]

With given KNN classifier, K=3 we need to identify K samples closest to the test data and assume the label of the majority as the test data’s label.

Distance can be calculated by Euclidean distance: square_root((x1-x2)**2 + (y1-y2)**2)
Here in our case since y-axis is not present, we can assume y1=y2=0.
So, the distance will be |x1-x2|.

For test data ‘2’. Distances will be:	d(2,1) = |2-1| = 1
d(2,3) = |2-3| = 1
d(2,6) = |2-6| = 3
d(2,7) = |2-7| = 4
Now the closest K (K=3) neighbors of ‘2’ are 1,3,6 and majority are of ‘class 1’. So, we assign ‘class1’ to test sample ‘2’.

Similarly, we find for rest of the test data 6, 10, 11.
For test data ‘6’. Distances will be:	d(6,1) = |6-1| = 5
d(6,3) = |6-3| = 3
d(6,6) = |6-6| = 0
d(6,7) = |6-7| = 1
Now the closest K (K=3) neighbors of ‘6’ are 3,6,7 and majority are of ‘class 1’. So, we assign ‘class1’ to test sample ‘6’.

For test data ‘10’. Distances will be:	d(10,1) = |10-1| = 9
d(10,3) = |10-3| = 7
d(10,6) = |10-6| = 4
d(10,7) = |10-7| = 3

Now the closest K (K=3) neighbors of ‘10’ are 3,6,7 and majority are of ‘class 1’. So, we assign ‘class1’ to test sample ‘10’.

For test data ‘11’. Distances will be:	d(11,1) = |11-1| = 10
d(11,3) = |11-3| = 8
d(11,6) = |11-6| = 5
d(11,7) = |11-7| = 4
Now the closest K (K=3) neighbors of ‘11’ are 3,6,7 and majority are of ‘class 1’. So, we assign ‘class1’ to test sample ‘11’.

So, the predicted labels for the test data are predicted_labels = [1,1,1,1].
However actual labels are actual_labels = [0,1,0,0].

2.	The confusion Matrix for the predictions of test data is as follows:

		                      Predicted labels
		                     Class 0	Class 1
Actual labels Class 0	      0        3
              Class 1	      0        1


So, the True Positives TP = 1
	True Negatives TN =0
	False Positives FP =3
	False Negatives FN =0

From this we can get, Positives P = TP+FN = 1
			Negatives N = TN+FP = 3

Now, to calculate accuracy, we can use formula Accuracy = (TP+TN)/(P+N)
							           = ¼ = 0.25 or 25%
To calculate Sensitivity (true positive rate TPR), we can use the formula 
Sensitivity (TPR) = TP/(TP+FN) = TP/P
		   = 1/1 = 1
	To calculate Specificity (true negative rate TNR), we can use the formula
Specificity (TNR) = TN/(FP+TN) = TN/N
    = 0 (since there are no true negatives in this case)

Usually, based on test and training datasets chosen the predictions and the accuracy, sensitivity, specificity values vary accordingly.



