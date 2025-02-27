# Data-Analysis
## Work of Art

# Table of Content

## PROJECT OVERVIEW
This is a Python and SQL project on an imaginary school called Graceland Academy. The analysis project objectives are aimed to analyze and give insight into the student’s overall performances in certain subjects in the year 2025. By careful analysis of the student’s data, we want to identify student performances, make recommendations to subjects needing improvement and help the school make data driven decisions.


### Disclaimer:
All dataset used for this analysis do not represent any company, institution or state but just a 
Self-created dataset to show the power of Python and SQL in data analysis.


## DATA SOURCE 

### Sales Data:
The primary dataset used here for the analysis is the “graceland.csv” file, containing detailed information about each student and their performances in the school during the period under review.

## TOOLS
 - 	Excel
 - 	Python Data Analysis
 - SQL Server Data Analysis
 - Power BI Creating Reports 


## DATA CLEANING / PREPARATION 
 - 	Data Loading and inspection 
 - 	Handling Missing Values
 -  Data Cleaning and Formatting


## EXPLORATORY DATA ANALYSIS 
 - 	Who is the overall best student?
 - 	Which subject has best performing students?
 - 	Best students in each subject?

## DATA ANALYSIS 

```python
    data = pd.read_csv("C:\\Users\\HP\\Documents\\Analysis Report\\graceland.csv")
```

```python
    data = data.fillna(0)
```

```sql
    select * from student_data;
```

## Result/Finding

  1. The school has a high number of good performing students with a good stability.
  2.  Mathematics has proven to be the best course offered in the school
  3.	Very high competition in the classes seeing over 3 students scoring a score of 100

## Recommendations

Based on the just concluded analysis,I hereby recommend the following actions:

   -	More teachers are needed in the biology subject
   -	Awards should be given to best performing students to improve the competition even more.
   -	There should be contact to parents of students who miss school due to reasons of some students missing exams.
   -	Students not performing so well should be enrolled on extra moral classes to aid improvement.








