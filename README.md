# Pusula Talent Academy Data Science Intern Case Study

* **Name Surname:** Murathan Elcuman
* **Mail Address**: mrthelcuman@gmail.com


## 1. Project Overview

This project involves the exploratory data analysis (EDA) and preprocessing of a patient dataset provided in a file. The primary goal is to clean, understand, and transform the data into a suitable format for machine learning tasks, such as predicting treatment duration.

The analysis covers several key stages:
* **Data Sanity Check:** Initial inspection for data quality, duplicates, and missing values.
* **Exploratory Data Analysis (EDA):** Understanding data distributions and relationships between variables using statistical summaries and visualizations.
* **Data Cleaning & Preprocessing:** Handling missing values and converting data types.
* **Feature Engineering:** Encoding categorical variables (both single-label and multi-label) and scaling numerical features to prepare the data for modeling.

---

## 2. Dataset

The dataset contains 2235 records of patient information with 13 distinct features:

* **HastaNo:** Patient ID
* **Yas:** Age
* **Cinsiyet:** Gender
* **KanGrubu:** Blood Type
* **Uyruk:** Nationality
* **KronikHastalik:** Chronic Disease(s)
* **Bolum:** Department
* **Alerji:** Allergy(ies)
* **Tanilar:** Diagnoses
* **TedaviAdi:** Treatment Name
* **TedaviSuresi:** Treatment Duration (Target Variable)
* **UygulamaYerleri:** Application Areas for Treatment
* **UygulamaSuresi:** Application Duration

---

## 3. Tools and Libraries

The analysis was performed using Python with the following key libraries:
* **Pandas:** For data manipulation and analysis.
* **NumPy:** For numerical operations.
* **Matplotlib & Seaborn:** For data visualization.
* **Scikit-learn:** For data preprocessing and feature engineering (encoding and scaling).

---

## 4. How to Run

1.  Ensure you have a Python environment with the libraries listed above installed.
2.  Place the dataset into the related part of the code.
3.  Run the `Notebook.ipynb` file in a Jupyter environment to replicate the analysis and preprocessing steps.
