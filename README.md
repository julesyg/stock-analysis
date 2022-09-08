# Refactor VBA Code and Measure Performance

## OVERVIEW OF PROJECT
The purpose of this project is to refactor code used in a large dataset to maximize efficiency of output while ensuring accuracy. 

## RESULTS
The subroutine 'All Stocks Analyzed Refactored' was created in an effort to increase the speed of analysis of the Green Stocks dataset without losing data integrity. Below we can compare the stock results of years 2017 vs 2018, as we can see 2017 yielded far better returns than 2018. 


<img width="204" alt="All_Stocks(2017)" src="https://user-images.githubusercontent.com/111521163/189006030-780eda35-66cc-455c-af8c-d00c7a6b28e8.png">


<img width="200" alt="All_Stocks(2018)" src="https://user-images.githubusercontent.com/111521163/189006045-3835e278-dcdd-4626-9fd0-1393272c7d00.png">

After refactoring the code we reduced the run time greatly.

Before refactoring:
<img width="532" alt="image" src="https://user-images.githubusercontent.com/111521163/189026103-22c6796d-05ed-4f24-8da8-893d2c04d16b.png">

<img width="532" alt="Before Refactor Screen Shot 2022-09-03 at 1 55 44 PM" src="https://user-images.githubusercontent.com/111521163/189010383-cf836179-9f3d-4dde-a32f-4176765e9bc5.png">



After refactoring:

<img width="532" alt="VBA_Challenge_2017" src="https://user-images.githubusercontent.com/111521163/189008095-96f63e2c-50bb-4a1e-a126-d4d534c229b1.png">

<img width="532" alt="VBA_Challenge_2018" src="https://user-images.githubusercontent.com/111521163/189008101-1586d0d2-f6b0-43f8-a7a7-3d1c599f0fd4.png">


Altering the code loops allowed for the code to run more efficiently.


<img width="446" alt="loop_code" src="https://user-images.githubusercontent.com/111521163/189025001-68edd051-c36a-4020-bb2c-38376f5b8084.png">



## SUMMARY

Refactoring allows code to run smoother and faster by eliminating redunduncies and excessive or confusing code. This allows for greater readability, maintenance and less error. Conversely, refactoring can allow for bugs and errors to be introduced to the code. 

Overall, refactoring Green_Stocks in VBA allowed for quicker, more readable code. A disadvantage, would be the insertion of potential error. 

