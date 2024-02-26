---
title: "Data Analysis Project"
excerpt: " **Find the healthy employees for the bonus**  <br/><img src='/images/thumb2.png'>"
collection: portfolio
author_profile: false
---

*This data analysis project was designed to showcase the concept of simulating a daily required task from the HR department to query and visualize the data on human resources with the wireframe, including the lifestyle of the employees—are they smokers or drinkers? to get the bonus program from the company.*

### Requirements from HR departments
1. Provide a list of Healthy Individuals & Low Absenteeism for our healthy bonus program - Total Budget $1000 USD
2. Calculate a Wage Increase or annual compensation for Non-Smoler for
	- Insurance Budget of $983,221 for all Non-Smokers
3. Create a Dashboard for HR to understand Absenteeism at work based on the approved wireframe.

And CSV files that include employee data, check [my repository](https://github.com/trannphuocloc/HR-dataset-project) here for the data.

### Project Details

Start by creating a join table  to combine all relevant datasets and ensure accurate employee information.

Input [1]:
```
SELECT * FROM Absenteeism_at_work a
LEFT JOIN compensation b
ON a.ID = b.ID
LEFT JOIN Reasons c
ON a.Reason_for_absence = c.Number;
```

Output [1]:

| ID | Reason for absence | Month of absence | Day of the week | Seasons | Transportation expense | Distance from Residence to Work | Service time | Age | Work load Average/day | Hit target | Disciplinary failure | Education | Son | Social drinker | Social smoker | Pet | Weight | Height | Body mass index | Absenteeism time in hours | ID | comp_hr | Number | Reason |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 1 | 26 | 7 | 3 | 1 | 289 | 36 | 13 | 33 | 239554 | 97 | 0 | 1 | 2 | 1 | 0 | 1 | 90 | 172 | 30 | 4 | 1 | 35 | 26 | unjustified absence  |
| 2 | 0 | 7 | 3 | 1 | 118 | 13 | 18 | 50 | 239554 | 97 | 1 | 1 | 1 | 1 | 0 | 0 | 98 | 178 | 31 | 0 | 2 | 49 | 0 | Unkown |
| 3 | 23 | 7 | 4 | 1 | 179 | 51 | 18 | 38 | 239554 | 97 | 0 | 1 | 0 | 1 | 0 | 0 | 89 | 170 | 31 | 2 | 3 | 47 | 23 | medical consultation  |
| 4 | 7 | 7 | 5 | 1 | 279 | 5 | 14 | 39 | 239554 | 97 | 0 | 1 | 2 | 1 | 1 | 0 | 68 | 168 | 24 | 4 | 4 | 51 | 7 | Diseases of the eye and adnexa |
| 5 | 23 | 7 | 5 | 1 | 289 | 36 | 13 | 33 | 239554 | 97 | 0 | 1 | 2 | 1 | 0 | 1 | 90 | 172 | 30 | 2 | 5 | 25 | 23 | medical consultation  |

From this, we find the list of employees who are healthy individuals and have low absenteeism for the bonus program. With the assumption that healthy individuals are non-smokers and non-drinkers, their BMI is less than 25, and their absence time must be under the average of the list.

Input [2]:
```
SELECT * FROM Absenteeism_at_work a
LEFT JOIN compensation b
ON a.ID = b.ID
LEFT JOIN Reasons c
ON a.Reason_for_absence = c.Number
WHERE Social_drinker = 0 
AND Social_smoker = 0
AND Body_mass_index < 25
AND Absenteeism_time_in_hours < (SELECT AVG(Absenteeism_time_in_hours) FROM Absenteeism_at_work)
ORDER BY Absenteeism_time_in_hours;
```

Output [2]:

| ID | Reason for absence | Month of absence | Day of the week | Seasons | Transportation expense | Distance from Residence to Work | Service time | Age | Work load Average/day | Hit target | Disciplinary failure | Education | Son | Social drinker | Social smoker | Pet | Weight | Height | Body mass index | Absenteeism time in hours | ID | comp_hr | Number | Reason |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 52 | 0 | 9 | 2 | 4 | 225 | 26 | 9 | 28 | 241476 | 92 | 1 | 1 | 1 | 0 | 0 | 2 | 69 | 169 | 24 | 0 | 52 | 42 | 0 | Unkown |
| 217 | 0 | 5 | 4 | 3 | 388 | 15 | 9 | 50 | 378884 | 92 | 1 | 1 | 0 | 0 | 0 | 0 | 76 | 178 | 24 | 0 | 217 | 42 | 0 | Unkown |
| 531 | 0 | 10 | 2 | 4 | 225 | 26 | 9 | 28 | 284853 | 91 | 1 | 1 | 1 | 0 | 0 | 2 | 69 | 169 | 24 | 0 | 531 | 25 | 0 | Unkown |
| 559 | 13 | 12 | 6 | 4 | 179 | 26 | 9 | 30 | 280549 | 98 | 0 | 3 | 0 | 0 | 0 | 0 | 56 | 171 | 19 | 1 | 559 | 51 | 13 | Diseases of the musculoskeletal system and connective tissue |
| 504 | 23 | 9 | 4 | 1 | 225 | 26 | 9 | 28 | 261756 | 87 | 0 | 1 | 1 | 0 | 0 | 2 | 69 | 169 | 24 | 1 | 504 | 50 | 23 | medical consultation  |
| 522 | 1 | 10 | 4 | 4 | 228 | 14 | 16 | 58 | 284853 | 91 | 0 | 1 | 2 | 0 | 0 | 1 | 65 | 172 | 22 | 1 | 522 | 55 | 1 | Certain infectious and parasitic diseases |
| 525 | 13 | 10 | 5 | 4 | 225 | 26 | 9 | 28 | 284853 | 91 | 0 | 1 | 1 | 0 | 0 | 2 | 69 | 169 | 24 | 1 | 525 | 39 | 13 | Diseases of the musculoskeletal system and connective tissue |
| 263 | 23 | 8 | 5 | 1 | 179 | 26 | 9 | 30 | 265615 | 94 | 0 | 3 | 0 | 0 | 0 | 0 | 56 | 171 | 19 | 1 | 263 | 50 | 23 | medical consultation |
| 184 | 28 | 3 | 2 | 3 | 225 | 26 | 9 | 28 | 343253 | 95 | 0 | 1 | 1 | 0 | 0 | 2 | 69 | 169 | 24 | 1 | 184 | 37 | 28 | dental consultation |
| 186 | 23 | 4 | 4 | 3 | 225 | 26 | 9 | 28 | 326452 | 96 | 0 | 1 | 1 | 0 | 0 | 2 | 69 | 169 | 24 | 1 | 186 | 46 | 23 | medical consultation |

Here, the list of company employees who have a healthy lifestyle matches the selection criteria for the bonus program. The output comes from 111 employees. There are ten of them.

Let's move on to the next requirement from HR: calculating a wage increase or annual compensation for the insurance budget of $983,221 for all non-smokers

*Note: the requirement is to calculate a wage increase or annual compensation for the insurance budget of $983,221 for ALL NON-SMOKER, it shall not be the same list as the previous requirement.*

Firstly, query the number of employees who are nonsmokers:

Input [3]:
```
SELECT COUNT(*) AS count_nonsmoker 
FROM Absenteeism_at_work
WHERE Social_smoker = 0;
```
Output [3]:

| count_nonsmoker |
| --- |
| 686 |

Calculate the total number of hours nonsmokers worked in a year if they worked 8 hours per day, 5 days a week, for 52 weeks: 

*686 x 8 x 5 x 52 = 1426880 (hours)*

Next, calculate how much the hourly wage of a nonsmoker increases as the company's insurance budget increases by $983,221. 

*983221/1426880 = 0.68907 ($/hour)*

Let's do it backward to see the cost in total for an employee per year after the company increases the insurance budget.

*0.68907 x 8 x 5 x 52 = 1,433.26 ($/year)*

**The rise of $0.689 per hour in an employee's hourly income may seem substantial, but a mere $1433 payment for a nonsmoker employee's insurance will have a significant impact on wellness and employee incentives.**
That's just too tiny for the company to encourage employees to get a better lifestyle for the next bonus program.



Before creating dashboard sections, as you can see from the two previous requirements, we query the data by using SELECT * all the time, which makes sense for people who just check out for the first time and want complete information. For some columns that we don't need in PowerBI, optimize the query again using

Input [4]:

```
SELECT 
	a.ID, 
	c.Reason,
	a.Month_of_absence,
	a.Body_mass_index,
CASE
	WHEN a.Body_mass_index < 18.5 THEN 'Underweight'
	WHEN a.Body_mass_index BETWEEN 18.5 AND 25 THEN 'Healthy'
	WHEN a.Body_mass_index BETWEEN 25 AND 30 THEN 'Overweight'
	WHEN a.Body_mass_index > 40 THEN 'Obese'
	ELSE 'Unknown'
END AS BMI_Caretory,
CASE 
	WHEN Month_of_absence IN (12,1,2) THEN 'Winter'
	WHEN Month_of_absence IN (3,4,5) THEN 'Spring'
	WHEN Month_of_absence IN (6,7,8) THEN 'Summer'
	WHEN Month_of_absence IN (9,10,11) THEN 'Fall'
	ELSE 'Unknown'
END AS seasons_name,
	Seasons,
	Month_of_absence,
	Day_of_the_week,
	Transportation_expense,
	Education,
	Son,
	Social_drinker,
	Social_smoker,
	Pet,
	Disciplinary_failure,
	Age,
	Work_load_Average_day,
	Absenteeism_time_in_hours
FROM Absenteeism_at_work a
LEFT JOIN compensation b
ON a.ID = b.ID
LEFT JOIN Reasons c
ON a.Reason_for_absence = c.Number
```
We use this data to create a dashboard using PowerBI with a frame approved by HR departments.

**The wireframe**
![This is an alt text.](/images/wireframe1.png "This is a sample image.")


And check [my final report](https://app.powerbi.com/view?r=eyJrIjoiMGYzMGJjNzktZmQ0OS00MDY4LWEzZTMtZjE1NDkwODdhMzg3IiwidCI6Ijc3ZGIwZDg5LTgyNzAtNGQwNy05NGY4LWNlZDhkYTVjNThjNiIsImMiOjEwfQ%3D%3D) here in PowerBI.
