# ML Assignment 1

## Overview

This repository contains Assignment 1 for a Machine Learning course. The assignment involves data preprocessing, exploratory data analysis (EDA), and basic model training using Python.

---

## Contents

- **Google Colab Notebook**: Access the full implementation in Google Colab by clicking [here](https://colab.research.google.com/drive/1RAKewTWPT56YooUVixGvHxEndHx2mExJ).
- **Results**: Summary of key findings and outputs generated during the analysis.

---

## Objectives

1. Understand and implement [specific algorithms or methods, e.g., Linear Regression, Convolutional Neural Network, ].
2. Analyze and preprocess the dataset.
3. Evaluate model performance using appropriate metrics.

---

## Dataset

- **Name**: weather_data.csv
- **Description**: Brief description of the dataset (number of rows, columns, type of data, etc.).

---
🔍 Data Loading & Preprocessing

Loading the Data
Before performing any data preprocessing or model training, we begin by loading the dataset and conducting an initial inspection.

Steps:

✅ Load the dataset: Read the weather data from a CSV file using Pandas.
✅ Check data types: Displaying column data types helps us understand the dataset structure.
✅ Inspect the first data point: Print all feature values of the first record to get an overview of the dataset content.
✅ Check dataset dimensions: Print the dataset shape to determine the number of rows and columns.

2️⃣ Install Dependencies
Ensure you have Python and Jupyter Notebook installed. Install required libraries using:

pip install -r requirements.txt
(If there's no requirements.txt, manually install NumPy, Pandas, Matplotlib, Scikit-learn, etc.)

3️⃣ Run the Notebook
Launch Jupyter Notebook and open MLassign1.ipynb:

jupyter notebook

🔍 Data Loading & Preprocessing

Loading the Data
Before performing any data preprocessing or model training, we begin by loading the dataset and conducting an initial inspection.

Steps:

✅ Load the dataset: Read the weather data from a CSV file using Pandas.
✅ Check data types: Displaying column data types helps us understand the dataset structure.
✅ Inspect the first data point: Print all feature values of the first record to get an overview of the dataset content.
✅ Check dataset dimensions: Print the dataset shape to determine the number of rows and columns.

Data Points
Each data point corresponds to a specific hour, e.g., 06-April-2023 from 06:00 - 07:00, recorded as 2023-04-06 06:00:00 (starting time) after preprocessing.

📌 Features: All hourly observations from the previous 5 hours. Example:

For the data point 2023-04-06 06:00:00, the features correspond to data from 01:00 - 06:00 on the same day.
📌 Label: Temperature recorded 5 hours ahead. Example:

For the data point 2023-04-06 06:00:00, the target variable is the temperature at 11:00.

📌 Example Visualization:
(Add a sample plot image here if available)

🤖 Machine Learning Models

Implemented Models:
✅ Linear Regression – Predicts a continuous target variable.
✅ Convolutional Neural Network –  CNNs are well-suited for sequential data as they can capture local patterns and temporal dependencies.
✅ Decision tree regressor –  a non-parametric model that can capture nonlinear relationships in the data.

Performance Metrics Evaluated:
✔️ RMSE (for regression tasks).

🛠 Technologies Used

Python
Jupyter Notebook
NumPy, Pandas, Matplotlib
Scikit-learn

📬 Contact

For any queries, feel free to reach out or raise an issue.


---

### 🚀 Next Steps  
- If you have **graphs or images**, place them inside the `images/` folder and reference them in the **README.md**.  
- If you have a `requirements.txt`, add dependencies to it.  

Let me know if you need further modifications! 🚀







