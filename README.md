Healthcare Data Analysis and Exploration

A comprehensive data analysis workflow in Python for processing, exploring, and visualizing patient admission records, demographics, and billing details.

📌 Project Overview

This repository provides an end-to-end data processing and exploratory data analysis (EDA) pipeline designed for healthcare datasets. It cleans raw patient data, handles missing values, engineers calculated metrics (such as duration of hospital stay), and builds detailed visual distributions across medical conditions, demographics, and billing amounts.

🔑 Key Features

Data Cleaning & Standardization:

Checks dataset dimensions and data types.

Identifies missing values and handles unassigned medical attributes.

Standardizes categorical attributes and string fields.

Feature Engineering:

Parses admission and discharge dates into native datetime structures.

Calculates exact patient stay durations (Length_of_Stay) in days.

Statistical Summary & Aggregation:

Summarizes average billing amounts and age metrics grouped by medical condition.

Generates cross-tabulations across admission types, genders, and diagnoses.

Data Visualizations:

Categorical Distribution: Bar charts showing counts per admission type and gender.

Financial Insights: Distribution plots and violin plots analyzing billing variations across medical conditions.

Time-Series / Stay Analysis: Length of stay variations grouped by hospital department and admission status.

🛠️ Tech Stack & Dependencies

Language: Python 3.8+

Libraries:

pandas – Data manipulation and aggregation

numpy – Numerical calculations

matplotlib – Core plotting and canvas customisation

seaborn – Advanced statistical data visualizations

📁 Repository Structure

├── healthcare_analysis.ipynb   # Main Jupyter/Colab notebook
├── README.md                   # Project documentation
└── data/                       # Dataset directory (optional)
    └── healthcare_dataset.csv


🚀 Getting Started

1. Prerequisites

Ensure you have Python installed. You can install all required dependencies using pip:

pip install pandas numpy matplotlib seaborn jupyter


2. Running the Notebook

Clone this repository:

git clone https://github.com/your-username/healthcare-data-analysis.git
cd healthcare-data-analysis


Launch Jupyter Notebook or Jupyter Lab:

jupyter notebook


Open healthcare_analysis.ipynb and run the cells sequentially.

📊 Sample Outputs & Visualizations

The notebook produces several visual insights including:

Age Distribution by Condition: Box plots comparing age ranges across various diagnoses.

Billing Amount Summary: Violin plots illustrating financial variation per admission type.

Gender vs Medical Condition Breakdown: Grouped bar charts visualizing demographic distributions.

📜 License

This project is available under the MIT License.
