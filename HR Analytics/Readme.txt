Promotion Model for the HR
 

Problem Statement:
Your client is a large MNC and they have 9 broad verticals across the organisation. One of the problem your client is facing is around identifying the right people for promotion (only for manager position and below) and prepare them in time. Currently the process, they are following is:
1. They first identify a set of employees based on recommendations/ past performance
2.  Selected employees go through the separate training and evaluation program for each vertical. These programs are based on the required skill of each vertical
3.  At the end of the program, based on various factors such as training performance, KPI completion (only employees with KPIs completed greater than 60% are considered) etc., employee gets promotion.
For above mentioned process, the final promotions are only announced after the evaluation and this leads to delay in transition to their new roles. Hence, company needs your help in identifying the eligible candidates at a particular checkpoint so that they can expedite the entire promotion cycle. 
They have provided multiple attributes around Employee's past and current performance along with demographics. Now, the task is to predict whether a potential promotee at checkpoint in the test set will be promoted or not after the evaluation process.
 
Variable Description:
employee_id - Unique ID for employee
department -	Department of employee
region -	Region of employment (unordered)
education -	Education Level
gender - Gender of Employee
recruitment_channel -	Channel of recruitment for employee
no_of_trainings -	no of other trainings completed in previous year on soft skills, technical skills etc.
age	- Age of Employee
previous_year_rating - Employee Rating for the previous year
length_of_service - Length of service in years
KPIs_met >80%	- if Percent of KPIs(Key performance Indicators) >80% then 1 else 0
awards_won?	- if awards won during previous year then 1 else 0
avg_training_score - Average score in current training evaluations
is_promoted	(Target) -  Recommended for promotion

 
Expectations and Evaluation:
We expect the candidate to build a model upon training data (70% of the train_hr.csv) and evaluate the model on the validation data, (30% of the train_hr.csv). Use the random_state=10 while splitting the data. Use the model to predict upon the test_hr.csv. 
Candidates are free to use any of the algorithms to build the model and the evaluation metric for this competition is F1_Score on the validation data.
