# 📊 COVID-19 Data Analysis Using PySpark

## 🧾 Project Overview

This mini project performs data analysis on the global COVID-19 dataset using **PySpark**. The goal is to process large-scale data, extract meaningful insights, and identify trends such as total cases, total deaths, and the most affected countries.

The dataset used is from **Our World in Data (OWID)**.

---

## 🎯 Objectives

* Load and explore COVID-19 dataset
* Clean and preprocess data
* Filter country-specific records
* Calculate total cases and total deaths
*Identify countries with highest COVID-19 cases
* Generate insights from real-world data
---

## 🛠️ Tools & Technologies

* Python 🐍
* PySpark 🔥
* pandas 🐼 (for optional data cleaning)
* Visual Studio Code 💻
* Git & GitHub 🌐
---
  ## 📂 Dataset
  
Source:
  
Our World in Data (OWID) COVID-19

DatasetFeatures include:
* total_cases
* total_deaths
* new_cases
* new_deaths
* location
* date
  
 ---
 
  ## ⚙️ Project Workflow
  
  ### 1. Data Loading
  
  Load the dataset using PySpark DataFrame API.
  
  ### 2. Data Cleaning
  
  * Handle missing values
  * Select required columns
  * Remove irrelevant data
    
  ### 3. Data Analysis
  
  * Filter country-wise data
  * Calculate total cases and deaths
  * Group and aggregate data
    
  ### 4. Ranking Countries
  Sort countries based on highest number of COVID-19 cases.
  
  ---
  
  ## 📊 Sample Output
  
  ### 🏆 Top Countries by Total Cases
  
  | Rank | Country       | Total Cases | Total Deaths |
  | ---- | ------------- | ----------- | ------------ |
  | 1    | United States | 103M+       | 1.1M+        |
  | 2    | India         | 45M+        | 533K+        |
  | 3    | Brazil        | 38M+        | 708K+        |
  |   4  | France        | 40M+        | 167K+        | 
  | 5    | Germany       | 38M+        | 174K+        |
  
  ---
  
  ## 📌 Key Insights
  
  * The United States had the highest number of COVID-19 cases globally.
  * India and Brazil were among the most affected countries.
  * Many countries showed missing values due to inconsistent reporting.
  * PySpark efficiently handled large-scale dataset processing.
  * Data aggregation helps in understanding global trends.
    
   ---
  
## 🚀 How to Run the Project

### 1. Install dependencies

```bash
pip install pyspark pandas
```

### 2. Run the script

```bash
python covid_analysis.py
```

OR open in Jupyter Notebook:

```bash
big_data.ipynb
```
---

## 📁 Project Structure

```project/
│
├── big_data.ipynb
├── covid_analysis.py
├── owid-covid-data.csv
└── README.md
```

---

## 👨‍💻 Members

**khadija 2023-ag-9563**
**hakim haq 2023-ag-9543**

---
## 📜 License

This project is for educational purposes only.
