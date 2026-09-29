# 📊 Exploratory Data Analysis – Adult Income Dataset

<p align="center">

### 🔎 Data Analysis | 🐍 Python | 📈 Visualization | 🧹 Data Cleaning

</p>

---

## 🌟 Project Overview

Welcome to my **Exploratory Data Analysis (EDA)** project!

In this project, I performed **data cleaning, data exploration, statistical analysis, and visualization** using the **Adult Income Dataset**.

The main purpose of this project is to understand the data, discover patterns and relationships between different variables, and analyze factors associated with income categories.

> 💡 **Project Focus:** Understanding demographic, educational, employment, and income-related patterns through data analysis.

---

## 🚀 Project Highlights

| 🔹 Area          | 📌 Details             |
| ---------------- | ---------------------- |
| 📂 Dataset       | Adult Income Dataset   |
| 📊 Records       | 32,561                 |
| 📋 Features      | 15                     |
| 🎯 Target        | Income                 |
| 🧹 Data Cleaning | Missing/unknown values |
| 📈 Visualization | Charts and graphs      |
| 🐍 Language      | Python                 |
| ☁️ Platform      | Google Colab           |

---

## 🛠️ Technologies & Tools

<p align="center">

🐍 **Python**
🐼 **Pandas**
🔢 **NumPy**
📊 **Matplotlib**
☁️ **Google Colab**
📈 **Data Visualization**

</p>

---

## 📁 Dataset Information

The dataset contains information about individuals such as:

* 👤 Age
* 💼 Workclass
* 🎓 Education
* 💍 Marital Status
* 👨‍💼 Occupation
* 👨‍👩‍👧 Relationship
* 🌎 Race
* ⚧️ Gender
* 💰 Capital Gain
* 📉 Capital Loss
* ⏰ Hours per Week
* 🌍 Native Country
* 💵 Income

### 🎯 Target Variable

`Income`

The income categories are:

```text
<=50K
>50K
```

---

## 🔄 EDA Workflow

```mermaid
flowchart LR
    A[📂 Load Dataset] --> B[🔍 Understand Data]
    B --> C[🧹 Clean Data]
    C --> D[❓ Handle Missing Values]
    D --> E[📊 Statistical Analysis]
    E --> F[📈 Data Visualization]
    F --> G[🔎 Find Patterns]
    G --> H[💡 Generate Insights]
```

---

# 🔍 Exploratory Data Analysis

## 1️⃣ Understanding the Dataset

I used Pandas functions to understand the dataset structure.

```python
data.head()
data.tail()
data.info()
data.describe()
data.columns
data.shape
data.size
data.count()
```

### 📌 What these functions help with

| Function     | Purpose                     |
| ------------ | --------------------------- |
| `head()`     | 🔝 First records            |
| `tail()`     | 🔚 Last records             |
| `info()`     | ℹ️ Data types & information |
| `describe()` | 📊 Statistical summary      |
| `columns`    | 📋 Column names             |
| `shape`      | 📐 Rows & columns           |
| `size`       | 🔢 Total elements           |
| `count()`    | 🔢 Non-null values          |

---

## 2️⃣ 🧹 Data Cleaning

The dataset was checked for missing and unknown values.

```python
data.isnull().sum()
```

The dataset contains unknown values represented by:

```text
?
```

These values were identified and considered during preprocessing.

### 🧹 Cleaning Steps

* 🔎 Checked missing values
* ❓ Identified `?` values
* 🔁 Checked duplicate records
* 🏷️ Examined categorical values
* 🔢 Checked numerical columns
* ✨ Prepared the dataset for analysis

---

# 📊 Data Visualization

Visualization was an important part of this project because charts make patterns easier to understand.

### 📈 Visualizations explored

* 📊 Income Distribution
* 👤 Age Distribution
* 🎓 Education Distribution
* 💼 Workclass Distribution
* 👨‍💼 Occupation Distribution
* ⚧️ Gender Distribution
* ⏰ Hours per Week
* 💰 Capital Gain
* 📉 Capital Loss
* 🎓 Education vs Income
* 👤 Age vs Income
* ⚧️ Gender vs Income
* 💼 Occupation vs Income
* ⏰ Working Hours vs Income

---

