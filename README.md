# 📊 Exploratory Data Analysis – Adult Income Dataset

### 🔎 Data Analysis | 🐍 Python | 📈 Visualization | 🧹 Data Cleaning | 🤖 Automated EDA

---

## 🌟 Project Overview

Welcome to my **Exploratory Data Analysis (EDA)** project.

In this project, I performed **data cleaning, data exploration, statistical analysis, automated EDA, and data visualization** using the **Adult Income Dataset**.

The main objective of this project is to understand the dataset, identify patterns and relationships between different variables, and explore factors associated with different income categories.

> 💡 **Project Focus:** Understanding demographic, educational, employment, and income-related patterns through data analysis.

---

## 🚀 Project Highlights

| Area             | Details                                    |
| ---------------- | ------------------------------------------ |
| 📂 Dataset       | Adult Income Dataset                       |
| 📊 Records       | 32,561                                     |
| 📋 Columns       | 15                                         |
| 🎯 Target        | Income                                     |
| 🧹 Data Cleaning | Missing / unknown values                   |
| 📈 Visualization | Charts and graphs                          |
| 🤖 Automated EDA | D-Tale, YData Profiling, AutoViz, Sweetviz |
| 🐍 Language      | Python                                     |
| ☁️ Platform      | Google Colab                               |

---

# 🛠️ Technologies & Tools

### 🐍 Programming & Data Analysis

* 🐍 **Python**
* 🐼 **Pandas**
* 🔢 **NumPy**

### 📊 Visualization

* 📊 **Matplotlib**

### 🤖 Automated EDA

* 📊 **D-Tale**
* 📋 **YData Profiling**
* 📈 **AutoViz**
* 📊 **Sweetviz**

### ☁️ Development Platform

* ☁️ **Google Colab**
* 🐙 **GitHub**

---

# 📁 Dataset Information

The dataset contains information about individuals, including:

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

The target variable is:

```text
Income
```

The income categories are:

```text
<=50K
>50K
```

---

# 🔄 EDA Workflow

```text
📂 Dataset
     ↓
🔍 Data Understanding
     ↓
🧹 Data Cleaning
     ↓
📊 Statistical Analysis
     ↓
🤖 Automatic EDA
     ↓
📈 Data Visualization
     ↓
🔎 Pattern Identification
     ↓
💡 Insights
```

---

# 🤖 Automatic EDA Tools

The project uses automated **Exploratory Data Analysis (EDA)** tools to efficiently inspect datasets, identify data-quality issues, analyze statistical patterns, and generate visual insights.

| Tool                | Primary Purpose                    | Key Capabilities                                                                                         |
| ------------------- | ---------------------------------- | -------------------------------------------------------------------------------------------------------- |
| **D-Tale**          | Interactive Data Exploration       | Data inspection, descriptive statistics, filtering, visualizations, and missing-value analysis           |
| **YData Profiling** | Automated Data Profiling           | Dataset overview, statistical summaries, missing-value analysis, distributions, and correlation analysis |
| **AutoViz**         | Automated Visualization            | Automatic generation of relevant charts and graphical representations                                    |
| **Sweetviz**        | Automated EDA & Dataset Comparison | Visual data profiling, distributions, correlations, feature analysis, and dataset comparison             |

### 🎯 Objective

These tools help streamline the EDA workflow by providing automated statistical analysis and visual exploration.

They can help reduce repetitive manual operations and make it easier to identify:

* 🔎 Data-quality issues
* 📊 Statistical patterns
* ❓ Missing or unknown values
* 🔗 Relationships between variables
* 📈 Data distributions
* 💡 Potential insights

### 📌 Automated EDA Workflow

```text
                 🤖 AUTOMATED EDA
                        │
        ┌───────────────┼───────────────┐
        │               │               │
     📊 D-Tale     📋 YData Profiling  📈 AutoViz
                        │
                    📊 Sweetviz
```

---

# 🔍 Exploratory Data Analysis

## 1️⃣ Understanding the Dataset

Pandas functions were used to understand the structure, dimensions, data types, and statistical characteristics of the dataset.

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

### 📌 Functions Used

| Function     | Purpose                                  |
| ------------ | ---------------------------------------- |
| `head()`     | View the first records                   |
| `tail()`     | View the last records                    |
| `info()`     | Check data types and dataset information |
| `describe()` | Generate statistical summaries           |
| `columns`    | Display column names                     |
| `shape`      | Identify rows and columns                |
| `size`       | Find the total number of elements        |
| `count()`    | Count non-null values                    |

---

# 2️⃣ 🧹 Data Cleaning

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

Visualization was used to make patterns and relationships within the dataset easier to understand.

### 📈 Visualizations Explored

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

# 🖼️ Visualization Gallery

