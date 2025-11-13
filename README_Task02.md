# Task-02: Titanic Dataset — Data Cleaning & Exploratory Data Analysis (EDA)

This project performs **data cleaning** and **exploratory data analysis (EDA)** on the classic **Titanic dataset**, as part of Prodigy InfoTech Task-02.

Dataset used:  
🔗 https://github.com/Prodigy-InfoTech/data-science-datasets/tree/main/Task%202

---

## 📌 Project Objectives

- Clean the Titanic dataset  
- Handle missing values & duplicates  
- Convert data types  
- Explore relationships between variables  
- Visualize patterns and trends  
- Generate insights from graphs  

---

## 📥 Dataset Description

The Titanic dataset contains the following important columns:

- **Survived** – 0 = No, 1 = Yes  
- **Pclass** – Passenger class (1/2/3)  
- **Sex** – Male/Female  
- **Age** – Age of the passenger  
- **Fare** – Ticket price  
- **Embarked** – Port of boarding  
- **SibSp** – Number of siblings/spouses aboard  
- **Parch** – Number of parents/children aboard  

---

## 🧹 Data Cleaning Steps

✔ Removed duplicate rows  
✔ Filled missing **Age** values using median  
✔ Filled missing **Embarked** values using mode  
✔ Filled missing **Fare** with median  
✔ Converted data types (Survived → int, Pclass → category)  
✔ Verified dataset quality after cleaning  

---

## 📊 Exploratory Data Analysis (EDA)

The notebook generates the following visualizations:

### 🔹 1. Survival Count  
- Bar chart showing number of survivors vs non-survivors

### 🔹 2. Survival by Gender  
- Female passengers had a higher survival rate

### 🔹 3. Age Distribution  
- Histogram of ages to show age spread

### 🔹 4. Passenger Class Distribution  
- Count of passengers in each class (1/2/3)

### 🔹 5. Survival by Passenger Class  
- Survival rate increases with class (1st class survived more)

### 🔹 6. Age vs Survival (Boxplot)  
- Younger passengers had higher chance of survival

### 🔹 7. Correlation Heatmap  
- Shows relationships between numeric features (Fare, Age, Survived, etc.)

### 🔹 8. Fare Distribution  
- Histogram with KDE for price variations

---

## 📁 Files Generated

The notebook produces the following files:

- `survival_count.png`  
- `survival_by_gender.png`  
- `age_distribution.png`  
- `pclass_distribution.png`  
- `survival_by_pclass.png`  
- `age_vs_survival_boxplot.png`  
- `correlation_heatmap.png`  
- `fare_distribution.png`  
- `titanic_cleaned.csv`  
- `Task02_Titanic_EDA.ipynb` (main notebook)

---

## 🏁 Key Insights

- Women had significantly higher survival rates.  
- Higher-class passengers (1st class) survived more than lower-class ones.  
- Younger passengers had better survival probability.  
- Fare is positively correlated with survival (higher fare → higher class).  

---

## ▶️ How to Run the Notebook

1. Download the notebook `Task02_Titanic_EDA.ipynb`  
2. Open in **Google Colab** or **Jupyter Notebook**  
3. Run all cells  
4. Plots will be generated and saved automatically  
5. Upload the notebook + images to GitHub  

---

## 👨‍💻 Author

**Qamar Shafiq Rao**  
B.Tech — Data Science  
Prodigy InfoTech Internship Tasks

---
