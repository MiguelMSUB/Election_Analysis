# Refactoring Code VBA

## Overview of Project

### Purpose
In this project, our final Python script will need to be able to deliver the following information when the script is run: 

*Total number of votes cast
*A complete list of candidates who received votes
*Total number of votes each candidate received
*Percentage of votes each candidate won
*The winner of the election based on popular vote



### Results
Refactoring the initial code required to create a new variable to loop through all the tickers and set it to zero before iterating over all the rows, this variable was "tickerIndex" which would increase after collecting the outputs from the different arrays.



![This is an image](Resources/Refactoring_CodeVBA.png)

The initial code that we developed ran the analysis in .82 seconds for 2017 and in .73 for 2018 so after refactoring the code we could have an improvement as we see in the next screenshots:

Code performance por 2017
![This is an image](Resources/VBA_Challenge_2017refactored.png)

Code performance por 2018
![This is an image](Resources/VBA_Challenge_2018refactored.png)

## Summary


### What are the advantages or disadvantages of refactoring code?
I think the advantages of refactoring are: 
1. It gives you an idea of the code structure
2. It will give you a closer look of what you can improve

Talking about disadvantages:
1. It takes time to understand what the original developer tried to map with variables and loops structures. 
2. Errors in the original code could be "invisible" util you actually run the refactored code.

### How do these pros and cons apply to refactoring the original VBA script?
The main advantage for this project was that we had the structure and comments that helped to finally accomplish the goal of making this code run faster.
