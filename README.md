Task 1
1)Variable selection rules-
We studied variable selection rules in python.
2)Operators-
We studied the operaters in python i.e Arithmatic,logical,assigment,identity,bitwise,membership,camparison etc.
Data type-
We studied the different data types in python like list,tuple,set,dictionary.
1)list-
In list we study the list methods like append,copy,reverse,pop,count,index,sort,accessing etc
s3)Set-
In set we studied the method like mutable,ordered etc.
4)Dictionary-
Dictionary cantain key values pairs as its data elements.They are mutable.
5)Number-
There are three types of number i.e numeric,float,complex.
6)Strings-
In string we studied single line and multi line string,string are written in double quotes.

Task-2
1)if statement-
if statement is used when single condition is to check like number is equal to, not equal to,greater than,smaller than etc.
2)if else statement-
if else statement is used to check the two condition like positive ,negative,numeric,complex etc.
3)if elif else statement-
if elif else statement is used to check more than two condition
4)for loop-
for loop is used to execute the code in certain number of time over a range or sequence.
5)while loop-
while loop is used to execute the code in certain number of time over a particular condition,while loop continues until a particular condition is no longer met.

Task-3
In Task 3 we study Breck,pass,continuenstatement also we study User define function like statistical(mean,median,mode,variance) and logical(odd,even,grades)
1)break-
Functionality: When break is encountered inside a loop, the loop stops its execution and control is transferred to the statement immediately following the loop.
Use Case: It is useful when you want to exit a loop as soon as a certain condition is met, avoiding unnecessary iterations.
2)continue
Functionality: When continue is encountered, the current iteration is terminated, and the loop proceeds with the next iteration.
Use Case: It is useful when you want to skip over some parts of the loop but continue with the next iterations. For instance, you might want to skip over even 
numbers or any specific condition within a loop.
3)pass
Functionality: The pass statement does nothing and is used as a placeholder.
Use Case: It is useful when a statement is syntactically required, but you do not want any action to be taken. Commonly used during development as a placeholder for future code, 
in empty function or class definitions, or within conditional statements where you plan to add code later.
4)Statistical User-Defined Functions-
Statistical functions are essential for data analysis and help summarize and understand the data's properties.
Mean is use to Calculate the average of a list of numbers.median is use to Find the middle value of a list of numbers.mode is used to Find the most frequently occurring value(s) 
in a list of numbers.Variance is used to Measure the spread of numbers in a list from the mean.Standard Deviation is used to Measure the amount of variation or dispersion of a set 
of values.Percentile is used to Determine the value below which a given percentage of observations fall.range is used to Calculate the difference between the maximum and minimum 
values in a list.Interquartile Range (IQR) is used to Measure the middle 50% of the data.Covariance is used to Measure how two variables change together.Correlation Coefficientis used to Measure the strength and direction of the relationship between two variables.
5)Logical User-Defined Functions-
#is_even-Purpose: Check if a number is even.#is_odd-Purpose: Check if a number is odd.#is_prime-Purpose: Check if a number is prime.#is_palindrome-Purpose: Check if a string is a palindrome.#is_anagram-Purpose: Check if two strings are anagrams.#is_subset-Purpose: Check if one set is a subset of another.#is_superset-Purpose: Check if one set is a superset of another.#are_disjoint-Purpose: Check if two sets are disjoint.#are_equal-Purpose: Check if two lists are equal.#is_sorted-Purpose: Check if a list is sorted.

Task 4 -
#In task 4 we studied all about Numpy library.Starting with a basic introduction and ends up with
creating and plotting random data sets,and working with NumPy functions:
#NumPy is an open source project that enables numerical computing with Python. It was created in
2005 building on the early work of the Numeric and Numarray libraries.
NumPy will always be 100% open source software and free for all to use.
We studied 1) creating arrays, 2)array indexing ,3) slicing, 4)numpy data types ,5) copy or view, 6)array
shape and reshape ,7)array itterating , 8)join , split, search , sort and filter .
Here 1D array , 2D array,3D array and multidimensional array are studied.
NumPy has some extra data types, and refer to data types with one character, like i for integers, u for
unsigned integers etc.
Below is a list of all data types in NumPy and the characters used to represent them.
1)i - integer
2)b - boolean
3)u - unsigned integer
4)f - float
5)c - complex float
6)m - timedelta
7)M - datetime
8)O - object
9)S - string
10)U - unicode string
11)V - fixed chunk of memory for other type ( void )
#Then we learn how to generate Random Number.
NumPy offers the random module to work with random numbers.
#Data Distribution is a list of all possible values, and how often each value occurs.
Such lists are important when working with statistics and data science.

The random module offer methods that returns randomly generated data distributions.
Then we see that generation of random numbers from particular distribution and visuallisation of that
distribution .like normal distribution ,binomial, poisson , uniform, logistic, multinomial, exonential, chi-
square,rayleighs,pareto,zipf distributions
To plot the graph of distribution
#from numpy import random
#import matplotlib.pyplot as plt
#import seaborn as sns
Then we use ufuncs stands for &quot;Universal Functions&quot; and they are NumPy functions that operate on the
ndarray object.
We studied ufunctions like simple arithmatic , rounding decimals, logs, summations, products,
differences, finding lcm,gcd, trignometric functions, hyperbolic function and set operations.

Task 5 -
In task 5 we studied the pandas library in python.
#we see creation of series and their operation .A Pandas Series is like a column in a table. It is a one-
dimensional array holding data of any type.
#Then we see the data frame creation using dictionary and matrix ,and how to to read data in csv and
xlsx file in panda library in python.
#Data frame operation -
In data frame operation different methods of operation like value count , apply, unique,
nunique,describe,merge,sort etc
#selection-
In selection we see that how to select data frame column and row by using (loc,iloc) function .
#In pandas, selecting data from a DataFrame involves specifying which columns and/or rows you want
to work with.
#we can use several methods for selection, including .loc, .iloc, and boolean indexing.
Also conditional selection with how to add , delete and update column in the data frame .Also seen that
indexing and removing indexing by set reset function.
Operation between two columns like addition , substraction, multiplication and division are carried out .
#missing values
In missing values we studied checking missing values, how to drop missing values by row and by column
and also filling missing values by mean ,median etc.By using function
#Using isnull(): This method returns a DataFrame of the same shape with boolean values indicating
whether the data is missing (True) or not (False).
#we can drop rows that contain any missing values using dropna(axis=0):
#we can fill missing values with a specific value using fillna(value):

Task 6 -
In task 6 we studied the matplotlib and seaborn library.
Matplotlib is a graph plotting library in python that serves as a visualization utility.
#Pyplot
Most of the Matplotlib utilities lies under the pyplot submodule, and are usually imported under the plt
alias:
#import matplotlib.pyplot as plt
#Plotting x and y points
The plot() function is used to draw points (markers) in a diagram.
In matplotlib we study matplotlib plotting with markers,lines,labels,grid,subplot,scatter plot,bars,
histograms and pie charts .
#seaborn libraray-
Seaborn is a powerful and versatile data visualization library in Python, built on top of the popular
Matplotlib library.
It provides a high-level interface for drawing attractive and informative statistical graphics.
Seaborn is particularly useful for visualizing complex datasets and for creating aesthetically pleasing
visualizations with minimal code.
#import seaborn as sns
#In seaborn library we see different types of plotting of graphs such as distribution plot, box plot, violin
plot, bar plot,scatter pot,
line plot, heatmap, pair plot ,facet grid, regression plot , residual plot.





