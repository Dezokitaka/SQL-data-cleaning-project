This Postgresql project uses the unclean version of data science job postings from Glassdoor. Link to the data set: "https://www.kaggle.com/datasets/rashikrahmanpritom/data-science-job-posting-on-glassdoor"
In this project I manually created a table, import the data to the table, and transformed the data to give the necessary information for an analysis. This data isnt complete enough to draw solid conclusions but the practice was invaluable.
During this project I used the following functions: Create table, Alter table, Drop column, Rename column, Count, Update, Left, Length, Replace, Rtrim, Alter column type, In, Case, Avg, and Round.
Lastly, I did add some code towards the bottom of the file that answered some question I had about the data.

Here were the questions and goals I wanted to solve throughout this process.
Questions for analysis
1. Find the most highly recommended jobs and the least recommended jobs. 
This can give us an idea which jobs are most enjoyable. This can only tell us so much because the sample size is small for each job but the sample size for each specific company is small. These might be great jobs but terrible companies.

2. What locations generally have a higher rating score?
Maybe some locations have higher success rate for each job.

3. What does salary have to do with the rating? Do higher payed jobs have a higher rating or not?

4. Public vs private vs Other, which one has a better review?

5. Does the sector ur working in affect the rating score?

Cleaning tasks
1. How to change the salary_estimated column into an integer?
A). I decided the best way to do this was to create three new columns. The max_salary, min_salary, and the avg_salary. This allowed me to have the salaries as integers but also made it easier to pick and choose what number value you want to use.

2. How to remove the numbers from the company name?
A). I used the LEFT and LENGTH function to get rid of the (0.0) digits. These digits were from the rating column and for some reason they combined together. (this took a bit of time and frustration)

3. How can you create some new features like a state column from the location column?
A). I used the right function to take the last two characters from the location column and then manually input them into its own column using the distinct function.


Throughout the cleaning process I ran into many problems like accidentally changing all the company names to the same name,and deleting values.
This project taught me how to avoid those mistakes next time as well as how to fix those mistakes. I've learned an invaluable amount of skills that I can take with me into the world of data analysis.
While I did learn new techniques and skills, I dont think that was the greatest take away from this project. The most valuable thing I've learned was how to overcome the mistakes you may run into at work. Everyone makes mistakes but its how you overcome those mistakes that matters.