> 📌 Save your generated chart images inside the `images` folder of this GitHub repository.

### 💵 Income Distribution

![Income Distribution](images/income_distribution.png)

### 🎓 Education Distribution

![Education Distribution](images/education_distribution.png)

### 👤 Age Distribution

![Age Distribution](images/age_distribution.png)

### 💼 Occupation Distribution

![Occupation Distribution](images/occupation_distribution.png)

### 🎓 Education vs Income

![Education vs Income](images/education_vs_income.png)

### 👤 Age vs Income

![Age vs Income](images/age_vs_income.png)

---

# 🔎 Analysis Questions

During the EDA process, I explored questions such as:

## 👤 Demographic Analysis

* What is the age distribution?
* What is the gender distribution?
* What are the common marital statuses?
* Which countries are represented in the dataset?

## 🎓 Education Analysis

* Which education levels are most common?
* How does education relate to income?
* How does `EducationNum` vary across income groups?

## 💼 Employment Analysis

* Which workclasses are most common?
* Which occupations occur most frequently?
* How does occupation relate to income?

## 💰 Income Analysis

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
data.duplicated()
data.duplicated().sum()
```

---

# 📊 Pandas Operations

```python
data.groupby()
data.value_counts()
data.sort_values()
data.drop_duplicates()
data.fillna()
data.dropna()
```

---

# 📈 Visualization

```python
import matplotlib.pyplot as plt

plt.hist()
plt.bar()
plt.plot()
plt.scatter()
plt.show()
```

---

# 🤖 Automatic EDA Installation

The following packages can be installed to perform automated EDA:

```bash
pip install dtale
pip install ydata-profiling
pip install autoviz
pip install sweetviz
```

### 📦 Complete Installation

```bash
pip install pandas numpy matplotlib dtale ydata-profiling autoviz sweetviz
```

---

# 🧠 Key Learning Outcomes

Through this project, I gained practical experience in:

* ✅ Exploratory Data Analysis
* ✅ Data cleaning
* ✅ Data preprocessing
* ✅ Working with categorical data
* ✅ Analyzing numerical data
* ✅ Descriptive statistics
* ✅ Grouping and filtering data
* ✅ Detecting missing and unknown values
* ✅ Detecting duplicate records
* ✅ Creating data visualizations
* ✅ Identifying patterns and relationships
* ✅ Using automated EDA tools
* ✅ Presenting analytical findings

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
│   ├── 💼 occupation_distribution.png
│   ├── 🎓 education_vs_income.png
│   └── 👤 age_vs_income.png
│
└── 📄 README.md
```

---

# ☁️ Google Colab

The complete analysis was performed using **Google Colab**.

### 🔗 Open My EDA Project

👉 [**Open Google Colab Notebook**](https://colab.research.google.com/drive/14SQ0IAtrA5PVi_k6L0eCNeqTNS4tiMUF?usp=sharing)

---

# ▶️ How to Run the Project

## ☁️ Google Colab

1. Open the Google Colab notebook.
2. Upload `adult.csv`.
3. Run the notebook cells.
4. Review the data-cleaning process.
5. Explore the statistical analysis.
6. View the generated visualizations.
7. Explore the automated EDA tools.

## 💻 Local Environment

### Step 1️⃣ Clone the repository

```bash
git clone https://github.com/neerukondaramalakshmi2005-dotcom/EDA---PROJECT.git
```

### Step 2️⃣ Open the project folder

```bash
cd EDA---PROJECT
```

### Step 3️⃣ Install the required libraries

```bash
pip install pandas numpy matplotlib
pip install dtale ydata-profiling autoviz sweetviz
```

### Step 4️⃣ Open the notebook

```text
EDA_Adult_Income.ipynb
```

### Step 5️⃣ Run the notebook

Run the cells sequentially to perform the complete EDA process.

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
🤖 Automatic EDA
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

I worked with the **Adult Income Dataset** to understand data structure, perform data cleaning, analyze statistical information, explore relationships between variables, and create visualizations.

I also explored **automated EDA tools** to support data profiling, visualization, and dataset exploration.

The project strengthened my understanding of:

* 🐍 Python
* 🐼 Pandas
* 🔢 NumPy
* 📊 Matplotlib
* 🧹 Data Cleaning
* 📈 Data Visualization
* 🤖 Automated EDA
* 📊 Statistical Analysis

---

# 👩‍💻 Author

### **Rama Lakshmi Neerukonda**

🎓 **B.Sc. Computer Science**

🔎 **Aspiring IT / Data Analytics Professional**

---

# ⭐ Project

If you find this project useful, feel free to explore the repository and notebook.

**Thank you for visiting my project! 🙏**

⭐ **Don't forget to star the repository if you find it useful.**

