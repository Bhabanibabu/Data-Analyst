# 🏭 Daikibo Factory Downtime Analysis

This is my **first project as a data analyst**, created using Tableau. The goal was to help Daikibo Industrials identify which of their factories experienced the most machine downtime, and which machines were responsible.

## 📁 Project Files

- `Daikibo_Dashboard.json` – Tableau dashboard saved as a JSON export (shared for viewing or future use)
- `Dashboard_Screenshot.png` – Image of the final dashboard showing downtime insights
- `README.md` – This project overview

## 🧠 Objective

Help the client answer two key questions:

1. **Which factory experienced the most machine breakdowns?**
2. **Which machine types broke down most often at that location?**

## 🛠 Tools Used

- **Tableau** – For data connection, calculated fields, visualizations, and dashboard creation
- **JSON** – Original telemetry data source (processed from machine logs)

## 🔍 Methodology

- Created a calculated field `Unhealthy = 10` (representing 10 minutes of downtime per unhealthy status)
- Built two bar charts:
  - **Down Time per Factory**
  - **Down Time per Device Type**
- Combined charts into a dashboard with **interactive filtering** (selecting a factory filters device types)

## 📊 Insights

- The dashboard clearly shows the **factory with the highest cumulative downtime**
- It also breaks down **which machines** contributed most to downtime at that location

## 🔐 Disclaimer

This dashboard is based on demo or sample data and is shared for **educational and portfolio purposes only**.

---

👋 Thank you for viewing my first project! Feedback and suggestions are welcome.
