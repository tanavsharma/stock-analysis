# stock-analysis
## Overview

In this repo, we will be able to analyzie an entire dataset of stocks at the click of a button. We will then make the code more efficient so it decreases the time it takes for execution and also improve performance. We will also be comparing the datasets from 2017 and 2018 and visualize the differences and similarities. 

## Results and Findings

### Benefits of Refactoring

Before we dive into the analysis of the data, lets look at the differnece between our code improvements. Below you will find two images of the time it took to execute the result. This output is the result of the initial code written. 

<p align="center">
<img src="/Resources/AllStock2017.png" alt="All Stock 2017 Time" width="400"> 
<img src="/Resources/AllStock2018.png" alt="All Stock 2018 Time" width="400"> 
</p>

However, after looking into the code and modifying the logic, we were able to: 
- produce the same output but with less steps
- use signficantly less memory

and as a result we were able to run our code/script much faster as shown by the images below

<p align="center">
<img src="/Resources/AllStock2017-Refactored.png" alt="All Stock 2017 Refactored" width="400"> 
<img src="/Resources/AllStock2018-Refactored.png" alt="All Stock 2018 Refactored" width="400"> 
</p>

### Data Analysis
  <p align="center"> 
    <img src="/Resources/VBA_Challenge_2017.png" alt="All Stock 2017 Time" width="400">
    <img src="/Resources/VBA_Challenge_2018.png" alt="All Stock 2017 Time" width="400">
  </p>

The above data is the change in volume over the course of the year highlighted. Just based on the data provided we can clearly see that the stocks with best performace and most gains were **ENPH** and **RUN**. These two stocks had the gains upto 81% for ENPH and 84% for RUN. This information could be used to help in the decision making process for investing in a stock. Based on the data, we can look deeper into company accounting reports and perform other research to help us in making an educated and safe decision. 

### Advantages & Disadvantage of Refactoring Code In General

**Advantages**
- It will improve the Design of the Software
- It makes the code easier to understand
- It helps in finding bugs in your code
- it will improve the performace and time-complexity of your code.

**Disadvantages**
- It may be time comsuming if code/application is to long
- It may come at a cost, which could mean going over project budget
- sometimes it may not even be necessary.

### Advantages & Disadvantage of Refactoring the VBA Code

**The Advantage:**

It improved the run time by 0.78 seconds. Which may not seem like a lot, but in computer science it's very significant. Let's break it down further. With the code being refactored, we can see the code runs 81.25% more efficiently. Here is how I calculated that: 

<img src="/Resources/Formula.png" alt="Formula">
<br>
<img src="/Resources/FormulaSolved.png" alt="Formula Solved"> 

Having your script run 81.25% more efficiently comes in handy when dealing with large data sets. 

**The Disadvantage:**

Sometimes refactoring a code means making it specific to just 1 data set. In other words that code wont be able to handle a different dataset if the original were to change. So refactoring code can sometimes lead to decreased usability and integration. 
