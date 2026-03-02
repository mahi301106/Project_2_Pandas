# 📊 Pandas CSV Reader & Basic Data Analysis

## 👩‍💻 Project Work Done By
**Mahrin Jawwad Arab**  

---

## 📌 Project Overview

This project demonstrates basic data analysis using Python and the Pandas library.  
The Titanic dataset (train.csv) is used to perform data exploration, statistical analysis, filtering operations, and data visualization.

---

## 🎯 Objectives

- Read a CSV file into a Pandas DataFrame
- Inspect dataset structure using head(), tail(), info(), and dtypes
- Compute summary statistics (mean, median, min, max, count)
- Filter rows based on specific conditions
- Select required columns
- Save filtered data into a new CSV file
- Create a basic data visualization chart

---

## 📂 Dataset Used

**Titanic Dataset (train.csv)**

The dataset contains passenger information such as:

- PassengerId
- Pclass
- Name
- Sex
- Age
- Fare
- Survived

---

## 🛠 Technologies Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook / VS Code

---

## 📊 Key Operations Performed

### 1️⃣ Data Loading
The CSV file was loaded into a Pandas DataFrame using:

```python
df = pd.read_csv("train.csv")

2️⃣ Data Inspection

df.head()

df.tail()

df.info()

df.dtypes

3️⃣ Summary Statistics

Mean Age

Median Fare

Minimum & Maximum values

Total Passenger Count

df.describe()

4️⃣ Data Filtering

Filtered passengers who survived:

survived = df[df["Survived"] == 1]
5️⃣ Saving Processed Data

The filtered dataset was saved as:

survived_passengers.csv
6️⃣ Data Visualization

A bar chart was created to visualize survival distribution using Matplotlib.

📈 Output

Filtered dataset file: survived_passengers.csv

Survival count bar chart visualization

🏁 Conclusion

This project demonstrates foundational data analysis skills using Python and Pandas.
It covers CSV handling, exploratory data analysis, filtering operations, file output, and basic visualization.

This serves as a beginner-level data analytics project showcasing practical implementation of Pandas.

⭐ Thank you for viewing this project!
