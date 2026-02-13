# European Soccer Match Prediction & Analytics Dashboard

This project focuses on predicting football match outcomes (Home Win, Draw, Away Win) using the European_Soccer_Dataset and presenting insights through an interactive Power BI dashboard.

🛠️ Tools Used: Power BI(Power Query, DAX)
📁 Dataset: European_Soccer_Dataset (25,000+ matches, 10,000+ players, 11 European countries)

---

## 🧠 Project Goal

To build a data-driven match outcome prediction system and visualize team performance trends using a professional Power BI dashboard.
The objective is to:

- Predict match results using betting probabilities (Bet365)
- Compare predicted outcomes vs real results
- Evaluate prediction accuracy through a confusion matrix
- Provide interactive filtering by season, league, and team
---

## 📈 Power BI Dashboard – Mutual Fund Insights

# Data Cleaning

- Removed unnecessary columns
- Handled missing values
- Standardized match statistics

# Feature Engineering

Created team-level and match-level metrics such as:

- Average home goals
- Average away goals
- Historical win ratios

**interactive dashboard** in Power BI.  
🔗 [Power BI Dashboard File (.pbix)](https://github.com/lvalencia232/European_Soccer_Dashboard-PowerBI/blob/main/Dashboard_European_Soccer.pbix)  

### 📌 Key Features

#### 📅 Dynamic Filters
- Season filter
- Team name filter
- League filter
- Multi-season comparison

#### 📊 Key Visuals
⚽ Team Performance Table

Displays:
- Team Name
- Average Home Goals
- Average Away Goals
- Team Speed
- Total Shots
- Provides quick performance comparison across leagues.

#### 📊 Real Results by Team (Stacked Bar Chart)
Breakdown of:

🟢 Home Wins
🟣 Draws 
🔴 Away Wins

Allows analysis of team tendencies and home advantage patterns.

#### 🎯 Betting-Based Result Probabilities (Donut Charts)
Three circular KPI visuals showing:

- Draw Percentage
- Home Win Percentage
- Away Win Percentage

Based specifically on Bet365 betting odds.

#### 📉 Confusion Matrix
Compares:

- Predicted results (based on betting odds)
- Actual match outcomes

Helps evaluate:

- Prediction accuracy
- Model bias (e.g., over-predicting home wins)
- Difficulty in predicting draws

---

## 🔍 Mutual Fund Investment Insights

The European_Soccer_Dataset includes:

- 25,000+ matches (2008–2016)
- 10,000+ players
- 11 European countries
- Betting odds from multiple bookmakers
- Player attributes from FIFA (updated over time)
- Team tactical attributes
- Match-level statistics (goals, shots, possession when available)

Key tables used:

- Match
- Team
- League
- Country
- Betting columns (B365H, B365D, B365A)

The dataset uses relational keys such as match_api_id, team_api_id, and player_api_id to link tables.

---

## 🖼️ Dashboard Preview

![European Soccer Dashboard Preview](https://github.com/lvalencia232/European_Soccer_Dashboard-PowerBI/blob/main/Dashboard.png)


---

### 🧠 Final Conclusion – See the Power of Investment

This project demonstrates how large-scale sports data can be transformed into predictive insights and business intelligence tools.

By combining:

- Data preprocessing
- Evaluation via confusion matrix
- Power BI for interactive visualization

---
- Power BI for interactive visualization

---
