# Not On the High Street Data Engineering Code Challenge

# 
This is a benchmark test to ensure that data engineers, Python developers can show a good understanding of the fundamentals of reading, coding and delivering to a timeframe.

## Rules
 A link to a public Git repository with your final solution must be provided within 48 hours of receipt of the test. 
Guidelines
1. To help understand how you approach the problem, we will assess your use of source control and how you build to the final solution, checking what is committed 
along each step (hint: frequent push)
2. The code must be written in Python 3.
3. You may use any frameworks or libraries to complete this task, excluding data analysis libraries like Pandas.
4. Unit tests must be provided

## Objectives
A data file will be provided alongside this test. The dataset is a CSV which contains publicly available data about New York Police Dept. (NYPD) Arrest Data in 2018 first 6 six months. 

### Actions
1. Load the data file, process and output the data in the forms specified
2. Read in, process and present the data as specified in the requirements section
3. Demonstrate usage of list comprehension for at least one of the tasks
4. Allow user input to run all of your script, or specific sections


## Requirements
1. Read in the attached file
  - Produce a dictionary count records group by `OFNS_DESC` in descending order
  - Obtain the first 10 items from the resultant list and output to the console


2. Obtain the count of arrests grouped by age group and PD_CD. 
   Find the 4th greatest number of arrests by PD_CD for each age group and output to the console.


3. Export to a csv file containing user specified `OFNS_DESC`. For example, a user can specify full or part of an offence - 'ASSAULT' or 'ASSAULT 3' or 'ASSAULT 3 & RELATED'. Export the result to a csv file.

  
4. Instantiate a sqlite db and insert all records from the original csv into it.
  
## Assessment
Your code will be reviewed and assessed according to the following:
1. Adherence to the requirements
2. Code quality – readability, structure of the code, performance
3. Unit test coverage and relevance of the tests

## Helpful Tips
If you struggle completing the test or have concerns over certain aspects that is okay – just highlight it to us when you submit your test. 
Explain what you couldn't get working and steps you took to solve the problem. Whilst we want to see completed tests 
it is just as important for us to see how you approached an issue and attempted to find a solution. 
Do not overthink your solution. Keep it simple and use what you know. Write tests only for your code. 
Don't forget the ReadMe Avoid creating additional requirements.

