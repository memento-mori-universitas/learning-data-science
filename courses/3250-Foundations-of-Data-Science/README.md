## Day 1

Instructor:
Larry Simon
larry.simon@utoronto.ca
larry.simon@inflectiongroup.com
416-427-1950
@LarryASimon



Course that are offered:

- 3251 - Statistics (Similar to a university statistics course)
Bayesian Stats

- 3252 - Systems & Tools
Course in distributed systems - Teach wants to call this course Data Engineering.
Tools: Hadoop & Spark

- 3253 - Data Mining
This is really a machine learning course


TV Show - Halt and Catch Fire

Spooky Stuff - search on Github



Next Week:

- Introduction to R

- Check Blackboard for instructions on how to Set up R

- Jupiter for R.


Homework:

- R in a Nutshell (Chapters 1 to 4)


## Day 2

Interesting article:
https://www.edx.org/course/reliable-distributed-algorithms-part-1-kthx-id2203-1x#!


*Book*:
Algorithms + Data Structures = Programs
https://en.wikipedia.org/wiki/Algorithms_%2B_Data_Structures_%3D_Programs


Three main style of programming languages:

- Imperative - (C)
  - Say step by step how the work needs to be done.
  - You can write very efficient algorithms.

- Object oriented - (Java)
  - Associate a particular code with that data structure.
  - The idea was to convert the language into something humans are familiar with.

- Functional(Lisp)/Declarative(Sql)
    - It much easier to write concurrent programs that run across a cluster.
    - Rather than try to describe the step prescriptively, you write down the end result first.
    - Example, in sql you just write down the results you want and sql figures out how to get that result.


Teacher mentioned that people are shying away from inheritance and going towards composition.

*Good reading material*
https://www.thoughtworks.com/insights/blog/composition-vs-inheritance-how-choose


A vector is an order collection of values, they all have to be at the same kind. A vector is a one dimensional  array.

### Data Frame


The cell inside a table is called an observation.
Once column is a special column that holds a function.

|         |            |   |
| ------------- |:-------------:| -----:|
| Dependent variables| Dependent variables| Independent variable - target|


Dependent variables and one independent variable. The columns are often represented

A data frame is a specific data set to work in a “table” structure.

Function is a first class object in R. Things you can do is pass a function to a function.

In order to have Jupyter Notebook running I had to install to following irkernal separately. 

https://irkernel.github.io/installation/


Next Week:

- Example in Blackboard to look at with R code.

## Day 3

RODBC → Standardized syntax for accessing database.

A **random variable** is a placeholder for an observation. Every time we do an observation the variable may change.

Probability: There is a bunch of variables that affect the outcome. However we do not know all the variables or we do not know the value of the variables. 
  - Probability is relative to the observer. 



Type of variables:

- Continuous - They take values in the continuum, for example weight.
- Categorical - We take values for small set of different alternatives( in R we called them factors). 
A coin with two sides = Nominal in value, heads and tails are equal in order.
Child/Youth/Adult/Senior = A soft ordinal numbers, there is an order, but the order is unclear)



**Data Distributions**:

How we describe the distribution a set of numbers. You can describe it either numerical or graphically.



**Summary Statistics**:


_Mean_: A single number that is a weighted averaged. Meaning, the each observation does not overlap but when it ovelaps that value is given a greater strength.



_Medium_: The center value - A measure of where the center of the distribution is. 



A robust statistic - Something that is not influenced much by outliers.



_Variance_: Is the expectation of the squared deviation. It is calculated as the square of the distance from the mean. (Square)



_Standard deviation_: The square root of the variance.



_Range_: The difference between max and min values. (Linear)



_Interquartile range(IQR)_: The difference between the 75% and 25%. (Robust statistic) The robust equivalent of standard deviation.



_Normal Distribution_: E -x(square)



At the heart of it correlation is the sum of two things multiplied together.


A signal is data in time.


