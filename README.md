# Titanic Survival Prediction 🚢 — EDA 📊 & Classification 🤖

This repository contains a comprehensive data analysis and a prediction engine for **Titanic** passenger survival using the famous dataset from Kaggle:
- 📒 A **Jupyter Notebook** for data cleaning, Exploratory Data Analysis (EDA), and feature engineering.
- 🤖 A **Classification Model** that predicts survival based on passenger demographics and ticket class.

> 💡 **Note**: The project focuses on uncovering the stories behind the tragedy through data visualization and narrative insights.

---

## Table of Contents 🧭

- [Project Structure](#project-structure-)
- [Overview](#overview-)
- [Dataset](#dataset-)
- [Notebook](#notebook-)
  - [Steps](#steps-)
  - [Insights](#insights-)
- [Power BI Dashboard](#power-bi-dashboard-)
- [Getting Started](#getting-started-)
  - [Requirements](#requirements-)
  - [Run the Notebook](#run-the-notebook-)
- [Author](#author-)
- [Acknowledgments](#acknowledgments-)
- [License](#license-)

---

## Project Structure 🗂️

```text
Titanic/
├─ Dataset/
│  └─ Titanic-Dataset.csv
├─ Dashboard/
│  └─ titanic.pbix
├─ Images/
└─ notebook.ipynb
```

---

## Overview ✨
The goal of this project is to:
- 🔎 **Analyze Demographics**: Understand the diversity of passengers on board.
- 🧩 **Missing Value Handling**: Implement strategies to impute missing Age and Cabin data.
- 📊 **Data Visualization**: Create intuitive charts to visualize survival rates by gender, class, and age.
- 🧪 **Predict Survival**: Build a machine learning model to predict who survived the disaster.
- 📊 **Dashboard**: Interactive Power BI dashboard for exploring passenger data.

---

## Dataset 📦

Location: `Dataset/Titanic-Dataset.csv`

Key columns used:
- 🎫 **Pclass**: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd).
- 👫 **Sex**: Gender of the passenger.
- 🕰️ **Age**: Age in years.
- 👨‍👩‍👧 **SibSp / Parch**: Number of siblings/spouses or parents/children aboard.
- 💵 **Fare**: Passenger fare.
- 🚪 **Embarked**: Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).
- ☠️ **Survived**: Survival (0 = No, 1 = Yes).

---

## Notebook 📒

File: `notebook.ipynb`

### 1. Data Preprocessing 🛠️
- **Cleaning**: Handling missing `Age` values using median imputation and `Cabin` values by marking them as "Unknown".
- **Feature Engineering**: Creating new features like `FamilySize` and `Title` extracted from names.
- **Encoding**: Converting categorical variables (Sex, Embarked) into numerical formats.

### 2. EDA Insights 📈
- **The Gender Gap**: Survival rates for females were significantly higher than for males.
- **Class Stratification**: 1st Class passengers had the highest survival rate, while 3rd Class suffered the most losses.
- **Age Distribution**: Children had a higher probability of survival, confirming the "Women and Children First" protocol.

---

## Power BI Dashboard 📈

Folder: `Dashboard/`

- `titanic.pbix`: Power BI report

Open the `.pbix` file using **Power BI Desktop**.

What you can do with the dashboard:
- 📌 Filter passengers by Class, Gender, and Survival status.
- 💳 Analyze Fare distribution and survival correlation.
- 🔎 Explore passenger details interactively.

---

## Getting Started 🚀

### Requirements 🧰

To run the notebook, you’ll typically need:
- Python 3.x
- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scikit-learn`

### Run the Notebook ▶️

1. Open `notebook.ipynb` in Jupyter / VS Code.
2. Run cells top-to-bottom.

---

## Author ✍️

- Name: **Mohamed Younis**

---

## Acknowledgments 🙏

- **Internship 🏢**: [Uneeq Interns](https://www.linkedin.com/company/uneeq-interns/)

---

## License 📄

This project is open-source. Feel free to use it for educational purposes.
