
README – HR Analytics Power BI Dashboard

Overview
--------
This Power BI dashboard provides a detailed analysis of employee demographics, job roles, compensation, and leave balances.
The dataset reflects real organizational data across multiple roles and education levels, enabling HR teams to gain insights into 
employee composition, salary distribution, and workforce planning.

Dataset Information
-------------------
File: hr-data.xlsx
Sheet: (Only one main sheet)

Column Details:
- Name: Employee name
- Emp ID: Unique employee ID
- Gender: Male / Female
- Education Qualification: Highest educational qualification
- Date of Join: Employee's joining date
- Job Title: Role/position in the organization
- Salary: Current salary
- Age: Age in years (float format)
- Leave Balance: Remaining leave days

Dashboard Features
------------------
1. Employee Overview
   - Total Employees
   - Gender Distribution
   - Education Qualification Breakdown
   - Age Distribution

2. Job and Role Analysis
   - Number of employees per job title
   - Average salary by job title
   - Leave balance by department (if grouped via role)

3. Compensation Analysis
   - Salary distribution by gender
   - Salary vs Age trend
   - Top and bottom salary earners

4. Workforce Tenure
   - Tenure calculation (based on Date of Join)
   - Relationship between tenure and leave balance

Key Insights
------------
- Employees are spread across varied roles like Chocolatier, Research Scientist, Marketing Specialist, etc.
- Education qualifications range from High School Diploma to Master's Degree.
- Leave balances vary, suggesting differences in usage or policy by role/tenure.
- Age ranges and salary differences can be analyzed for fairness and workforce planning.

Tools & Techniques Used
------------------------
- Power BI Desktop for visual reports
- Power Query for data loading and date processing
- DAX for calculated columns and measures:
  - Tenure = Today() - Date of Join
  - Average Salary per Role
  - Leave Balance Analysis

Interactivity
-------------
- Slicers: Gender, Education Qualification, Job Title
- Charts with cross-filtering: select a role to see related salary and demographics
- Tooltips and drill-throughs for detailed employee segments

How to Use
----------
1. Open the .pbix file in Power BI Desktop.
2. Use slicers to explore salary, leave, and demographic distribution.
3. Hover over visuals for deeper data insights.

Potential Improvements
----------------------
- Add department field for org-level insights
- Include performance metrics and attrition data
- Build time-based views using Date of Join
