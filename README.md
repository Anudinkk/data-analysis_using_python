# Employee Data Analysis Project

## Summary

This project involves a complete analysis of employee dataset.  
The dataset includes **458 employees** across various teams and positions.

---

## Business Problem

Needs a better understanding of:  
- Determine the distribution of employees across each team and calculate the percentage split relative to the total number of employees.
- Segregate employees based on their positions within the company.
- Identify the predominant age group among employees.
- Discover which team and position have the highest salary expenditure.
- Investigate if there's any correlation between age and salary, and represent it visually.

---

## Technologies Used

- Python 3.11
- pandas
- numpy
- matplotlib
- seaborn
- openpyxl (for Excel file handling)

---

## Data Preprocessing

- Replaced invalid or missing values in the **Height** column.
- Generated realistic height values randomly between **150 cm and 180 cm**.

```python
import numpy as np
np.random.seed(42)
df['Height'] = np.random.randint(150, 181, size=len(df))
```

---

## Analysis and Key Findings

### 1. Team Distribution
- **New Orleans Pelicans** has most number of employees followed by **Memphis Grizzlies** team.

*Visualization:* Bar Plot showing employee count by Team.

---

### 2. Position Segregation
- Majority of employees are **SG** and **PF**.
- **C** Position have least number of employees

*Visualization:* count Plot showing employee count by Position.

---

### 3. Age Grouping
- Created clear age brackets: **11–20**,**21–30**, **31–40**, **41–50**.
- Employees aged **21–30** dominate the workforce.

*Visualization:* Bar Plot showing distribution by Age Groups.

---

### 4. Salary Expenditure
- **Cleveland Cavaliers** consumes the **highest salary budget** among teams.
- **C** contribute the highest total salary among all positions.

*Visualization:* Bar Charts of Total Salary by Team and by Position.

---

### 5. Correlation: Age vs Salary
- Correlation: **~0.21**.
- Conclusion: **No significant relationship** between employee age and salary.

*Visualization:* Scatter Plot (Age vs Salary).

---


## Conclusion

This analysis provided valuable insights into the employee structure and salary distribution at ABC Company.  
It helps stakeholders to make decisions and solving the problems.

---


# Thank you

---

