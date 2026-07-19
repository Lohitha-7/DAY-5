# DAY-5
📅 Day 5 – Data Cleaning
# 🧹 Day 5 – Data Cleaning Using Pandas

## 📌 Project Overview

Data cleaning is one of the most important steps in the data analysis process. Real-world datasets often contain missing values, duplicate records, inconsistent formats, and incorrect data types that can affect the accuracy of analysis. In this project, I used the **Pandas** library in Python to clean a CSV dataset and prepare it for further analysis.

The goal of this task was to improve the quality of the dataset by identifying and handling missing values, removing duplicate records, and converting columns to the correct data types.

---

# 🎯 Objectives

The main objectives of this project are:

- Learn the importance of data cleaning.
- Detect missing values in a dataset.
- Handle missing data using appropriate methods.
- Remove duplicate records.
- Convert incorrect data types into the correct format.
- Prepare a clean dataset for analysis and visualization.

---

# 🛠 Technologies Used

- **Python** – Programming language
- **Pandas** – Data manipulation and cleaning library
- **Jupyter Notebook** – Development environment
- **CSV Dataset** – Source of data

---

# 📂 Dataset

The dataset used in this task is a CSV file containing sample student information.

Example columns include:

- Student ID
- Name
- Age
- Gender
- Department
- Marks
- Attendance

The dataset may contain missing values, duplicate records, or incorrect data types that need to be corrected.

---

# 📋 Tasks Performed

## ✅ 1. Loaded the Dataset

Imported the dataset into Pandas using the `read_csv()` function.

---

## ✅ 2. Checked Missing Values

Used the `isnull()` function to identify missing values in every column.

This helps understand which columns require cleaning.

---

## ✅ 3. Handled Missing Values

Filled missing values using suitable methods such as:

- Replacing with 0
- Replacing with mean
- Replacing with median
- Replacing with mode

This ensures that incomplete records do not affect further analysis.

---

## ✅ 4. Removed Duplicate Records

Used the `drop_duplicates()` function to eliminate duplicate rows from the dataset.

Removing duplicates improves data quality and prevents repeated information.

---

## ✅ 5. Corrected Data Types

Converted columns into appropriate data types.

Examples:

- Marks → Integer
- Age → Integer
- Salary → Float
- Date → Datetime

Correct data types improve memory efficiency and enable accurate calculations.

---

## ✅ 6. Verified the Clean Dataset

Checked:

- Dataset information
- Number of rows
- Number of columns
- Data types
- Missing values after cleaning

This confirms that the dataset is ready for analysis.

---

# 📊 Data Cleaning Workflow

```
Load Dataset
      │
      ▼
Check Missing Values
      │
      ▼
Handle Missing Values
      │
      ▼
Remove Duplicate Records
      │
      ▼
Correct Data Types
      │
      ▼
Verify Clean Dataset
```

---

# 📌 Functions Used

| Function | Purpose |
|----------|---------|
| read_csv() | Load dataset |
| isnull() | Find missing values |
| fillna() | Fill missing values |
| drop_duplicates() | Remove duplicate rows |
| astype() | Change data type |
| info() | View dataset information |
| dtypes | Display column data types |

---

# 💻 Sample Code

```python
import pandas as pd

# Load dataset
data = pd.read_csv("students.csv")

# Check missing values
print(data.isnull().sum())

# Fill missing values
data.fillna(0, inplace=True)

# Remove duplicate rows
data.drop_duplicates(inplace=True)

# Convert data type
data["Marks"] = data["Marks"].astype(int)

# Display dataset information
print(data.info())
```

---

# 📈 Expected Outcome

After completing the data cleaning process:

- Dataset contains no missing values.
- Duplicate records are removed.
- Data types are correctly assigned.
- Dataset becomes accurate and reliable.
- Clean data is ready for filtering, analysis, and visualization.

---

# 🎯 Learning Outcomes

By completing this task, I learned how to:

- Identify data quality issues.
- Handle missing values using Pandas.
- Remove duplicate records efficiently.
- Convert incorrect data types.
- Prepare datasets for further analysis.
- Improve the accuracy and reliability of data.

---

# 🚀 Future Scope

The cleaned dataset can now be used for:

- Data Filtering
- Statistical Analysis
- Data Visualization
- Dashboard Development
- Business Insights
- Machine Learning Models

---

# 📌 Conclusion

Data cleaning is a crucial step in every data analytics project. By removing inconsistencies, handling missing values, and correcting data types, the dataset becomes more accurate and suitable for analysis. This task strengthened my understanding of data preprocessing using Pandas and prepared me for the next stages of the data analytics workflow.

---

## 👩‍💻 Author

**Ketha Lohitha**  
**B.Tech – Data Science**  
**Data Analytics Internship – Day 5**
