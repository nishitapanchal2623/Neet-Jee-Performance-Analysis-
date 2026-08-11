# NEET-JEE Exam Performance Analysis

## 1. Project Overview

This project performs Exploratory Data Analysis (EDA) on a student entrance examination and admission dataset.

The analysis focuses on understanding student performance patterns across entrance examinations, states, student categories, academic performance, and admission outcomes.

The project includes dataset understanding, data cleaning, exploratory analysis, statistical relationships, and meaningful visualizations.

## 2. Objectives

The main objectives of this project are:

- Understand the structure and characteristics of the dataset.
- Validate and clean the dataset.
- Analyze entrance examination score distributions.
- Compare student performance across different examinations.
- Analyze state-wise student performance.
- Study performance across different student categories.
- Analyze admission probability and admission status.
- Identify relationships between academic and performance variables.
- Summarize the major insights obtained from the analysis.

## 3. Dataset Description

The dataset used for this project is `College_Admission.csv`.

It contains **25,000 student records** and **13 features** related to student demographics, academic performance, entrance examinations, and admission outcomes.

### Dataset Features

| Feature | Description |
|---|---|
| `student_id` | Unique identifier assigned to each student |
| `age` | Age of the student |
| `gender` | Gender of the student |
| `category` | Student category |
| `state` | State of the student |
| `preferred_stream` | Preferred academic stream |
| `entrance_exam` | Entrance examination taken |
| `entrance_score` | Score obtained in the entrance examination |
| `board_percentage` | Percentage obtained in board examinations |
| `extracurricular_score` | Score representing extracurricular performance |
| `admission_probability` | Admission probability value |
| `admission_status` | Admission outcome |
| `scholarship_eligibility` | Scholarship eligibility status |

### Dataset Structure

- **Number of records:** 25,000
- **Number of features:** 13
- **Numerical and categorical features:** Present
- **States represented:** 26
- **Student categories:** 5

## 4. Data Cleaning and Validation

Before performing exploratory data analysis, the dataset was checked for common data quality issues.

The following validation steps were performed:

### 4.1 Missing Values

The dataset was checked for missing values across all columns.

**Result:** No missing values were found.

- Total missing values: **0**

Therefore, no missing-value imputation was required.

### 4.2 Duplicate Records

The dataset was checked for duplicate rows.

**Result:** No duplicate records were found.

- Total duplicate records: **0**

### 4.3 Data Type Validation

The data types of all columns were inspected to ensure that numerical and categorical variables were represented appropriately.

### 4.4 Categorical Value Validation

Categorical variables such as gender, category, state, preferred stream, entrance examination, and admission status were examined to understand their unique values and ensure consistency.

### 4.5 Numerical Value Validation

Numerical variables such as age, entrance score, board percentage, extracurricular score, and admission probability were checked for valid values and reasonable ranges.

### Cleaning Summary

| Validation Check | Result |
|---|---:|
| Total Records | 25,000 |
| Total Columns | 13 |
| Missing Values | 0 |
| Duplicate Records | 0 |
| Data Type Validation | Completed |
| Categorical Validation | Completed |
| Numerical Validation | Completed |

The validated dataset was saved as `College_Admission_Cleaned.csv` for further analysis.

## 5. Exploratory Data Analysis

Exploratory Data Analysis was performed to understand the distribution of student characteristics, entrance examination performance, academic performance, and admission-related variables.

The analysis used visualizations to identify important patterns and relationships in the dataset.

### 5.1 Numerical Feature Analysis

The distributions of the following numerical variables were analyzed:

- Age
- Entrance examination score
- Board percentage
- Extracurricular score
- Admission probability

Box plots were also used for selected numerical variables to understand their spread and identify potential outliers.

### 5.2 Categorical Feature Analysis

The following categorical variables were analyzed:

- Gender
- Student category
- State
- Preferred stream
- Entrance examination
- Admission status

These analyses helped understand the composition of the student population and the distribution of students across different groups.

### 5.3 Entrance Examination Analysis

The average entrance score and average admission probability were compared across different entrance examinations.

This analysis helps identify differences in performance and admission-related patterns among the examination groups.

### 5.4 Category Analysis

Student performance was analyzed across different categories.

The analysis includes:

- Average entrance score by category
- Average admission probability by category
- Overall category distribution

Category was retained as an important analytical variable because admission-related patterns can differ across student categories.

