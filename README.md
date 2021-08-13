# Project 1: SAT & ACT Analysis 

 ## Contents:
 
- [Problem Statement](#Problem-Statement)  
- [Executive Summary](#Executive_Summary)
- [Data](#Data)
- [Data Dictionary](#Data-Dictionary)
- [Data Analysis](#Data-Analysis)
- [Conclusions and Recommendations](#Conclusions-and-Recommendations)
- [Next Step](#Next_Step)
- [References](#References)


## Problem Statement:

**What entrance exam should I take?**
Both ACT and SAT scores are used for college admissions decisions and awarding merit-based scholarships. But the difficulty for the student lies in how to choose between these two exams. As a journalist, I will provide a set of information to the college board so that they can make a decision through a set of data, and then they can help the students in how to choose between the two exams.
At the outset, we will note the reason for choosing the data for the year 2017 because The SAT college exam was undergo sweeping changes on what’s tested among these changes The test was a shift from its current score scale of 2400 back to 1600, and the College Board will partner for the first time with Khan Academy to provide free test preparation materials .
we can take the results obtained after a full year of these changes, and also we will calculate the percentage of graduate students from us colleges in the year 2021, so the date for graduating students of the class of 2017 will be.


### Executive Summary
This notebook begins by importing and cleaning the 2017  participation & score data files for both the SAT and ACT.  we perform some exploratory data analysis to uncover trends in the participation rates and section scores for both the SAT and ACT in 2017 on a state-wide basis across all 51 states, then identify states that saw the largest in participation rate over the year to carry out a deep dive on. Using external resources in conjunction with our data, we reach some conclusions.



## Data

* [datafile 1](act_2017.csv) 
* [datafile 2](sat_2017.csv)


## Data Dictionary
|Feature|Type|Dataset|Description|
|:---:|:---:|:---:|:---|
|**State**|*object*|ACT/SAT|The US state under consideration|
|**sat_participation**|*float64*|SAT|percentage of high school students (freshman through senior) in the state that took the SAT in 2017|
|**sat_reading_writing**|*int64*|SAT|scaled score between 200-800 (inclusive) measuring verbal reasoning, averaged over all test takers in state in 2017|
|**sat_math** |*int64*|SAT|scaled score between 200-800 (inclusive) measuring mathematical reasoning, averaged over all test takers in a state in 2017|
|**total**|*int64*|SAT|sum of verbal and reading score, averaged over all test takers in a state in 2017|
|**act_participation**|*float64*|ACT|percentage of high school students (freshman through senior) in the state that took the ACT in 2017|
|**act_english**|*float64*|ACT|scaled score between 1-36 (inclusive) measuring command of grammar, averaged over all test takers in a state in 2017|
|**act_math**|*float64*|ACT|scaled score between 1-36 (inclusive)measuring mathematical reasoning, averaged over all test takers in a state in 2017|
|**act_reading**|*float64*|ACT|scaled score between 1-36 (inclusive)measuring reading comprehension, averaged over all test takers in a state in 2017|
|**act_science**|*float64*|ACT|scaled score between 1-36 (inclusive)measuring scientific reasoning, averaged over all test takers in a state in 2017|
|**act_composite**|*float64*|ACT|mean of English, Math, Reading,and Science scores, averaged over all test takers in state in 2017|

    
## Data Analysis:

- Describe the data (2017 Data Import & Cleaning)
- Perform methods of exploratory data analysis, including:
1 Use Matplotlib to create visualizations
2 Use NumPy to explore distributions of individual variables and relationships among pairs of variables
3 Display your cleaned Jupyter notebook on a personal static website.


## Conclusions and Recommendations:

By studying the data for the year 2017, it became clear that we have states that require ACT for state testing and have very high if not 100% participation rates. These States are important for the College Board to know about (Alabama, Arkansas, Colorado, Kentucky, Louisiana, Minnesota, Mississippi, Missouri, Montana, Nevada, North Carolina, Oklahoma, South Carolina, Tennessee, Utah, Wisconsin, Wyoming)
And To be fair, We must compare the states in which both exams are located, because the participation rates between SAT and ACT are negatively correlated, meaning that if one state tends to have high SAT participation, then it probably will have low ACT participation and vice versa.
-After studying the data of the two exams and studying the distribution of each of them to the states, I see that there is no need for SAT exam, for many reasons:
-Through our study of the distribution of marks, as it became clear that the student's marks in the ACT exam were better than SAT exam
-Also, through our study of external research, it was found that the percentage of graduates in 2021 in states that accept ACT is better than the percentage of students in states that accept SAT.
-And away from the distribution the main difference between the SAT and the ACT is that the ACT includes a science section and the SAT does not. In my opinion, scientific subjects are the most important subjects that a student can attend before entering college


## Next Step

Things I would like to look into as the project continues:
Since there are a lot of complaints about the two exams, and student waste a lot time trying to figure out which exam to take and in most cases student attends to take both exam to find which one is the higher score which i believe is costing student a lot time money and efforts. I want to keep track of the data to make sure what i found in the data for 2017 apply for other years as well,
Or if they worked on any developments on the law of the two exams or added anything to the subjects.


## References

[Major Changes to 2016 SAT test] (https://www.cnn.com/2014/03/05/living/sat-test-changes-schools/index.html)
[college graduation rates 2021] (https://educationdata.org/number-of-college-graduates)




