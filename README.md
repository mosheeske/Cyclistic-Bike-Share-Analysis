# 🚲 Cyclistic Bike-Share Analysis

## 📌 Project Overview

This project analyzes historical bike-share data from Cyclistic (Chicago) to understand the behavioral differences between **casual riders** and **annual members**.

The goal is to generate data-driven insights that help design marketing strategies aimed at converting casual users into annual members.

---

## 🎯 Business Task

The main question addressed in this analysis is:

> **How do annual members and casual riders differ in their usage of Cyclistic bikes?**

---

## 📊 Dataset

- Source: Divvy Bike Share (public dataset)
- Period: Last 12 months
- Records analyzed: ~5.6 million rides
- Data includes:
  - Ride timestamps
  - User type (casual vs member)
  - Bike type
  - Trip duration
  - Geolocation data

---

## 🧹 Data Cleaning & Preparation

The following steps were performed:

- Merged 12 monthly datasets into a single dataframe
- Converted date columns to datetime format
- Created new features:
  - `ride_length` (trip duration)
  - `day_of_week`
- Removed:
  - Negative ride durations
  - Extreme outliers (rides > 2 hours)
  - Duplicate records
- Dropped columns with high missing values (station data)

---

## 📈 Key Findings

### ⏱️ Ride Duration
- Casual riders: longer trips (~16–17 minutes)
- Members: shorter trips (~11–12 minutes)

👉 Casual users tend to use bikes for **recreational purposes**, while members use them for **daily transportation**.

---

### 📅 Usage Patterns
- Members: consistent usage throughout the week
- Casual riders: peak usage on weekends

👉 Indicates:
- Members → commuting behavior  
- Casual → leisure behavior  

---

### 🚲 Bike Preferences
- Electric bikes are the most used by both groups

👉 Suggests a strong preference for **comfort and efficiency**

---

### 📦 Ride Distribution
- Casual users show higher variability in trip duration
- Members have more consistent usage patterns

---

## 💡 Recommendations

### 1. Convert casual users into members
- Offer targeted promotions for weekend users
- Introduce trial memberships

---

### 2. Encourage weekday usage among casual riders
- Discounts for weekday rides
- Work commute incentives

---

### 3. Leverage electric bike popularity
- Highlight convenience in marketing campaigns
- Offer benefits tied to electric bike usage

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📁 Project Structure

├── data/
├── notebooks/
│ └── Proyecto_Bicicletas_Compartidas.ipynb
├── README.md


---

## 🚀 How to Run

1. Clone this repository
2. Install dependencies:
  pip install pandas numpy matplotlib seaborn
3. Open the notebook:
  jupyter notebook


---

## 👨‍💻 Author

**Moises Eskenasy**  
Data Analyst | Python | SQL | Power BI  

🔗 LinkedIn: https://www.linkedin.com/in/moises-eskenasy-sierra-b39190289/  
🔗 GitHub: https://github.com/mosheeske
