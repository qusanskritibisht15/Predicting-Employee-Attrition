# Predicting-Employee-Attrition
This project analyzes employee attrition using machine learning and EDA. It identifies key factors like income, job level, age, and experience influencing attrition. Visualizations highlight workforce behavior patterns, helping HR teams design effective retention strategies.

**OVERVIEW**

This project focuses on analyzing employee attrition and identifying the key factors that influence whether employees stay or leave an organization. By using exploratory data analysis (EDA), statistical relationships, and rich visualizations, the goal is to convert raw HR records into meaningful insights. The analysis emphasizes how demographic, organizational, satisfaction-related, and compensation-based variables collectively shape attrition outcomes.
________________________________________
**OBJECTIVES**

•	To explore, clean, and visualize a multidimensional HR dataset.
•	To identify the main socio-economic and organizational drivers of employee attrition.
•	To compare behavioral and satisfaction patterns between retained and attrited employees.
•	To uncover trends in income, overtime workload, satisfaction, and job characteristics that influence turnover.
________________________________________
**DATASET DESCRIPTION**

File: 
Source: Simulated organizational HR dataset
The dataset provides a detailed overview of the workforce, including:
Feature	Description
Age	Employee age
Department	Department of employment
JobRole	Specific job designation
MonthlyIncome	Monthly salary
Gender	Male/Female
Job Satisfaction	Employee’s satisfaction score
Work-Life Balance	Balance rating
Overtime	Whether the employee works overtime
YearsAtCompany	Total years spent in the organization
NumCompaniesWorked	Past job experience
Environment Satisfaction	Work environment rating
Attrition	Whether the employee left the organization
This rich mix of demographic, satisfaction, performance, and employment-related variables supports detailed attrition analysis.
________________________________________
**LIBRARIES USED**

•	NumPy – Numerical operations
•	Pandas – Data cleaning and manipulation
•	Matplotlib – Core data visualization
•	Seaborn – Statistical plots and heatmaps
•	Scikit-learn – Preprocessing, splitting data, and basic modeling
•	Joblib – Model storage and serialization
________________________________________
**APPROACH**

1. Data Preprocessing

•	Loaded and validated the dataset using Pandas.

•	Checked data types, missing values, and corrected inconsistent entries.

•	Ensured the dataset was clean enough for reliable visualization and analysis.

2. Correlation Analysis

•	Generated correlation matrices for all numerical variables.

•	Used heatmaps and triangular correlation plots for clearer interpretation.

•	Mapped relationships between income, tenure, satisfaction scores, and attrition.

3. Data Visualization

Created multiple visualizations to compare retained vs. attrited employees, including:
•	Histograms for Age, Job Level, and Working Years

•	Income category comparisons to understand how salary influences attrition

•	Bar charts and countplots for categorical variables

•	Pie charts to show the overall retention-to-attrition ratio

These visualizations highlight how specific factors differ between groups.

4. Comparative Workforce Analysis

•	Compared attrition rates across income brackets, job roles, job levels, and salary hike ranges.

•	Identified clusters of employees with higher turnover likelihood—especially those with low satisfaction, mandatory overtime, and shorter experience.
________________________________________
**RESULTS**

Key findings reveal strong indicators of attrition:
•	Lower income employees show significantly higher attrition rates.
•	Overtime workers leave at substantially higher frequencies.
•	Lower job satisfaction and poor work-life balance strongly correlate with departure.
•	Employees early in their careers (shorter tenure, younger age) are more likely to leave.
•	Long-serving employees tend to remain, showing greater organizational loyalty.
These insights clearly map the risk factors driving turnover.
________________________________________
**VISUALIZATION**

Visualization	Description
Pair Plot	Shows relationships between numerical variables
Correlation Heatmap	Highlights interactions and dependencies among features
Triangular Heatmap	Cleaner, simplified correlation view
Attrition Pie Chart	Displays proportion of retained vs. attrited staff
Age & Job Level Charts	Visualizes attrition across age groups and job hierarchy
Income Category Chart	Contrasts attrition rates across salary levels
________________________________________
**CONCLUSION**

The Employee Attrition Analysis successfully transforms complex HR data into actionable insights. By identifying the socio-economic, behavioral, and organizational factors at the heart of employee turnover, this project provides a strong foundation for HR decision-making. These findings can help organizations:

•	Detect at-risk employees early

•	Improve retention strategies

•	Enhance compensation and career development policies

•	Strengthen workforce planning and well-being programs
________________________________________
**Author**

Sanskriti Bisht
