# pandas-challenge

## Module 4 Challenge for KU Data Analytics

### **Author:  Kevin Krause**

## Comments:   03-30-2023 CORRECTION MADE.  
##              The average used for passing math and reading was inadvertantly calculated as > 70.  I changed it to >= 70 instead.
##              The value then was used thru out the code correctly.

### Comments: 
The  ipynb notebook program written is named PyCitySchools_Analysis.ipynb and resides under
pandas-challenge/PyCitySchools.  This program was based on the PyCitySchools_starter.ipynb program.

- Files used for the PyCitySchool district analysis are stored as followed:
  - pandas-challenge/PyCitySchools/Resources (input)
    schools_complete.csv
    students_complete.csv
 -  Output is generated to the Jupyter Notebook screen interactively
 -  The summary of my analysis is stored in a PDF Document named "Summary of District Student Test Data Analysis.pdf"
    under pandas-challenge/PyCitySchools
  - README.md



The following website was used to obtain syntax for calling pandas.  In additon, just making sure I had the syntax correct for all commands:
  (https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.sort_values.html)
  (https://www.geeksforgeeks.org/python-pandas-dataframe/)



##Analysis:


District Student Data
Standardized Test Results Analysis
Author: Kevin Krause 
KU Data Analytics Bootcamp 
Module 4 Challenge - Pandas Challenge 
Due Date: April 27, 2023 
Background Information: 
•	•Standardized test scores that tested math and reading skills from 15 schools within the district have been analyzed. The 15 schools included 39,170 students that completed the testing. 
	•When looking at the size of the schools the following criteria is used: o Small Schools with less than 1,000 students 
	o Medium Schools with 1,000 to 2,000 students 
	o Large Schools with 2,000 to 5,000 students 
	

Summary of Findings: 
•	The total budget for all schools combined in the district is $ 24,649,428 
•	The average score for each of the tests (math and reading) are as follows:
o	Average Math Score: 78.98% 
o	Average Reading Score: 81.88% 

•	The percent of students that passed each of the tests is as follows: 
o	Percentage of students that passed the Math Test: 74.9808526933878% 
o	Percentage of students that passed the Reading Test: 85.80546336482001% 
o	Percentage of students passing both the Math and the reading test: 65.17232575950983% 


•	The district is made up of 2 school types: 
o	District 7 schools 
o	 Charter 8 schools 
o	The population of each school ranges from 427 students to 4976 students 
o	The budget per student for each school ranges from $578 to $655 

Findings and Observations 
o	Small and medium sized schools out-performed large schools by a significant amount for overall testing scores. The percentage of students that passed both math and reading in small and medium schools is 88.88% and 90.62% respectively. Whereas only 58.28% of students in large schools passed both the math and reading tests. 
o	Charter schools out-performed District schools by a significant amount for overall testing scores. The percentage of students that passed both math and reading in charter schools is 90.43. Whereas only 53.67% of students in District schools passed both the math and reading tests. 
o	Schools that budgeted less per student out-performed schools that spent more by a significant amount for overall testing scores. The following shows the budget per student along with the percentage of students that passed both the math and reading tests: 

 
