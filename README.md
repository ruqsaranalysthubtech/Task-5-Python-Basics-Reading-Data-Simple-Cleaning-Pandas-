# Task-5-Python-Basics-Reading-Data-Simple-Cleaning-Pandas-
# Task 5 – Data Cleaning with Pandas (Titanic Dataset)

##  Objective
The objective of this task is to perform basic data cleaning and preprocessing using Python Pandas. This includes reading the dataset, identifying and handling missing values, removing duplicates, optimizing data types, creating new features, and exporting a cleaned dataset for further analysis.

---

##  Dataset
**Titanic Dataset**

The dataset contains information about passengers aboard the Titanic, including:
- Passenger demographics
- Ticket class
- Fare details
- Survival status

This dataset is commonly used to practice data cleaning and exploratory data analysis.

---

##  Tools & Technologies Used
- Python
- Pandas
- NumPy
- Google Colab / Jupyter Notebook

---

##  Steps Performed

1. Loaded the Titanic dataset using Pandas.
2. Inspected the dataset using `head()` and `info()` to understand structure and data types.
3. Identified missing values using `isnull().sum()`.
4. Handled missing values:
   - Filled missing `Age` values using median.
   - Filled missing `Embarked` values using mode.
   - Dropped the `Cabin` column due to excessive missing values.
5. Removed duplicate records to maintain data accuracy.
6. Converted relevant columns to categorical data types.
7. Created new features:
   - `Age_Group` to categorize passengers by age.
   - `Family_Size` to represent total family members onboard.
8. Validated the cleaned dataset.
9. Exported the final cleaned dataset as a CSV file.

---




---

##  Output
- **cleaned_titanic_data.csv**  
  A cleaned and processed version of the Titanic dataset, ready for analysis or visualization.

---

## Outcome
This task helped in gaining hands-on experience with:
- Pandas data cleaning techniques
- Handling real-world data issues
- Writing clean, future-safe Python code
- Documenting data analysis workflows

---

##  Key Learnings
- Importance of handling missing values appropriately
- Avoiding chained assignment warnings in Pandas
- Feature engineering for better insights
- Why Python is more efficient than Excel for large datasets

---

## Author
**Ruqsar Begum**  
Aspiring Data Analyst
