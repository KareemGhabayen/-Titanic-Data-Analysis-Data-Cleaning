🚢 Titanic Data Analysis & Data Cleaning
Exploratory Data Analysis (EDA) and Preprocessing for AI Modeling

📌 Project Overview
This project focuses on the Titanic dataset, a classic benchmark in data science. The goal was to perform a deep dive into the data to understand passenger demographics and survival factors, while executing a rigorous data cleaning process to prepare the dataset for future Machine Learning algorithms.  

📋 Project Requirements & Tasks
To ensure high-quality data for modeling, the following technical tasks were successfully implemented:

Data Exploration: Initial loading and structural analysis of the dataset using Pandas.  

Missing Value Management: * Detected null values in key columns like age and embarked.  

Imputed missing age values using the Median to maintain statistical consistency.

Dropped the deck column due to a high percentage of missing information.

Duplicate Handling: Identified and removed 116 duplicate records to prevent data leakage and bias.  

Outlier Detection: Used the IQR (Interquartile Range) method to detect and handle extreme values in the fare column, ensuring the model isn't skewed by "noisy" data.  

Gender-Based Analysis: Investigated and visualized survival rates, revealing significant insights into the "Women and Children first" protocol.  

Demographic Visualization: Created age histograms to analyze the distribution of passengers.  


🛠️ Tech Stack
Python 3.x

Libraries: Pandas (Data Manipulation), NumPy (Numerical Ops), Seaborn & Matplotlib (Visualization).  
+1

📊 Key Results Summary

Survival Gap: Females had a survival probability of approximately 74%, while males were at 21%.  

Data Integrity: The final dataset is cleaned, free of duplicates, and has zero missing values in critical features.

<img width="1112" height="663" alt="Skjermbilde 2026-05-11 224822" src="https://github.com/user-attachments/assets/2800f221-9293-48f5-b2f9-ae2258d66146" />


Efficiency: Automated the cleaning process, making it reusable for any similar CSV data structure.


📂 Repository Contents

Titanic_EDA_Cleaning.ipynb: The primary Jupyter Notebook containing the full code and visual results.  

titanic.csv: The raw dataset used for this analysis.  


Developed as part of the AI & Computer Science Curriculum at Al-Aqsa University.
