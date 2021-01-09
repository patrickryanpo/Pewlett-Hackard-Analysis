# Pewlett-Hackard-Analysis

# Overview
The project was initiated to examine the employees of Pewlett Hackard. More specifically, the project looks at employees who are soon to retire and then further deduced to those eligible for the part-time mentorship program. 

The initial data and relationships are presented by the ERD below. 

![ERD](https://github.com/patrickryanpo/Pewlett-Hackard-Analysis/blob/main/EmployeeDB.png)

# Results
The following findings have been made based on this study:

- We found that the initial list of employees close to retirement had more than one entry for employees. Hence, we created a list of unique employees who are closing to their retiring age. In the same file, their latest job titles and hiring date are included as reference. 

![Unique Titles](https://github.com/patrickryanpo/Pewlett-Hackard-Analysis/blob/main/unique_titles.png)

- We were able to show the number of expected retirees per department as represented in the retiring_titles file. This way Pewlett Hackard can anticipate their hiring count in the next couple of years. 

![Retiring Titles](https://github.com/patrickryanpo/Pewlett-Hackard-Analysis/blob/main/retiring_titles.png)

- As we found using this analysis, two managers are close to retirement age and Pewlett Hackard will have to plan for the replacement of these critical positions. They may either query to find eligible employees who may be promoted or start sourcing the job market for outside hiring. In any case, it would be ideal for Pewlett Hackard to hire these managers prior to the existing managers retirement to enable a smooth transition. 

- 1,549 Pewlett Hackard employees are eligible for the proposed mentorship program. Eligible mentors were queried based on their birth year of 1965.

![Mentorship Eligibility](https://github.com/patrickryanpo/Pewlett-Hackard-Analysis/blob/main/mentorship%20eligibility%20count.png)

- 

# Summary

Based on the aforementioned findings and analysis, there will be 90,398 positions to be filled based on projected employee retirements. They will have to start planning on filling these roles in order to effectively transition employees effectively. 

Based on our query, there are only 1,549 eligible mentors to mentor the next generation of Pewlett Hackard employees. The "silver tsunami" count is currently at 90,398, which means that each mentor will have to mentor approximately 58 employees each. I would recommend for Pewlett Hackard to include more mentors into the mentorship program. The current list only includes employees who were born in 1965. In order for them to increase the number of mentors, they must include more years to the mentorship program pool. 