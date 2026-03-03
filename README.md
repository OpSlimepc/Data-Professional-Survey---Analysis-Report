# Data Professional Survey Analysis | Salary, Career Shifts & Workplace Insights
Excel + Power BI Project | Global Data Professionals Survey | From Raw Responses to Career Insights

## Table of Contents

-  [Project Overview](#project-overview)
-  [Tools & Technologies](#tools--technologies)
-  [Dataset Overview](#dataset-overview)
-  [Data Cleaning Process](#data-cleaning-process)
-  [Power BI Dashboard](#power-bi-dashboard)
-  [Key Insights](#key-insights)
-  [Recommendations](#recommendations)

---

### Project Overview
This project analyzes survey responses from data professionals to uncover trends in salary distribution, career transitions, work-life balance, job satisfaction, and their priorities.
The project transforms raw survey responses into actionable workforce insights using Excel and Power BI.

---

### Tools & Technologies
Tools & Technologies
1. Excel – Data cleaning & transformation
2. Power BI – Data modeling & dashboard visualization
3. DAX – Measures and calculated columns

---

### Dataset Overview
The dataset contains survey responses from 630 data professionals.

Key columns include:
1. Age
2. Gender
3. Country
4. Ethnicity
5. Current Industry
6. Favorite Programming Language
7. Salary
8. Work/Life Balance Rating
9. Satisfaction Ratings (Salary, Management, Learning, Growth)
10. Career Switch into Data (Yes/No)
11. Difficulty Breaking into Data
12. Important Factors for New Job

---

### Data Cleaning Process
Data cleaning and preprocessing were conducted using Microsoft Excel prior to visualization in Power BI. 
The following steps were performed:
1. Removed Unnecessary Columns
- Columns that are empty and those not relevant to the analysis were deleted to reduce noise and improve clarity in the data model.
2. Renamed Columns
- Column names were standardized for consistency and readability (e.g., shortened long survey questions into clear analytical field names).
3. Standardized Categorical Responses
- Many survey questions had open-ended responses with slight variations (e.g., different spellings or phrasing).
To ensure consistency:
Similar responses were grouped under a single standardized category.
- A new cleaned column was created to preserve original data while enabling structured analysis.
4. Reduced Category Noise
- Categories with fewer than 5 responses were grouped into an “Other” category to:
  - Improve visual clarity in dashboards
  - Prevent distortion from extremely small sample groups
  - Enhance readability of charts
5. Converted Salary Ranges to Numeric Values
The salary column originally contained ranges (e.g., "0-40k").
- To enable quantitative analysis:
  - Salary ranges were converted into their midpoint (average value).
  - The field was transformed into a numeric data type for aggregation and visualization.

---

### Power BI Dashboard
The interactive dashboard includes:
1. KPI Cards:
  - Total Survey Takers
  - Average Age of Takers
2. Salary Distribution
3. Career Switch Breakdown
4. Favorite Programming Language
5. Difficulty Breaking into Data
6. Work/Life Balance by Gender & Age
7. Satisfaction Ratings by Gender
8. Industry Distribution
9. Important Factors for New Job
10. Industry where Data Professionals Work
11. Interactive slicers allow filtering by:
  - Gender
  - Country
  - Ethnicity

<img width="1412" height="797" alt="image" src="https://github.com/user-attachments/assets/c15ac6c5-afe8-490d-b00b-f8e7b1d3b94b" />

---

### Key Insights
1. A majority of respondents transitioned into data from another career.
2. Python dominates as the most preferred programming language.
3. Salary is the most important factor when considering a new job.
4. Many respondents report moderate difficulty entering the data field.
5. Data professionals are distributed across diverse industries, with tech leading representation.
6. Work-life balance ratings are relatively consistent across genders and ages.

---

### Recommendations
* Organizations should prioritize competitive salary offerings.
* Flexible work arrangements remain a strong attraction factor.
* Upskilling in Python remains a valuable investment.

---


Dataset source:
[Download Here](https://www.kaggle.com/datasets/alptheanalyst/data-professionals-survey)
