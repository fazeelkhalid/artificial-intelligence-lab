# artificial intelligence lab
 All solved lab of FAST NUCES Lahore campus _ 2022 Spring





# ----------------------------------------------------------------
#                                   LAB - 2
# ----------------------------------------------------------------

# Question 1.1:  
    Concatenate two lists 
    Write a program to add two lists index-wise. Create a new list that contains the 0th index item from both the list, then the 1st index item, and so on till the last element. any leftover items will get added at the end of the new list.

# Question 1.2:   
    Convert a tuple to a Dictionary. (3 Marks)
    Write a Python program to convert a tuple to a dictionary. 
    Sample Output: {'w': 2, 'r': 3}

# Question 1.3:
    Reverse a tuple (2 Marks)
    Write a Python program to reverse a tuple.

# Question 1.4:
    Sort a Tuple (3 Marks)
    Sort a tuple of tuples by 2nd item.
    Given: tuple1 = (('a', 23),('b', 37),('c', 11), ('d',29))
    Expected: (('c', 11), ('a', 23), ('d', 29), ('b', 37))

# Question 1.5:
    Create a Dictionary (5 Marks)
    Write a Python program to create a new dictionary by extracting the mentioned keys from the below dictionary.
    Sample Dictionary:
    sample_dict = {
        "name": "Kelly",
        "age": 25,
        "salary": 8000,
        "city": "New york"}
    # Keys to extract
    keys = ["name", "salary"]

# Question 1.6:
    Nested Dictionary (5 Marks)
    Write a Python program to change Brad’s salary to 8500 in the following dictionary.
    Given:
    sample_dict = {
        'emp1': {'name': 'Jhon', 'salary': 7500},
        'emp2': {'name': 'Emma', 'salary': 8000},
        'emp3': {'name': 'Brad', 'salary': 500}
    }






# ----------------------------------------------------------------
#                                    LAB - 3
# ----------------------------------------------------------------

# Question 1:
    Write a Python program to find the length of a set, apply all sets
    operations(union,intersection) and print the results,find maximum and the minimum value in a
    set,create a shallow copy of sets,check if a set is a subset of another set, remove all elements
    from a given set,check if two given sets have no elements in common.check if a given set is
    superset of itself and superset of another given set.
    set1 = {1,2,3,4,5}
    set2 = {4,5,6,7,8}

# Question 2:
    Python program to count the number of vowels using sets in a given string.
    sample output
    Input : Hello World
    Output : No. of vowels : 3
    2: Exception Handling (10 marks)

# Question 3:
    Write a function to add, mul, divide two numbers x and y. Implement exception handling
    technique
    (try..except clause) for handling possible exceptions in the scenario.







# ----------------------------------------------------------------
#                                    LAB - 4
# ----------------------------------------------------------------

# Question 1:
    For a list of integers, find square and cube for each value using lambda function.

# Question 2:
    Form a queue such that it works in FIFO order

# Question 3:
    Create a class for rectangle shape that calculates its area based upon the length and width

# Question 4:
    Write a Python class named Circle constructed by a radius and two methods which will compute the area and the perimeter of a circle.








# ----------------------------------------------------------------
#                                    LAB - 5
# ----------------------------------------------------------------

