# 🛒 Superstore Predictive Analytics & Dashboard

## 📌 Project Overview
An end-to-end data analytics solution for a retail superstore. This project integrates **Python Machine Learning** for sales forecasting and **Power BI** for interactive dashboards, enhanced with **GPT-4 generated insights** to identify key business risks and opportunities.

## 🎯 Business Goal
To predict future sales trends and identify specific profit-draining areas (e.g., specific states or discount strategies) to improve the company's net margin.

## 🛠️ Tech Stack
* **Python:** Pandas, NumPy, Scikit-Learn (Random Forest), Prophet (Time Series).
* **Visualization:** Power BI (Interactive Dashboard), Matplotlib, Seaborn.
* **AI Integration:** OpenAI API (GPT) for automated executive summaries.

## 📊 Key Insights
1.  **The "Texas Problem":** Texas is the worst-performing state, generating significant sales but a net loss of **-$25,729** due to excessive discounting.
2.  **Sales Forecast:** The Prophet model predicts stable daily sales averaging **$917** for the next 30 days.
3.  **Top Category:** "Technology" is the highest revenue driver and should be the focus of marketing efforts.

## 📷 Dashboard Snapshots
### Main Dashboard (Sales & Forecasting)
![Main Dashboard](dashboard/dashboard_main.png)

### AI Insights Page
![AI Insights](dashboard/dashboard_ai.png)

## 🧠 Machine Learning Results
* **Sales Prediction (Regression):** Random Forest Regressor outperformed Linear Regression with a lower RMSE ($677).
* **Time Series Forecasting:** Facebook Prophet successfully captured weekly seasonality and produced a 365-day forward-looking trend.

## 🚀 How to Run
1.  Clone the repository.
2.  Install dependencies: `pip install pandas scikit-learn prophet openai`.
3.  Run the notebooks in the `notebooks/` folder.
4.  Open `dashboard/Superstore.pbix` in Power BI Desktop.