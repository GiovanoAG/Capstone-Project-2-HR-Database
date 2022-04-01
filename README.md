# Capstone-Project-2-HR-Database

## DATA UNDERSTANDING

### Context
A company engaged in the export-import (shipping) of electronic equipments wants to know about the overlapping salaries of its employees and how the company retains the employees so that employees receive appropriate wages.

There is a database showing the details of each employee. From the database, the company wants to gain insight so that later the company can implement a reward and punishment strategy that is right on target to its employees for the satisfaction of every employee and providing the best performance.

### Database Information

[Download database](https://drive.google.com/drive/folders/1G9Q2sohMFVes7NCHaUHcuAAjlOybBYJG?usp=sharing)

HR database has 7 tables, namely:
- Countries : Describes information about country data based on the location of the region (ID and Region ID).
- Departments: Describes information about the details of each department in the HR database.
- Employees : Describes information about each employee from name, contact (email, phone), date of joining, job title and position, salary amount ($), boss ID, and department ID.
- Job History: Describes information on the start and end dates of certain employees who have been transferred or given promotions.
- Jobs : Describes detailed salary ranges (MIN and MAX) of each Job Title.
- Locations: Describes office location data in various countries in the world.
- Regions : Describes information about the continent of each office location.

Each table contained in the database can be connected, either directly or indirectly, so that any information from this database will be interrelated.

This repocitory will solve the main problem above by Statistics, Anomalies Findings, Data Analysis and Visualization to find out the conclusion to the company.

## CONCLUSION

Insights to that company from this project :

1. Recommendations for making salary structure based on *Competency Based* (similar to fit and proper test). Employees who have good performance will be promoted. Promotion is not directly based on Grade (ex. from D to C), but must go through a career ladder based on Grade_Class (from Junior to Middle, then Middle to Senior). When Grade_Class is in the upper class (senior), employees can take competency based to Grade promotion.

2. Implement a reward and punishment system for each employee. For employees whose performance is good, they will get rewards that can be in the form of an increase in Grade Class or the provision of incentives on the salary they get in order to spur employees to continue to give their best performance for the company's profit and the company can retain its best employees. Meanwhile, employees who underperform will receive punishment, from the lightest, namely persuasive counseling for underperforming employees, giving drying letters and even demotion. This also refers to employees being able to give their best performance so they don't get punishment for the company's profit.
