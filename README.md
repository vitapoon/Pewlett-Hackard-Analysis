# Pewlett-Hackard-Analysis

## Purpose of our project

The purpose of this analysis is to determine the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship program. Then, summarizes the analysis and helps prepare the “silver tsunami” as many current employees reach retirement age. I used PostgreSQL to complete my analysis.

## Results

## Task 1: The Number of Retiring Employees by Title
The current criteria for this analysis is to find employees born between 1952 and 1955. The major takeaways from this analysis are:

1, There are 90,396 employees who are likely to retire soon

2, 57,668 employees are senior level employees

3, 43,636 employees are engineers

4, 40,497 employees are staff

5, Only 2 managers need to be replaced

6, Our retiring_titles shows us the a majority of the employees of retirment age (57,668/90,398 = 64%) have senior titles.

### retiring_titles

![retirement titles](https://user-images.githubusercontent.com/71739110/98469942-75c25c80-221d-11eb-9c37-9f93878380b4.png)

## Task 2: The Employees Eligible for the Mentorship Program

The current criteria for this analysis is to find employees born in 1965 and have current roles with no termination dates. The major takeaways from this analysis are:

1, There are 1,550 employees eligible for the mentorship program

2, 741 employees are senior level employees

3, 748 employees are engineers

4, 724 employees are staff

### Mentorship Program

![Screen Shot 2020-11-09 at 12 05 51 AM](https://user-images.githubusercontent.com/71739110/98470285-955a8480-221f-11eb-95ba-4e84ff7a243b.png)


## Summary

We can see that of the 90,396 potential spaces that need to be filled due to retirement, there are only 1,550 employees currently eligible to mentor new employees to fill those positions and only 741 senior level employees eligible to mentor 57,668 vacancies. That means there is one senior level mentor for every 77 new senior level employee.

If we change to criteria for the mentorship program to employees born between 1961 and 1965, there are 75,319 employees eligible for the mentorship program and 33,413 senior level employees to mentor 57,668 vacancies. That means there is one senior level mentor for every new senior level employee.

![metorship_1961to1965](https://user-images.githubusercontent.com/71739110/98471503-c3dc5d80-2227-11eb-836a-07c8140d7ef0.png)
