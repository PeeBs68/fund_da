Readme.md for Fundamentals of Data Analysis Tasks and Projects   

Author: Phelim Barry 

Python v3.11.4   
VS Code: v1.82.2   
Jupyter Notebook: v6.5.4

---

**Table of Contents**
1. [Introduction](#Introduction) 
2. [Task1](#Task1)
3. [Task2](#Task2)
4. [Task3](#Task3)
5. [Task4](#Task4)
6. [Task5](#Task5)
7. [Project](#project)
    1. [Part1](#Part1)
    2. [Part2](#Part2)
    3. [Part3](#Part3)
8. [Summary](#Summary)
9. [References](#References)


# Introduction
The purpose of this README is to describe the tasks and project associated with Fundamentals of Data Analysis 
Using Jupyter Notebooks we show/describe etc...

***

# Task1
The Collatz conjecture is a famous unsolved problem in mathematic which was introduced in 1937 by Lother Collatz $^1$. It asks the question whether applying two simple arithmetic equations to any positive integer will always result in a value of 1. As of time of writing, no number has yet been found that breaks this sequence but the conjecture has yet to be proven for all numbers. Although in 2019, Australian mathematician Terence Tao $^2$ suggested that it would be very rare for any number to diverge from the Collatz rule, but not necessarily impossible.

The purpose of Task1 is to prove that the Collatz conjecture is true for the first $10,000$ positive integers.

In the code we start by defining a function $f(x)$ which applies a formula on $x$ depending on whether $x$ is even or odd and returns the calculated value back to the code.   

Next we define a second function ```collatz``` which uses a while loop to continuously call $f(x)$ until the value of $x = 1$.   

Finally we define a range of values for $x$ from $1$ to $10,000$ using a for loop which sends the values to the ```collatz``` function.

If our code reaches the value $10,000$ without going into any continuous loop then it has  proved the conjecture for those numbers.   

# Task2
All about Task2 here

# Task3
All about Task3 here

# Task4
All about Task4 here

# Task5
All about Task15 here

# Project
All about the project here
## Part1
Sub heading for project
## Part2
Sub heading for project
## Part3
Sub heading for project


# Summary

# References
$^1$ Collatz Conjecture | Wikipedia. July 2023. URL: https://en.wikipedia.org/wiki/Collatz_conjecture (Accessed on 2/10/2023)   

$^2$ Even the Smartest Mathematicians Can't Solve the Collatz Conjecture. | Jesslyn Shields, How Stuff Works. nd. URL: https://science.howstuffworks.com/math-concepts/collatz-conjecture.htm (Accessed on 2/10/2023)   



To make it look like code
```data```   
Or Latex to make it look mathematical
$+/=45/2$