Presentation topics from last year:
- How cost of crude oil affects airline stocks
- Forecasting stock price
- Job recommendation engine
- Predicting medical appointment no show


Homework

- Assignment #1 -on paper, beginning of class
- Chapter 5-9, 11

Links of the weeks:
https://www.wolframalpha.com/


## Day 4

**Data visualization**
- Jer Thorpe - NY Times
    - http://nytlabs.com/projects/cascade.html
    - http://nytlabs.com/projects/openpaths.html
    - Think of data in a human context

- Giorgia Lupi - http://www.accurat.it/ - Data Visualization Advertising Company
  - Strata Conference - Recommended Big Data Conference.



**Visualization in R**


_Histogram_ = counting the instances of data

_Bar Chart_ = counting the categorical values

_Bi-variate Plots_ = correlation between things.


Recommend reading for learning statistics:
https://www.openintro.org/stat/textbook.php?stat_book=os



ggplot2 - Cheetsheet
https://www.rstudio.com/wp-content/uploads/2015/03/ggplot2-cheatsheet.pdf



This data set is very useful for example as a classification algorithm.
https://en.wikipedia.org/wiki/Iris_flower_data_set



Books:
- Beautiful Visualization
  http://www.rioleo.org/docs/Oreilly.Beautiful.Visualization.Jun.2010.pdf
- R Graphics Cookbook → Handy reference book.


Next week:

Assignment 2 Due

## Day 5

Correlation is the heart of machine learning. We are interested in finding patterns in data.



#### Machine Learning

Machine learning is when you have a target or outcome and we compare it with some independent variables in order to predict the outcome based on new variables being introduced to the dataset.



Most machine learning falls into **supervise learning**.


- Machine Learning = Electrical Engineers talked to statisticians and talked to CS. Statistical approach.


- Artificial Intelligent = Rules based systems definition in the 1970’s. Logical Inference approach. 
Usually AI falls into unsupervised learning.


- Deep Learning = Neural Nets it was called before -  Decision maker units affect others in different layers.


Some people are calling the whole thing Machine Intelligence.



**Unsupervised Learning: Clusters**


K-Mean Algorithm to determine which are the clusters:


1. Guess the centeroid of the cluster
2. Measure the distance for the candidate center to each point. We repeat that for every point
3. We sort them and then put them in buckets
4. We move the centeroid to the mean difference between the two centeroid.
5. We repeat this process until the centeroid stops moving



Regression = numerical prediction


**Overfitting** = Forcing your function to meet your data but in the act causing the function to do unnatural things.

## Day 6

Python books:

How to think like a Computer Science - Python

Good practice website:
http://anandology.com/python-practice-book/index.html


Assignment #3:

- kNN - k-Nearest Neighbours


## Day 8


**Regression** = trying to predict a numeric value.

**Classification** = trying to predict the label of value based on the category.

In a dataset, having more row is a good thing, having more columns is a bad thing. Every column is a new dimension. You need about 30% as much more data for each column that you have.



__Robust Statistic__: A statistic which is not as influenced by outliers.



There are two libraries that are popular for machine learning:


- Statsmodels = older library more stats
  - http://www.statsmodels.org/stable/index.html


- Scikit-learn = more useful if you are doing machine learning
  - http://scikit-learn.org/



This charts allows you to select the right model based on what you are looking for:
http://scikit-learn.org/stable/tutorial/machine_learning_map/index.html



Linear models tend to perform better with more dimensions.


Next Week

- Work on Connor Johnson -  http://connor-johnson.com/2014/02/18/linear-regression-with-python/


Assignment #4

Two variables to look at:
- Temperature of time to launch
- Test pressure


https://archive.ics.uci.edu/ml/machine-learning-databases/space-shuttle/o-ring-erosion-or-blowby.data


How many O-rings does the model predict will show erosion or blowby when the temperature is 31 degrees F?
