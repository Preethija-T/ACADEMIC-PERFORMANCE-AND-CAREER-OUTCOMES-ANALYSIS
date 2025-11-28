# 📊 ACADEMIC PERFORMANCE AND CAREER OUTCOMES ANALYSIS

> **Tools:** Power BI | Excel | DAX | Power Query | Data Modeling  
> **Domain:** Education | Career Analytics

![Power BI](https://img.shields.io/badge/Tool-Power%20BI-yellow)
![Excel](https://img.shields.io/badge/Tool-Excel-green)
![Domain-Education](https://img.shields.io/badge/Domain-Education-blue)
![Language-DAX](https://img.shields.io/badge/Language-DAX-orange)


## 📘 Project Overview
This project analyses how different educational factors—such as degree level, grades, skills, and certifications—impact career outcomes like employment, salary, and career growth. 
The goal is to understand what education-related factors contribute most to career success.

---

## 🎯 Project Objectives

•	Identify the link between education level and career success.

•	Analyze how skills and certifications influence job opportunities.

•	Study the impact of academic performance on salary and employment.

•	Provide insights that help students and job seekers make better career decisions.

•	Visualize key trends using dashboards for easy understanding.


---

## 📂 Data Sources

**Sources & Timeline:**
Source Description and Timeline: The data comes from a student survey dataset that tracks 
academic performance, skills, internships, and early career outcomes such as job offers, salary, and promotions.Include original filename and 
download URL here. https://www.kaggle.com/datasets/adilshamim8/education-and-career-success

**Domain:** Education

---

## ❓ Problem Statement

Students follow different educational paths, but not all achieve the same career outcomes. This project aims to identify which academic, skill-based, and personal factors most strongly influence job offers, salary, and early career growth.

•	Analyze academic performance, skills, internships, and certifications.

•	Study their impact on job offers, salary, promotions, and satisfaction.

•	Provide insights to help students make better education and career decisions.

---

## 🧾 Attribute Details

| **Attribute Name** | **Description** |
|--------------------|---------------|
| Student_ID	| Unique identifier for each student in the dataset |
| Age	|  Student’s age at the time of data collection |
| Gender	| Gender of the student (Male/Female) |
| High_School_GPA	| Academic performance score from high school |
| SAT_Score	| Standardized test score for college admission |
| University_GPA	| GPA obtained during university/college education |
| Field_of_Study	| The academic major or department (e.g., Engineering, Business, Science) |
| Internships_Completed	| Number of internships completed by the student |
| Projects_Completed	| Number of academic or personal projects done |
| Certifications |	Count of professional or technical certifications earned |
| Soft_Skills_Score	| Score representing communication, teamwork, leadership, etc |
| Networking_Score	| Score showing how well the student builds professional connections |
| Job_Offers	| Number of job offers received after graduation |
| Starting_Salary	| Salary offered at the student’s first job |
| Career_Satisfaction	| Student’s satisfaction level with their career (scale-based) |
| Years_to_Promotion	| Time taken to get the first promotion |
| Current_Job_Level		| Position level in the current job (e.g., Entry, Mid, Senior) |
|Work_Life_Balance	| Rating of work-life balance in their job |
|Entrepreneurship 	| Indicates whether the student started a business (Yes/No or score) |
| GPA Improvement		| GPA improvement from High school to university |
| Total Experience	| Total of Internship, projects and certificates |

---


## 🧹 Data Preprocessing Steps (Power Query)

### 1. Load Data
Load the dataset into Power Query Editor.

### 2. Remove Unnecessary Columns
Remove columns not needed for analysis (e.g., Student_ID if not required for visualization).

### 3. Handle Missing Values
Replace or remove missing/null values

### 4. Correct Data Types
Ensure each column has the correct data type:

o	Numeric → Age, GPA, SAT_Score, Job_Offers, Starting_Salary

o	Text → Gender, Field_of_Study

o	Date/Time → if any timestamp columns

### 5. Filter Outliers or Invalid Data
Filter rows with invalid data (e.g., negative GPA or salary)

### 6. Create New Columns (Optional)
Derive useful features:

o	Total Experience = Years_to_Promotion + 1 (example)

o	Career Readiness Score = Soft_Skills_Score + Networking_Score

### 7. Sort and Organize Data
Sort by GPA, Starting Salary, or Job Offers for analysis.

### 8. Load Cleaned Data
After preprocessing, Close & Apply to load the data into Power BI for visualization


---

## 📉 Analysis & Visualizations

Developed **interactive Power BI dashboards** addressing all problem statements using:
### ✅1. Pie Chart (Gender Distribution)
The pie chart shows a balanced gender distribution, with 50% Female (200 students) and 50% Male (200 students). 
This equal representation indicates that the dataset is gender-neutral, allowing unbiased comparisons in academic performance, skills, and placement outcomes.

### ✅2. Stacked Bar Chart (Field of study Distribution)
Business has the highest student enrollment (72), followed by Engineering (58) and Psychology (55). 
Fields like Finance, Education, and Nursing have very low representation, indicating niche or less preferred disciplines.

### ✅3. Line Chart (Students in different age group)
Student distribution across ages is almost equal for both genders. Each age group (21–25) has around 39–41 students, showing a balanced and consistent representation across gender and age.

### ✅4. Funnel Chart (Gender by Field of Study)
Business, Engineering, Psychology, and Computer Science have the highest student enrollment, while fields like Finance, Education, and Nursing have very few students, indicating niche or less preferred areas.

### ✅5. Line Chart (student vs University GPA)
Female students dominate the higher GPA ranges (3.5 to 4.0), while male students are more concentrated in mid-range GPAs (3.0 to 3.4). 
This suggests that female students consistently achieve slightly higher academic performance overall.
                           
### ✅6. Scatter Chart (SAT score vs University GPA)
Female students are more concentrated in the higher GPA ranges (3.5–4.0), while male students show stronger representation in the mid-range GPAs (3.0–3.4). This suggests that female students slightly outperform male students academically.
                           
### ✅7. Stacked Column Chart (Field of study by Work Life balance)
Most students rate their work-life balance as 6 or 7, indicating a generally moderate and manageable lifestyle. Very few students rate extremely low or extremely high, showing a balanced overall trend.

### ✅8. Donut Chart (Job offers by Gender)
Female students received a higher total number of job offers (611) compared to male students (485), suggesting stronger placement outcomes for female students.
                             
### ✅9. Bar Chart (starting salary by field of study)
Students from Computer Science, Business, and Engineering have the highest total starting salaries, indicating that technical and management fields offer stronger initial earning potential. 
Fields like Education, Nursing, and Finance have the lowest total starting salaries.

### ✅10. Area Chart (Job offers for university GPA)
Students with higher GPAs generally receive more job offers, with a noticeable increase starting from GPA 3.4. The trend peaks around GPA 3.7–3.9, showing a strong correlation between academic performance and employability.
                              
### ✅11. Column Chart (Internships completed)
Most students have completed 2–3 internships, indicating strong engagement in practical experience. Very few students have no internships (10) or 4 internships (76), showing a balanced but active participation in internship programs.
                              
### ✅12. Tree map (Job offers by field of study)
Students in Computer Science, Business, and Engineering receive the highest number of job offers, while fields like Education, Nursing, and Finance receive the fewest, reflecting strong employability in technical and management disciplines.



---

## 📈 Performance Insights

- The dataset shows a balanced gender distribution and consistent age groups (21–25).
  
- Popular fields include Business, Engineering, Psychology, and Computer Science, while Finance, Education, and Nursing have fewer students.
  
- Female students excel in higher GPAs and received more job offers than males, with top offers in technical and management fields.
  
- Most students complete 2–3 internships, maintain a moderate work-life balance, and higher GPAs strongly correlate with increased employability and starting salaries.           

---

## 🧠 Conclusion

A combination of strong academics, practical experience, soft skills, and networking significantly improves career success. 
Insights can guide students toward smarter academic and professional development choices.

---

## 👩‍💻 Author

**Preethija T**  
*Data Analyst | Power BI Developer*  

- 🌐 GitHub: (https://github.com/Preethija-T) 
- 💼 LinkedIn:(www.linkedin.com/in/preethija23051989)
- 📧 Email: Preethija23@gmail.com

If you found this project useful or have feedback, feel free to reach out!  

---

## 📚 Tags
`#PowerBI` `#DataAnalysis` `#MutualFunds` `#FinanceAnalytics`  
`#DAX` `#DataVisualization` `#ExcelPowerQuery`

