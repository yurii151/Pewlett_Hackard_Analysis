# Pewlett_Hackard_Analysis

## Analysis Overview

### Overview

This is a deeper look into the employee data base that was created during the model. In this analysis, I figure out the demographics of the compnay and how the age of each employee breaks down to try and anticipate a incoming large wave of retirement. The results of the analysis are very interesting to look at. 

## Results

### Retiring Employees

The first task was to find out the number of retiring employees per title. I was able to this by using listing all the employees who are of retirement age, grouping them by what department their title is under, and then counting the amount of people per group. Here were the results:

<img width="224" alt="Screen Shot 2021-12-21 at 9 24 55 PM" src="https://user-images.githubusercontent.com/92888170/147040383-bd3d900c-4d42-45db-961a-f45dfbf4f3bc.png">

- The position with the most employees of retirement age is Staff
- The position with the second most employees of retirement age is Senior Engineer
- The position with the third most empoloyees of retirement age is Engineer 
- The position with the least amount of employees of retirement age is Assistant Engineer

The second task was to find employees that were eligible for the Mentorship Program. I was able to to this by querying the list of employees and only listing the employees who were born in the year 1965. Here were the results:

<img width="750" alt="Screen Shot 2021-12-21 at 9 36 16 PM" src="https://user-images.githubusercontent.com/92888170/147041207-50399edb-5099-41e0-9674-c2faa76d2361.png">

- Using the count method, I figured out that there were 1940 employees eligible for the mentorship program. 
- A majority of the people eligible for the program are staff members.
- The longest tenured employee eligilbe for the program has been working since February 1985 
- THe shortest tenured employee eliglible for the program has been working since July 2002. 


## Summary

### Questions

- As the silver tsunami comes, based on the data we can expect roughly 90400 jobs that might need to be replaced in a short to medium time frame.
- In terms of people in house that are qualified to move up, I would say that the Engineer position has the least to worry about. There are the least amount retirement eligible individuals who are Assistant Engineers, and there are over 600 Engineers in the mentorship program, so when the Engineers retire we can replace them with the assistant engineers. 

## Queries
- Another thing that we can try and use is a query to figure out the total number of younger people who are eligible for the mentorship program. 
We could do this by taking the query code that was used to find the mentorship program elibile people and just change the age of the people that we want to be pulled up. 
- We could also create a table that would contain the likely to be promoted people. This could be done by manipulating the code that was used to find the retiring jobs employees and update the query to find people who had the longest time passed since thier start date, this giving us people who might be the most qualified for the replacement of the retired workers. 