# Question 1:
    Write a Python program to filter a list of integers using Lambda.
    Original list of integers:
    [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
    Even numbers from the said list:
    [2, 4, 6, 8, 10]
    Odd numbers from the said list:
    [1, 3, 5, 7, 9]

# Question 2:
    Design a code which reads text from the file “Alphabets.txt” and stores its data in reverse order in another file. For this you may upload the given text file on Google Collab’s session and define the path as:
    file_path= ‘/Alphabets.txt’
    The same convention can be followed for defining path of the resultant file (reversed text file).

# Question 3:
    Create an iterator that returns numbers, starting with 1, and each sequence will increase by one (returning 1,2,3,4,5 etc.):

# Question 4:
    Create a class for rectangle shape that calculates its area based upon the length and width. Make a sub class of triangle called Trapezium, such that it inherits the functionality of rectangle class and implements area method of its own. Length and width should be defined in the constructor of rectangle class.
    Area
    Area of Rectangle =Length+Width
    Area of Trapezium=½*(l+w)*h

    After creation of the class, define the relevant attributes. Define a function for area computation and then a function for displaying area. Incorporate your knowledge of class and objects here.

# Question 5:
    Write a function AMCount() in Python, which should read each character of a text file STORY.TXT, should count and display the occurrence of alphabets A and M (including small cases a and m too).
    For Example:
    If the file content is as follows:
    “Updated information
    As simplified by official websites.”
    The EUCount() function should display the output as:
    A or a:4
    M or m :2







# ----------------------------------------------------------------
#                                    LAB - 6
# ----------------------------------------------------------------

# Question 1:
    4.1	NumPy is a library for the Python which adds support for large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions to operate on these arrays. Create two arrays A= [1,2,3,2,3,4,3,4,5,6] and B= [7,2,10,2,7,4,9,4,9,8]. You need to get the positions where elements of A and B match. Use a numpy function or implement your own logic. 
    Desired Outcome:
    [1, 3, 5, 7]

# Question 2:

    4.2.1   You need to findinsights about data using as many different techniques as you can. Don’t use libraries that haven’t been covered yet.

    Hint: Explore the dataset, look for the outliers, missing values, etc
    Use the automobile data set provided in the Google class room to explore EDA functions.

        1.	Check first five entries of data set.   # data.head().
        2.	Check last five entries of dataset.# data.tail().
        3.	Check the columns of data set.# data.columns.
        4.	Check unique values for each column    # data.numique().
        5.	Check the missing values for each column.   # data.isnull().sum().
        6.	Drop unnecessary data columns     # new_data= data.drop([‘column_name’,‘second_column_name’], axis=1).
        7.	Drop null value. #df.dropna(subset=df.columns,inplace=True) 

# Question 3:
    4.2.2	Data Analysis is the process of exploring and analyzing large datasets to make predictions and decisions. It involves a broad set of activities to clean, process, transform a data collection to learn from it and derive meaningful insights. Its profound application can be seen in analysing consumer behaviour in retail industry to reach out to the right customers and perform targeted marketing to increase sales. One sample dataset has been provided which lists various features of cars. You need to use your data analysis skills in answering the questions given ahead. 

        (Libraries Involved: Numpy, Pandas)
        Dataset: automobile_data.csv
        Initial Steps: 
        •	Import necessary libraries
        •	Upload/Read the csv file using pandas
        •	Review the dataset for identifying any missing values
        •	Observe the different attributes and entries

        Questions
        a.	Find the most expensive car from the dataset and display its price
        b.	Calculate total cars per manufacturer and show the result
        c.	Read the details of vehicles against Toyota manufacturer and print them
        d.	Arrange the cars according to the prices (highest-lowest) and display relevant information for first 5 rows only










# ----------------------------------------------------------------
#                                    LAB - 7
# ----------------------------------------------------------------


# Question 1
	Make a Soccer PlayerWeight PieChart (20 Marks)
    Consider the following dataset: fifa_data.csv
    Make a pie chart using Matplotlib, similar to the one shown below:

 
# Question 2	Create a Histogram, Bar-graph, and Box plot as well.










# ----------------------------------------------------------------
#                                    LAB - 8
# ----------------------------------------------------------------

# Question 1:
    Run the given code and verify the solution. Change given expression to any other expression of your choice; change the parameters to increase the efficiency of code if possible. 

# Question 2:
    Implement 8-queen problem using genetic algorithm. 
    For help regarding representation of states you may watch the following video:
    https://www.youtube.com/watch?v=vXotl0NPeUU











# ----------------------------------------------------------------
#                                    LAB - 9
# ----------------------------------------------------------------

# Question 1:
    Load and Visualize the MNIST Dataset
    To get started, you can load and visualize the dataset using this code snippet in Python:
    fromkeras.datasets import mnist
    frommatplotlib import pyplot
    # load dataset
    (trainX, trainy), (testX, testy) = mnist.load_data()
    # summarize loaded dataset
    print('Train: X=%s, y=%s' % (trainX.shape, trainy.shape))
    print('Test: X=%s, y=%s' % (testX.shape, testy.shape))
    # plot first few images
    fori in range(9):
        # define subplot
        pyplot.subplot(330 + 1 + i)
        # plot raw pixel data
        pyplot.imshow(trainX[i], cmap=pyplot.get_cmap('gray'))
    # show the figure
    pyplot.show()

# Question 2:
    Once you have made your predictions using the test split of the MNIST dataset, you are required to test the accuracy of your model on real-world data. 
    In order to achieve this task, you are required to:
    •	Make your own handwritten digits from 0-9 using paint or any other online tool available. 
    •	Use different brush strokes of different sizes to diversify your test data.
    •	Load these images as a dataset into your Python notebook. 
    •	Convert these images into grayscale as well as resize them to 28 by 28 dimensions using Python (Use any Python library like OpenCV, PIL, or scikit-image). 
    •	Provide these images to your trained digit classifier. 
    •	Observe the model predictions.
    For some inspiration, you can also visit this link: https://scikit-learn.org/stable/auto_examples/classification/plot_digits_classification.html













# ----------------------------------------------------------------
#                                    LAB - 10
# ----------------------------------------------------------------

# Question 1:
    Online Retail Dataset is attached in the file. You need to load the dataset and preprocess it for missing values and outliers. You need to scale the data for better clusters. You are then required to perform Kmeans clustering on this dataset and try with different number of clusters and visualize it. 
    
# Question 2:
    Online Retail Dataset is attached in the file. You need to load the dataset and preprocess it for missing values and outliers. You need to scale the data for better clusters. You are then required to perform Hierarchical clustering on this dataset and try with different number of clusters and visualize it.












# ----------------------------------------------------------------
#                                    LAB - 11
# ----------------------------------------------------------------

The general formula for multiple linear regression outcomes is as follows:

![plot](https://github.com/fazeelkhalid/artificial-intelligence-lab/blob/main/Lab11/1.png)

•	β0 is known as the intercept.
•	β0 to βi are known as coefficients.
•	x1 to xi are the features of the data set.
•	ε are the residual terms.

We can also represent the formula in vector notation

![plot](https://github.com/fazeelkhalid/artificial-intelligence-lab/blob/main/Lab11/2.png)

The output equation would look like:

![plot](https://github.com/fazeelkhalid/artificial-intelligence-lab/blob/main/Lab11/3.png)

To find the coefficient values, we use the ordinary least square method which minimizes the sum of the square of the residuals. The formula for resulting coefficients in vector notation is:

![plot](https://github.com/fazeelkhalid/artificial-intelligence-lab/blob/main/Lab11/4.png)


The derivation of this formula is out of the scope of this lab.If you want to learn, read more about it here: https://web.stanford.edu/~mrosenfe/soc_meth_proj3/matrix_OLS_NYU_notes.pdf

The outcome of the algorithm, beta β with a hat (^) on top, is a vector containing all of the coefficients that can be used to make predictions by using the formula presented in the beginning for multiple linear regression.

Assuming that you have a number of predictions for some observed data, how can you measure how well the model predicted the ground truth? You can measure the accuracy of how well the multiple linear regression model performs by using a metric called r squared.

![plot](https://github.com/fazeelkhalid/artificial-intelligence-lab/blob/main/Lab11/5.png)


•	yi is one value of y at index i.
•	ŷ is pronounced as y hat and is the predicted values of y.
•	y̅ is pronounced as y bar and is the average of y.

The metric measures the relationship between the residual sum of squares (RSS) and the total sum of squares (TSS). The RSS is computed as the ground truth minus the predicted ground truth, while the TSS is computed as the ground truth minus the average of the ground truth.


