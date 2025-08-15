# 👶 AICP Internship – Week 6: US Birth Rate Analysis (EDA)

This repository contains **exploratory data analysis (EDA)** performed on the **US Births Dataset** provided by the Centers for Disease Control (CDC), completed as part of the **Artificial Intelligence Community of Pakistan (AICP)** internship program.

---

## 📝 Overview
The dataset `births.csv` contains information about births in the United States over multiple decades.  
The analysis focuses on trends, patterns, and seasonality in birth rates while removing statistical outliers to ensure meaningful insights.

---

## 📂 Dataset
- **File:** `births.csv`
- **Key Attributes:**
  - Year
  - Month
  - Day
  - Gender (Male/Female)
  - Number of births

---

## 🔍 Tasks

### **Q1: Create "Decade" Column**
- Added a new column `Decade` by rounding the year down to the nearest decade (e.g., 1969 → 1960).

### **Q2: Descriptive Statistics**
- Displayed summary statistics for all numeric columns.

### **Q3: Missing Values Check**
- Checked and reported if there are any null values in the dataset.

### **Q4: Birth Trends by Decade**
- Plotted male and female birth counts by decade to analyze trends over time.

### **Q5: Outlier Removal**
- Applied the **5 standard deviations rule** to exclude extreme outliers from the dataset.

### **Q6: Births by Weekday**
- Plotted the average number of births by weekday across several decades.
- Added observations to highlight patterns.

### **Q7: Grouping by Month and Day**
- Grouped the dataset by month and day separately to explore seasonal patterns.

### **Q8: Average Births by Date of the Year**
- Created a time series plot showing the average number of births for each date (month/day) across all years.

---

## 🛠 Tech Stack
- **Language:** Python
- **Libraries:**
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn

---

## 🚀 How to Run
1. **Clone Repository**
   ```bash
   git clone https://github.com/malik8154/AICP-Internship-Week6-Birth-EDA.git
   cd AICP-Internship-Week6-Birth-EDA

2. Install Dependencies

pip install pandas numpy matplotlib seaborn

3. Run Script

python week6_birth_eda.py
