#  Medical Data Visualizer

This project is part of the **freeCodeCamp Data Analysis with Python Certification**. The goal is to clean and analyze a medical dataset and create informative visualizations to understand the relationship between lifestyle choices and health risks.

---

##  Project Objectives

- Normalize data for better analysis  
- Create a categorical plot to show the distribution of variables  
- Generate a heatmap to analyze correlation between medical features  
- Apply data cleaning and transformation techniques

---

##  Dataset

The dataset contains patient medical examination results such as:

- Age, Gender, Height, Weight  
- Blood pressure, Cholesterol, Glucose  
- Lifestyle factors like smoking, alcohol intake, activity  
- Cardiovascular disease status

---
##  Tools & Libraries Used

- Python  
- pandas  
- seaborn  
- matplotlib  
- numpy  

---

##  Tasks Performed

- Converted height and weight to BMI  
- Added an 'overweight' column based on BMI  
- Normalized cholesterol and glucose values  
- Created a **categorical plot** showing counts for each health indicator  
- Created a **correlation heatmap** with a mask for upper triangle  

---

##  Visualizations

1. **Categorical Plot** – Distribution of health indicators per cardiovascular disease status  
2. **Heatmap** – Correlation matrix of all medical variables (cleaned data only)

---

##  Files

- `medical_data_visualizer.py`: Main script with all functions  
- `medical_examination.csv`: Input dataset  
- `catplot.png`: Output of categorical plot  
- `heatmap.png`: Output of heatmap  

---

##  How to Run

```bash
# Clone the repo
git clone https://github.com/Saloni1999-star/medical-data-visualizer.git

# Navigate to the folder
cd medical-data-visualizer

# Run the script
python medical_data_visualizer.py