### 5.5 State-wise Performance

Average entrance examination scores were compared across the different states represented in the dataset.

This provides an overview of geographical differences in entrance examination performance.

### 5.6 Admission Outcome Analysis

Entrance scores were compared between students with different admission statuses.

This helps examine whether entrance examination performance is associated with admission outcomes.

### 5.7 Relationship Analysis

Relationships between important numerical variables were examined using scatter plots and correlation analysis.

The main relationships analyzed were:

- Entrance score vs admission probability
- Board percentage vs admission probability
- Correlation between numerical variables

A correlation heatmap was used to provide an overall view of relationships among the numerical variables.

## 6. Key Findings and Overall Insights

The exploratory analysis revealed several important patterns in the student performance and admission dataset.

### 6.1 Entrance Examination Performance

The average entrance scores differed across the examination groups present in the dataset.

- CET students had an average entrance score of approximately **99.97**.
- JEE students had an average entrance score of approximately **146.50**.
- NEET students had an average entrance score of approximately **354.78**.

These values should be interpreted within the scoring scales and characteristics of the respective examinations.

### 6.2 Admission Probability

Average admission probability also varied across examination groups:

- CET: approximately **0.339**
- JEE: approximately **0.372**
- NEET: approximately **0.505**

This indicates differences in admission-related patterns among the examination groups represented in the dataset.

### 6.3 Relationship Between Entrance Score and Admission Probability

Entrance score showed a positive correlation with admission probability, with a correlation coefficient of approximately **0.554**.

This suggests that students with higher entrance scores generally tend to have higher admission probabilities within this dataset.

### 6.4 Relationship Between Board Percentage and Admission Probability

Board percentage showed the strongest positive correlation with admission probability among the analyzed numerical variables, with a correlation coefficient of approximately **0.727**.

This indicates a strong positive relationship between board percentage and admission probability in this dataset.

### 6.5 Extracurricular Performance

Extracurricular score showed a positive relationship with admission probability, with a correlation of approximately **0.40**.

The relationship is weaker than the relationships observed for board percentage and entrance score.

### 6.6 Admission Status

The dataset contains:

- **8,152 admitted students**
- **16,848 rejected students**

The analysis of entrance scores by admission status showed that admitted students generally had higher entrance scores than rejected students.

### 6.7 Category Analysis

Student categories were analyzed using entrance scores and admission probability.

The category distribution provides an overview of the student population, while category-wise performance analysis helps identify differences between student groups.

### 6.8 State-wise Performance

Average entrance scores were compared across the **26 states** represented in the dataset.

This analysis provides a state-wise view of student entrance examination performance.

### 6.9 Overall Insight

Overall, the analysis indicates that academic and entrance examination performance are associated with admission-related outcomes in the dataset. Board percentage and entrance score showed particularly strong positive relationships with admission probability.

However, these findings represent patterns within the available dataset and should not be interpreted as actual NEET/JEE admission cutoffs or guaranteed admission criteria.

## 7. Conclusion

The NEET-JEE Performance Analysis project provided an overview of student academic and entrance examination performance using exploratory data analysis.

The dataset was successfully validated, with no missing values or duplicate records. Multiple analyses were performed to understand score distributions, examination-wise performance, category-wise patterns, state-wise performance, and admission outcomes.

The correlation analysis showed that board percentage and entrance score had positive relationships with admission probability in the analyzed dataset.

Overall, the project demonstrates how data cleaning, exploratory analysis, statistical relationships, and visualization can be used to identify meaningful patterns in student admission data.

## 8. Tools and Libraries

The following tools and Python libraries were used for this project:

- **Python** — Programming language used for data analysis
- **Pandas** — Data manipulation and analysis
- **NumPy** — Numerical operations
- **Matplotlib** — Data visualization
- **Seaborn** — Statistical data visualization
- **Jupyter Notebook** — Interactive development and analysis environment

## 9. Project Limitations and Future Scope

### Limitations

- The analysis is based only on the provided dataset.
- The dataset does not represent official NEET/JEE cutoff data.
- Correlation represents association and does not establish causation.
- The results should not be used as a guaranteed admission prediction.

### Future Scope

The project can be extended by:

- Adding historical official cutoff datasets.
- Building an interactive student performance dashboard.
- Developing a machine learning model for prediction.
- Creating a student performance analyzer web application.
- Adding college and course-level analysis when suitable data is available.