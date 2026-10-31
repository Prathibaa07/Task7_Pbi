# Task 7: Students Performance Dashboard using Power BI

## Project Overview
This project focuses on analyzing student performance using Microsoft Power BI.

The objective is to understand students' academic performance through data analysis and visualization. The project uses the Students Performance dataset to explore student scores and identify performance patterns.

## Objective
- Analyze student academic performance.
- Understand students' mathematics, reading, and writing scores.
- Calculate average student scores using DAX.
- Create meaningful visualizations using Power BI.
- Present student performance information through a dashboard.

## Dataset
**Dataset Name:** Students Performance

The dataset contains student information and academic scores.

### Important Dataset Columns
- Gender
- Race/Ethnicity
- Parental Level of Education
- Lunch
- Test Preparation Course
- Math Score
- Reading Score
- Writing Score

## Tools and Technologies
- Microsoft Power BI Desktop
- Power Query
- DAX (Data Analysis Expressions)
- CSV Dataset

## Data Preparation
The dataset was imported into Power BI for analysis.

The following activities were performed:
- Imported the student performance dataset.
- Checked the available columns.
- Reviewed the academic score fields.
- Prepared the dataset for visualization.
- Created DAX measures for score analysis.

## DAX Measures

### Average Math Score
```dax
Avg_Math_Score =
AVERAGE('StudentsPerformance'[math score])
```

### Average Reading Score
```dax
Avg_Reading_Score =
AVERAGE('StudentsPerformance'[reading score])
```

### Average Writing Score
```dax
Avg_Writing_Score =
AVERAGE('StudentsPerformance'[writing score])
```

### Total Students
```dax
Total_Students =
COUNTROWS('StudentsPerformance')
```

## Dashboard Analysis

### 1. Student Performance Analysis
Analyze students' academic scores in mathematics, reading, and writing.

### 2. Gender Analysis
Compare academic performance between male and female students.

### 3. Parental Education Analysis
Analyze student scores based on parents' educational qualifications.

### 4. Test Preparation Analysis
Compare student performance based on completion of the test preparation course.

### 5. Lunch Category Analysis
Analyze academic performance based on students' lunch categories.

## Visualization
Power BI visualizations can be used to analyze:
- Average mathematics scores
- Average reading scores
- Average writing scores
- Student distribution by gender
- Performance based on parental education
- Performance based on test preparation
- Performance based on lunch category

## Interactive Features
Interactive slicers can be used to filter student performance by:
- Gender
- Race/Ethnicity
- Parental Level of Education
- Lunch
- Test Preparation Course

These features help users explore student performance across different categories.

## Dashboard Formatting
- Added a meaningful dashboard title.
- Used suitable charts for student performance analysis.
- Organized visualizations clearly.
- Applied appropriate labels and formatting.
- Used DAX measures for academic score analysis.

## Results
The project provides a structured approach to understanding student academic performance.

The analysis helps compare mathematics, reading, and writing scores and explore how different student categories relate to academic results.

## Deliverables
- Power BI Project File (.pbix)
- DAX Measures
- Dashboard Screenshots

## Conclusion
The Students Performance Power BI project demonstrates the use of data visualization and DAX measures for academic performance analysis.

The project helps understand student score patterns and provides a foundation for exploring academic performance using interactive Power BI visualizations.

**Project:** Task 7 – Students Performance

**Tool:** Microsoft Power BI Desktop
