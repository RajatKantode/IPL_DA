# 🏏 IPL Analytics Dashboard & Match Winner Prediction

A complete Data Analytics and Machine Learning project built using IPL historical data. This project provides interactive Power BI dashboards for IPL insights and a Machine Learning model for match winner prediction.

---

## 📌 Project Overview

This project analyzes IPL match and ball-by-ball data to uncover insights about:

- Team Performance
- Player Statistics
- Orange Cap Race
- Purple Cap Race
- Venue Analysis
- Toss Impact Analysis
- Match Winner Prediction

The project combines:

- Python for Data Cleaning & EDA
- Power BI for Dashboard Development
- Machine Learning for Match Outcome Prediction

---

## 🛠️ Tech Stack

### Data Processing
- Python
- Pandas
- NumPy

### Visualization
- Power BI
- Matplotlib
- Seaborn

### Machine Learning
- Scikit-Learn
- Random Forest
- Logistic Regression
- XGBoost (Optional)

### Development Environment
- Jupyter Notebook
- VS Code

---

## 📂 Project Structure

```text
IPL_DA/
│
├── deliveries.csv                     # Original ball-by-ball IPL dataset
├── matches.csv                        # Original match dataset
│
├── cleaned_deliveries.csv             # Cleaned deliveries dataset
├── matches_cleaned.csv                # Cleaned matches dataset
│
├── data_clean_deliveries.ipynb        # Data cleaning notebook for deliveries data
├── data_clean_matches.ipynb           # Data cleaning notebook for matches data
│
├── EDA.ipynb                          # Exploratory Data Analysis notebook
├── match_winner_pred.ipynb            # Machine Learning model notebook
│
├── IPL_Dashboard.pbix                 # Power BI Dashboard file
├── IPL_Dashboard.pdf                  # Dashboard PDF export
│
└── README.md
```

---

## 📊 Dashboard Features

### 1️⃣ IPL Overview
- Total Matches
- Total Seasons
- Total Teams
- Total Runs
- Total Wickets

### 2️⃣ Orange Cap Analysis
- Top Run Scorers
- Season-wise Runs
- Player Comparison
- Strike Rate Analysis

### 3️⃣ Purple Cap Analysis
- Top Wicket Takers
- Economy Rate Analysis
- Season-wise Wickets

### 4️⃣ Team Analytics
- Team Win Percentage
- Toss Impact
- Head-to-Head Records

### 5️⃣ Venue Analytics
- Venue-wise Matches
- Average Scores
- Highest Team Totals
- Winning Trends

---

## 🤖 Machine Learning Module

### Match Winner Prediction

### Features Used
- Team 1
- Team 2
- Venue
- Toss Winner
- Toss Decision

### Target Variable
- Match Winner

### Models Tested
- Logistic Regression
- Random Forest Classifier

### Evaluation Metrics
- Accuracy Score
- Confusion Matrix
- Classification Report

---

## 📈 Key Insights

- Identified top-performing teams across seasons.
- Analyzed venue-specific winning trends.
- Evaluated toss impact on match outcomes.
- Determined leading run scorers and wicket takers.
- Built a predictive model for IPL match winners.

---

## 🚀 How to Run

### Clone Repository

```bash
git clone https://github.com/yourusername/IPL-Analytics-Dashboard.git
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Run Notebooks

```bash
jupyter notebook
```

Open:

- data_clean_matches.ipynb
- data_clean_deliveries.ipynb
- EDA.ipynb
- match_winner_pred.ipynb

---

## 📷 Dashboard Preview

Open:

```text
IPL_Dashboard.pbix
```

using Power BI Desktop.

---

## 📊 Dataset

Dataset Source:

https://www.kaggle.com/datasets/patrickb1912/ipl-complete-dataset-20082020

Files Used:

- matches.csv
- deliveries.csv

---

## 🎯 Future Improvements

- Live IPL Data Integration
- Streamlit Web Application
- Win Probability Prediction
- Player Performance Prediction
- Team Recommendation Analytics

---

## 👨‍💻 Author

**Rajat Satish Kantode**

Data Science Student | AI/ML Enthusiast | Data Analytics Enthusiast

### Connect With Me

- LinkedIn: [LinkedIn Profile](https://www.linkedin.com/in/rajat-kantode-14486528b/)
- GitHub: [GitHub Profile](https://github.com/RajatKantode)
- Email: [Email](rajatskantode2@gmail.com)

---

⭐ If you found this project useful, consider giving it a star on GitHub.
