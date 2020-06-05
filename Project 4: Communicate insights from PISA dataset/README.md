# Analysis of The Programme for International Student Assessment (PISA) 2012 study

## by Aakar Shah

## Preliminary Wrangling

> PISA is a worldwide study developed by the Organisation for Economic Co-operation and Development (OECD) to examine the skills of 15-year-old school students around the world. The study assesses students’ maths, science, and reading skills and contains a wealth of information on students’ background, their school and the organisation of the education system. For most countries, the sample is around 5,000 students, but in some countries the number is even higher. In total, the PISA 2012 dataset contains data on 485 490 pupils.


### Dataset Structure

The dataset consists of 636 columns and 485490 rows. I will thus need to limit the number of features to assess this large dataset. The dataset can be found [here](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud507/pisa2012.csv.zip&sa=D&ust=1554482573645000) 

**Student Information**
- CNT: Country
- ST04Q01: Gender
- WEALTH: Wealth of family

**Student Grades**
- PV1MATH: Overall Mathematics Score
- PV1READ: Overall Reading Score
- PV1SCIE: Overall Science Score

**Effect of teachers on grades**

- **Student-Teacher Relation**
    - ST86Q01: Get Along with Teachers
    - ST86Q02: Teachers Are Interested
    - ST86Q03: Teachers Listen to Students
    - ST86Q04: Teachers Help Students
    - ST86Q05: Teachers Treat Students Fair

- **Teacher Support**
    - ST83Q01: Lets Us Know We Have to Work Hard
    - ST83Q02: Provides Extra Help When Needed
    - ST83Q03: Helps Students with Learning
    - ST83Q04: Gives Opportunity to Express Opinions

**Effect of student's own perseverence, study ethics and self beliefs on his/her grades**

- **Math Work Ethic**

    - ST46Q01: Homework Completed in Time
    - ST46Q02: Work Hard on Homework
    - ST46Q03: Prepared for Exams
    - ST46Q04: Study Hard for Quizzes
    - ST46Q05: Study Until I Understand Everything
    - ST46Q06: Pay Attention in Classes
    - ST46Q07: Listen in Classes
    - ST46Q08: Avoid Distractions When Studying
    - ST46Q09: Keep Work Organized

- **Math Anxiety**

    - ST42Q01: Worry That It Will Be Difficult
    - ST42Q03: Get Very Tense
    - ST42Q05: Get Very Nervous
    - ST42Q08: Feel Helpless
    - ST42Q10: Worry About Getting Poor

- **Math Interest**

    - ST29Q01: Enjoy Reading
    - ST29Q03: Look Forward to Lessons
    - ST29Q04: Enjoy Maths
    - ST29Q06: Interested

- **Math Behaviour**

    - ST49Q01: Talk about Maths with Friends
    - ST49Q02: Help Friends with Maths
    - ST49Q03: (Extracurricular) Activity
    - ST49Q04: Participate in Competitions
    - ST49Q05: Study More Than 2 Extra Hours a Day
    - ST49Q06: Play Chess
    - ST49Q07: Computer programming
    - ST49Q09: Participate in Math Club
    
- **Perseverence**
    - PERSEV: Preseverence of student

- **Instrumental Motivation**
    - ST29Q02: Worthwhile for Work
    - ST29Q05: Worthwhile for Career Chances
    - ST29Q07: Important for Future Study
    - ST29Q08: Helps to Get a Job


**Effect of parents on grades**

- **Parents at home**
    - ST11Q01: Mother
    - ST11Q02: Father

- **Education level of Parents**  
    - PARED: Highest Qualification of parents


## Summary of Findings


- **How do students from individual countries perform in Math, Reading and Science literacy?**
    - Eastern countries such as China, Singapore, Korea, Hong Kong outperform other countires

- **What is the effect of teachers on student grades?**
    - We could only find a weak positive correlation between teachers and student grades. 

- **What is the effect of conducive home environment on student grades?**
    - We discovered that either parent staying at home showed increase in student grades

- **What effect does student's own perseverence and study ethics has on his/her grades?**
    - We could not find any significant impact of personal traits on grades

- **Do grades differ based on gender across subjects in higher percentiles?**
    - We discovered that as the Males perform better in Math and Science where as Females perform better in Reading.
    
***Chose all of the above questions for explanatory analysis***

## List of resources

- https://www.oecd.org/pisa/pisaproducts/PISA-2012-technical-report-final.pdf
- https://www.oecd.org/pisa/pisaproducts/PISA12_stu_codebook.pdf
- http://mi2.mini.pw.edu.pl:8080/SmarterPoland/PISAcontest/
- https://seaborn.pydata.org/generated/seaborn.barplot.html#seaborn.barplot
- https://stackoverflow.com/questions/44880444/how-to-increase-the-font-size-of-the-legend-in-my-seaborn-plot
- https://stats.stackexchange.com/questions/3476/how-to-name-the-ticks-in-a-python-matplotlib-boxplot
- https://s3.amazonaws.com/assets.datacamp.com/blog_assets/Python_Seaborn_Cheat_Sheet.pdf
