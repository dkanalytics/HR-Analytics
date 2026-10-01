# HR-Analytics

An interactive Excel dashboard that analyzes employee salaries, bonuses, demographics, and departmental pay trends. HR data is transformed into actionable business insights.

## The Scenario

Nexora is a simulated multinational company with employees across multiple departments and geographic regions.

The objective was to transform raw employee data into an interactive Excel dashboard that provides insight into workforce compensation, bonus allocation, demographics, and departmental salary trends. The dashboard enables HR and management teams to identify salary patterns, monitor compensation distribution, and make data-driven decisions regarding workforce planning.

<img width="100%" alt="Employee-Salary-Dashboard" src="https://github.com/user-attachments/assets/3d4518c1-3a07-4087-9be5-93a2842acda7" />

Interactive slicers to filter that data by Area and Department.

<img width="100%" alt="Main-Screen-Shot-GIF22" src="https://github.com/user-attachments/assets/a47c046f-f369-4fc5-b29d-7905a87f3db6" />

## Process
### 1. Generated and cleaned the raw dataset

The project began with a synthetic HR dataset containing employee records, including salaries, bonuses, departments, age, gender, performance ratings, and geographic location.

<img width="100%" alt="Raw-data" src="https://github.com/user-attachments/assets/30ca73e1-93b1-4071-b5b8-30b8edf0745f" />

The raw data was manually reviewed and cleaned to ensure consistency across fields, remove formatting issues, standardize values, and prepare the dataset for analysis.

### 2. Structured the data for analysis

The cleaned dataset was converted into a structured Excel Table, ensuring each row represented a single employee record and each column contained a unique employee attribute.

This made the dataset suitable for PivotTables, filtering, dashboard visuals, and future scalability.

<img width="100%" alt="Cleaned-data-consolidated" src="https://github.com/user-attachments/assets/53c9db68-fd0c-4afd-9e46-f34fa9a7399a" />


### 3. Performed exploratory analysis

Initial analysis was conducted to understand the distribution of salaries, employee demographics, departmental representation, and bonus allocation.

The dataset was reviewed to identify:

- Total workforce size
- Salary ranges
- Bonus participation rates
- Departmental salary differences
- Gender salary comparisons
- Age-related compensation trends
- Geographic workforce distribution

<img height="100%" alt="Insight-Calculations" src="https://github.com/user-attachments/assets/0038f3df-9e45-41cb-8db8-409b2132d273" />


### 4. Built calculation and KPI sheets

A dedicated calculations sheet was created to support dashboard metrics and business insights.

Key calculations included:

Total Employees
Total Salary Expenditure
Average Salary
Bonus Participation Percentage
Average Salary by Department
Average Salary by Gender
Employee Distribution by Area


These metrics were designed to provide a high-level summary of workforce compensation.

### 5. Built PivotTables and PivotCharts

PivotTables were used to aggregate and analyze the employee data from multiple perspectives.

Analysis included:
- Average Salary by Department
- Average Salary by Gender
- Employee Counts by Area
- Salary Trends by Age
- Bonus Distribution
- Workforce Demographics

PivotCharts were then created to visualize these findings and improve data accessibility.

<img width="100%" alt="Pivot-Tables" src="https://github.com/user-attachments/assets/89be2471-c9ef-45c9-84ed-30a534d0d127" />

### 6. Assembled the interactive dashboard

The dashboard was designed as a single-page reporting solution featuring:

KPI Cards
- Total Employees
- Total Salaries Paid
- Average Salary
- Bonus Participation %

<img width="100%" alt="Employee-Salary-Dashboard" src="https://github.com/user-attachments/assets/3f3e96b1-d6cf-4230-8453-93586d65e501" />


Interactive Slicers to filter Area and/or Department allows users to quickly explore employee compensation patterns and identify key workforce trends.

### 7. Transformed analysis into business insights

Rather than presenting raw metrics alone, the project focused on extracting actionable insights from the data.

#### Key findings included:

- HR and Procurement departments recorded the highest average salaries.
- Approximately 98% of employees received bonuses.
- Average salary generally increased with age and experience.
- Female employees earned slightly higher average salaries than male employees within the dataset.
- Salary levels varied across geographic regions and departments.
- Three out of 153 employees did not receive bonuses.

#### Action Items:

**1) Investigate the Website department's gender pay gap specifically.**

It is the one place where the company-wide "women earn more" pattern reverses, and by a wide margin — worth understanding whether that's role/seniority mix or something else before it becomes a compliance question.

**2) Review whether performance ratings should influence pay more than they currently do.**

With Poor and Very Poor performers earning about the same as Average performers, the current pay structure doesn't obviously incentivize the rating system it uses.

**3) Check the three zero-bonus employees individually.**

Confirm whether it's a deliberate policy reason (e.g. probation period, recent start) or a data entry gap.

<img width="100%" alt="nexora_key-insights" src="https://github.com/user-attachments/assets/ebbd5149-c5f3-4194-a58b-90fd55ff6c2e" />


These findings demonstrate how workforce data can be leveraged to support compensation and talent management decisions.

### 8. QA and validation

The dashboard underwent validation to ensure KPI values matched the underlying calculations and PivotTable outputs.

Checks included:

- Employee counts
- Salary totals
- Average salary calculations

Formula references and dashboard calculations were reviewed to ensure the reported figures accurately reflected the underlying dataset.

## Skills Demonstrated
- Data Cleaning and Validation
- Data Structuring and Preparation
- Exploratory Data Analysis (EDA)
- PivotTables and PivotCharts
- KPI Development
- Dashboard Design with interactive Reporting

This project uses a synthetic employee dataset created for analytics and dashboarding purposes. The raw data was manually cleaned, validated, and transformed prior to analysis and dashboard development.
