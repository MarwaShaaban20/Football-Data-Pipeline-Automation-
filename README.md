

# ⚽ European Football Matches Analysis & Prediction (2023–2026)

##  Project Overview

This project analyzes **European football matches data** from **2023 to 2026**, combining historical match results with real-time live data to generate insights and predict future match outcomes.

The project integrates **API-based data extraction**, **workflow automation**, **data visualization**, and **machine learning** to deliver an end-to-end analytics solution.

---

##  Data Sources

### 1️⃣ Historical Matches (2023–2025)

* Source: **Football-Data.org API**
* API Provider: [https://www.football-data.org/](https://www.football-data.org/)
* Data includes:

  * Match results
  * Teams
  * Goals
  * Standings
  * League performance

### 2️⃣ Live Matches (2026)

* Live match data is collected using **n8n**
* Automated workflows fetch real-time match data
* Data is stored in **Google Sheets**
* Used later for live monitoring and prediction updates

---

## 🛠 Tools & Technologies

* **Python**

  * Data extraction & cleaning
  * Feature engineering
  * Machine learning modeling
* **Football-Data.org API**
* **n8n**

  * Live match automation (2026)
* **Google Sheets**

  * Real-time data storage
* **Power BI**

  * Interactive dashboards & visual analytics
* **Machine Learning**

  * Match outcome prediction (XGBoost)

---

## 🔄 Project Workflow

1. **API Data Extraction**

   * Fetch historical matches (2023–2025) using Python
2. **Data Cleaning & Feature Engineering**

   * Goals difference
   * Team momentum
   * League position gap
3. **Live Data Automation (2026)**

   * n8n workflows pull live match data
   * Data stored automatically in Google Sheets
4. **Machine Learning Prediction**

   * XGBoost model predicts match outcomes
   * Generates a **Win Confidence Score**
5. **Visualization**

   * Interactive Power BI dashboard for insights & analysis

---

## 🤖 Machine Learning Model

* Algorithm: **XGBoost**
* Objective: Predict match outcomes for 2026
* Key Features:

  * Position Gap
  * Goal Difference Dynamics
  * Team Performance Trends
* Accuracy: **~51%**, outperforming random probability
* Output:

  * Match result prediction
  * Confidence score per match
  * High-risk vs high-certainty matches

---

## 📈 Power BI Interactive Dashboard

🔗 **Live Dashboard:**
👉 [https://app.powerbi.com/view?r=eyJrIjoiOTFhMjIyNzItN2ZjNi00ZDI2LWJjZjMtMzIxMGZhYTk0OWJjIiwidCI6IjJiYjZlNWJjLWMxMDktNDdmYi05NDMzLWMxYzZmNGZhMzNmZiIsImMiOjl9&pageName=02fb49e4b005d490e6c7](https://app.powerbi.com/view?r=eyJrIjoiOTFhMjIyNzItN2ZjNi00ZDI2LWJjZjMtMzIxMGZhYTk0OWJjIiwidCI6IjJiYjZlNWJjLWMxMDktNDdmYi05NDMzLWMxYzZmNGZhMzNmZiIsImMiOjl9&pageName=02fb49e4b005d490e6c7)

Dashboard Highlights:

* League performance comparison
* Home vs Away goal analysis
* Team dominance across seasons
* Match volume and trends
* Prediction insights

<img width="1493" height="811" alt="Screenshot (415)" src="https://github.com/user-attachments/assets/d6b5a324-d5f2-40d0-bda3-3e9d4845d95e" />

<img width="1499" height="810" alt="Screenshot (421)" src="https://github.com/user-attachments/assets/62ab9a82-e801-4e9a-97ec-95423f3f8b37" />

<img width="1508" height="821" alt="Screenshot (417)" src="https://github.com/user-attachments/assets/80353345-85ac-40d8-99a4-cd69a50273b2" />

---

## 📂 Repository Structure (Suggested)

```
├── data/
│   ├── raw/
│   ├── processed/
│
├── notebooks/
│   ├── data_extraction.ipynb
│   ├── data_cleaning.ipynb
│   ├── feature_engineering.ipynb
│   ├── model_training.ipynb
│
├── n8n/
│   └── live_matches_workflow.json
│
├── powerbi/
│   └── dashboard.pbix
│
├── presentation/
│   └── project_presentation.pdf
│
├── README.md
```

---

## 📎 Presentation

The full project explanation, insights, and results are available in the project presentation file.

---


## ⭐ Future Enhancements

* Improve prediction accuracy with additional features
* Deploy live predictions using a web app
* Add automated alerts for high-risk matches
* Integrate more leagues and seasons


لو حابة:

* أظبطه **أكتر Tech / أكتر Business**
* أو أكتبه **بالإنجليزي أخف مناسب HR**
* أو أضيف **Badges + Screenshots + Demo GIFs**

قولي و أظبطهولك فورًا 🔥⚽
