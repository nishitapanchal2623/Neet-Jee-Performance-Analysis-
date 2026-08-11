# NEET-JEE Performance Analysis

## 📌 Project Overview

This project analyzes student entrance examination and academic performance data to understand patterns related to entrance scores, academic background, student categories, states, preferred streams, and admission outcomes.

The project focuses on exploratory data analysis (EDA), data cleaning, statistical analysis, and visualization of the dataset.

---

## 🎯 Objectives

- Understand the structure and characteristics of the student dataset.
- Identify and handle data quality issues.
- Analyze entrance examination performance.
- Study student performance across different categories and states.
- Analyze admission probability and admission status.

- Identify relationships between academic/performance variables.
- Present important findings through meaningful visualizations.

---

## 📂 Dataset

**Dataset:** `College_Admission.csv`

The dataset contains **25,000 student records and 13 columns**.

### Main Features

| Feature | Description |
|---|---|
| `student_id` | Unique student identifier |
| `age` | Student age |
| `gender` | Student gender |
| `category` | Student category |
| `state` | Student state |
| `preferred_stream` | Preferred academic stream |
| `entrance_exam` | Entrance examination |
| `entrance_score` | Entrance examination score |
| `board_percentage` | Board examination percentage |
| `extracurricular_score` | Extracurricular activity score |
| `admission_probability` | Estimated admission probability |
| `admission_status` | Admission outcome |
| `scholarship_eligibility` | Scholarship eligibility |

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📁 Project Structure

```text
Project1-NEET-JEE-Performance-Analysis/
│
├── data/
│   ├── raw/
│   │   └── College_Admission.csv
│   │
│   └── processed/
│       └── College_Admission_Cleaned.csv
│
├── notebooks/
│   ├── 01_Dataset_Understanding.ipynb
│   ├── 02_Data_Cleaning.ipynb
│   └── 03_Univariate_EDA.ipynb
│
├── README.md
└── LICENSE
---

## 🔍 Data Cleaning

The dataset was checked and validated for:

- Missing values
- Duplicate records
- Data types
- Categorical values
- Invalid numerical values

### Cleaning Results

- **Total Records:** 25,000
- **Total Columns:** 13
- **Missing Values:** 0
- **Duplicate Records:** 0

The original raw dataset was preserved, and the cleaned dataset was saved separately for further analysis.

---

## 📊 Exploratory Data Analysis

The project includes analysis of:

### Numerical Features

- Age distribution
- Entrance examination score
- Board percentage
- Extracurricular score
- Admission probability

### Categorical Features

- Gender
- Student category
- State
- Preferred stream
- Entrance examination
- Admission status

### Performance Analysis

- Average entrance score by examination
- Average admission probability by examination
- Category-wise entrance score
- Category-wise admission probability
- State-wise average entrance score
- Entrance score by admission status

### Relationship Analysis

- Entrance score vs admission probability
- Board percentage vs admission probability
- Correlation analysis of numerical variables

---

## 📈 Key Findings

- The dataset contains **25,000 student records** across **13 features**.
- No missing values or duplicate records were found.
- The dataset contains students from **26 states** and **5 student categories**.
- Entrance examination performance varies across CET, JEE, and NEET groups.
- Board percentage showed a strong relationship with admission probability in this dataset.
- Entrance score also showed a positive relationship with admission probability.
- Admission outcomes were compared using entrance scores and other student characteristics.
- Category and state-wise analyses were performed to understand differences in student performance.

---

## 📓 Notebooks

### `01_Dataset_Understanding.ipynb`

Explores the dataset structure, features, data types, descriptive statistics, and categorical variables.

### `02_Data_Cleaning.ipynb`

Performs data quality checks including missing values, duplicate records, data types, categorical values, and numerical values.

### `03_Univariate_EDA.ipynb`

Performs exploratory data analysis and visualizes student performance, entrance examination patterns, category-wise analysis, state-wise performance, admission outcomes, and relationships between important variables.

---

## 🚀 Future Scope

The project can be extended into an interactive student performance analysis application.

Possible future improvements include:

- Machine learning-based prediction
- Interactive dashboard
- Student performance analyzer
- Historical cutoff analysis
- College and stream recommendation features
- Web application deployment

---

## 👩‍💻 Author

**Nisheeta Panchal**

Data Science Student

---

## 📄 License

This project is created for educational and learning purposes.