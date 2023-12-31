Readme.md for Fundamentals of Data Analysis Tasks and Projects   

Author: Phelim Barry 


The contents of this repository are available at https://github.com/PeeBs68/fund_da 

To execute the code the following applications are suggested:   
Anaconda Navigator v2.4.2   
Python v3.11.4   
VS Code: v1.82.2   
Jupyter Notebook: v6.5.4

---
The purpose of this README is to describe the tasks and project associated with Fundamentals of Data Analysis 
Using Jupyter Notebooks we show the requirement of each task and describe how we went about completing it. We also outline the requirements for the project and the methods we used to complete it.
---

# Tasks

## Task1
The Collatz conjecture is a famous unsolved problem in mathematics which was introduced in 1937 by Lother Collatz $^1$. It asks the question whether applying two simple arithmetic equations to any positive integer will always result in a value of 1. As of time of writing, no number has yet been found that breaks this sequence but the conjecture has yet to be proven for all numbers. Although in 2019, Australian mathematician Terence Tao $^2$ suggested that it would be very rare for any number to diverge from the Collatz rule, but not necessarily impossible.

The purpose of Task1 is to prove that the Collatz conjecture is true for the first $10,000$ positive integers.  

## Task2
The purpose of Task2 is to give an overview of the penguins data set, explaining the types of variables it contains. And suggesting the types of variables that should be used to model them in Python, explaining the rationale.

The data for the penguins data set was collected through research by Gorman and other researchers from the Palmer Research Station $^3$. The dataset is available from a number of sources including Michael Waskom's github repository $^4$ and also directly through the seaborn module in python.

## Task3
The purpose of task3 is to suggest which probability distribution from the numpy random distribution list $^5$ is most appropriate to model the variables in the penguin dataset.

## Task4
The purpose of this task is to plot the entropy of the total number of heads versus the probability $p$ of giving heads when flipping two coins.
Assumption: we are making the assumption that the question refers to the probability of both coins landing on Heads with each single toss (as opposed to either coin landing on Head)

## Task5
The purpose of this task is to create appropriate individual plots for each of the variables in the penguin data set based on the amount and type of data the variable contains.

---
---

# Project

The purpose of this project is to investigate the variables and data points within the iris flower data set. In this we discuss the classification of each variable within the data set. We will select, demonstrate and explain the most appropriate statistics to describe each variable. We will also select, demonstrate and explain the most appropriate plots for each variable.

## Classification of Variables
In this section we discuss the classification of each variable within the dataset according to common variable types and scales of measurement within mathematics, statistics and Python.

## Statistics
For this section we looked at each individual variable in the dataset and discussed ways to describe and explaine the most appropriate summary statistics for each.

## Plots
In this section we looked at various plot types for each of the variables in our data set. We concluded that bar/pie charts are most appropriate for the categorical variables (i.e. Class) and that histograms were most appropriate for the numeric variables.   
We also explored using scatterplots to compare the relationships between two variables and a correlation heatmap plot to show at a glance the strength of the relationships between each of the variables in our data set. We finished with a pair plot to show a mix of combined and individual plots.


# References

$^1$ Collatz Conjecture | Wikipedia. July 2023. URL: https://en.wikipedia.org/wiki/Collatz_conjecture (Accessed on 2/10/2023)   

$^2$ Jesslyn Shields "Even the Smartest Mathematicians Can't Solve the Collatz Conjecture" 1 January 1970.
HowStuffWorks.com. <https://science.howstuffworks.com/math-concepts/collatz-conjecture.htm>  (Accessed on 27/10/2023)

$^3$ Gorman KB, Williams TD, Fraser WR (2014). "Ecological sexual dimorphism and environmental variability within a community of Antarctic penguins (genus Pygoscelis)." PLoS ONE 9(3):e90081. https://doi.org/10.1371/journal.pone.0090081

$^4$ Michael Waskom's Seaborn Data Repository. URL: https://github.com/mwaskom/seaborn-data/blob/master/penguins.csv (Accessed on 5/10/2023)

$^5$ Numpy Random Number Generator. Numpy.org. nd. URL: https://numpy.org/doc/stable/reference/random/generator.html#distributions (Accessed on 10/10/2023)

