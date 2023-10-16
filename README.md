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
The penguin data set...

The purpose of Task2 is to give an overview of the penguins data set, explaining the types of variables it contains. And suggesting the types of variables that should be used to model them in Python, explaining the rationale.

Although the penguin dataset is commonly used...

The data from the penguins data set was collected through research by Gorman and researchers from the... $^3$.

Useful Links - more to references section if used...

https://medium.com/@marvelouskgc/build-a-penguin-project-using-pandas-and-seaborn-eugene-tsai-e4b7e0b499ea

https://www.kaggle.com/code/parulpandey/penguin-dataset-the-new-iris

https://towardsdatascience.com/penguins-dataset-overview-iris-alternative-9453bb8c8d95




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

Need to format these right so they are all consistent

$^1$ Collatz Conjecture | Wikipedia. July 2023. URL: https://en.wikipedia.org/wiki/Collatz_conjecture (Accessed on 2/10/2023)   

$^2$ Even the Smartest Mathematicians Can't Solve the Collatz Conjecture. | Jesslyn Shields, How Stuff Works. nd. URL: https://science.howstuffworks.com/math-concepts/collatz-conjecture.htm (Accessed on 2/10/2023)   

$^3$ Gorman KB, Williams TD, Fraser WR (2014). Ecological sexual dimorphism and environmental variability within a community of Antarctic penguins (genus Pygoscelis). PLoS ONE 9(3):e90081. https://doi.org/10.1371/journal.pone.0090081


To make it look like code
```data```   
Or Latex to make it look mathematical
$+/=45/2$


Notes:

Old references for Task2 - can be deleted probably
Adélie penguins:

    Palmer Station Antarctica LTER and K. Gorman, 2020. Structural size measurements and isotopic signatures of foraging among adult male and female Adélie penguins (Pygoscelis adeliae) nesting along the Palmer Archipelago near Palmer Station, 2007-2009 ver 5. Environmental Data Initiative. https://doi.org/10.6073/pasta/98b16d7d563f265cb52372c8ca99e60f (Accessed 2020-06-08).

Gentoo penguins:

    Palmer Station Antarctica LTER and K. Gorman, 2020. Structural size measurements and isotopic signatures of foraging among adult male and female Gentoo penguin (Pygoscelis papua) nesting along the Palmer Archipelago near Palmer Station, 2007-2009 ver 5. Environmental Data Initiative. https://doi.org/10.6073/pasta/7fca67fb28d56ee2ffa3d9370ebda689 (Accessed 2020-06-08).

Chinstrap penguins:

    Palmer Station Antarctica LTER and K. Gorman, 2020. Structural size measurements and isotopic signatures of foraging among adult male and female Chinstrap penguin (Pygoscelis antarcticus) nesting along the Palmer Archipelago near Palmer Station, 2007-2009 ver 6. Environmental Data Initiative. https://doi.org/10.6073/pasta/c14dfcfada8ea13a17536e73eb6fbe9e (Accessed 2020-06-08).