## 📊 Example Visualization Section

### 💵 Income Distribution

> 📌 This visualization shows the distribution of individuals across the two income categories.

**Recommended chart:** Bar Chart / Count Plot

```text
Income
  │
  │       █████████████████
  │       █████████████████
  │       █████████████████
  │  █████████
  │  █████████
  └────────────────────────
       <=50K       >50K
```

---

### 🎓 Education Analysis

Education levels can be explored to understand the distribution of educational qualifications within the dataset.

**Recommended chart:** Bar Chart

```text
Education
    │
    │ ███████████████
    │ █████████████
    │ ███████████
    │ █████████
    │ ███████
    └──────────────────
```

---

### 👤 Age Distribution

A histogram can be used to understand the distribution of ages.

**Recommended chart:** Histogram

```text
Frequency
   │       ███
   │     ███████
   │   ███████████
   │ ███████████████
   │█████████████████
   └──────────────────── Age
```

---

# 🔎 Analysis Questions

During the EDA process, I explored questions such as:

### 👤 Demographic Analysis

* What is the age distribution?
* What is the gender distribution?
* What are the common marital statuses?
* Which countries are represented in the dataset?

### 🎓 Education Analysis

* Which education levels are most common?
* How does education relate to income?
* How does `EducationNum` vary across income groups?

### 💼 Employment Analysis

* Which workclasses are most common?
* Which occupations occur most frequently?
* How does occupation relate to income?

### 💰 Income Analysis

* What is the distribution of `Income`?
* How does age vary between income groups?
* How does education relate to income?
* How do working hours vary between income categories?

---

# 📌 Important Python Functions Used

```python
data.head()
data.tail()
data.info()
data.describe()
data.columns
data.count()
data.shape
data.size
data.isnull()
data.isnull().sum()
data.sum()
data.min()
data.max()
```

### 📊 Pandas Operations

```python
data.groupby()
data.value_counts()
data.sort_values()
data.drop_duplicates()
data.fillna()
data.dropna()
```

### 📈 Visualization

```python
import matplotlib.pyplot as plt

plt.hist()
plt.bar()
plt.plot()
plt.scatter()
plt.show()
```

---

# 🧠 Key Learning Outcomes

Through this project, I learned how to:

✅ Load a real-world dataset
✅ Understand dataset structure
✅ Inspect data types
✅ Detect missing and unknown values
✅ Clean data
✅ Work with categorical data
✅ Analyze numerical data
✅ Calculate descriptive statistics
✅ Group and filter data
✅ Create visualizations
✅ Identify patterns and relationships
✅ Present analytical findings

---

# 📂 Project Structure

```text
📁 EDA-Adult-Income-Analysis
│
├── 📄 adult.csv
│
├── 📓 EDA_Adult_Income.ipynb
│
├── 📁 images
│   ├── 📊 income_distribution.png
│   ├── 🎓 education_distribution.png
│   ├── 👤 age_distribution.png
│   └── 💼 occupation_distribution.png
│
└── 📄 README.md
```

---

# ☁️ Google Colab

The complete analysis was performed in Google Colab.

### 🔗 Open My EDA Project

👉 [**Open Google Colab Notebook**](https://colab.research.google.com/drive/1cr6Tt0n513OmvwLxV0ykY83hwgg3ZFZk?usp=sharing)

---

# ▶️ How to Run the Project

### ☁️ Google Colab

1. Open the Google Colab notebook.
2. Upload `adult.csv`.
3. Run the notebook cells.
4. Review the data cleaning process.
5. Explore the statistical analysis.
6. View the generated visualizations.

### 💻 Local Environment

Install the required libraries:

```bash
pip install pandas numpy matplotlib
```

Then open:

```text
EDA_Adult_Income.ipynb
```

and run the notebook.

---

# 📊 Project Summary

```text
📂 Dataset
    ↓
🔍 Data Understanding
    ↓
🧹 Data Cleaning
    ↓
📊 Statistical Analysis
    ↓
📈 Visualization
    ↓
🔎 Pattern Identification
    ↓
💡 Insights
```

---

# 🏁 Conclusion

This project provided practical experience in performing **Exploratory Data Analysis using Python**.

I worked with a real-world dataset a
