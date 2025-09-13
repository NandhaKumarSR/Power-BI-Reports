# 🚗 Tesla Model Insights Dashboard

This project presents a Power BI dashboard that visualizes Tesla's global sales trends, model specifications, and predictive unit sales. It combines curated datasets, machine learning forecasts, and interactive visuals to deliver a compelling overview of Tesla’s electric vehicle lineup.

🔗 **Live Report**: [View Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiMjc2ZDcxNDYtYTgxMC00MmZmLTgwOTktMjgyMDNjZmVlMzQ1IiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9)

<img width="1549" height="845" alt="image" src="https://github.com/user-attachments/assets/24524009-ccd7-4c54-9413-98c3dd5eda20" />

---

## 📊 Data Sources

- **Sales Data**: [Visual Capitalist – Tesla Global Sales (2016–2023)](https://www.visualcapitalist.com/charted-teslas-global-sales-by-model-and-year-2016-2023/)
- **Vehicle Specs & Ratings**: [U.S. News – Tesla Reviews](https://cars.usnews.com/cars-trucks/tesla)
- **Predicted Sales**: Generated via linear regression in a Jupyter notebook and appended to the source file.

---

## 🔍 Features

- **Model Tabs**: Explore Model S, 3, X, and Y with interactive navigation.
- **Performance Metrics**: Acceleration, range, top speed, interior capacity, and handling—visually scored.
- **Sales Breakdown**:
  - Actual units sold (2012 Q3 – 2023 Q3)
  - Predicted unit sales with 75% confidence interval
- **Pricing Snapshot**: MSRP ranges and starting prices for each model.
- **Forecasting Integration**: Linear regression predictions embedded directly into the Power BI data model.

---

## 🧠 Predictive Modeling

The Jupyter notebook uses **linear regression** to forecast future unit sales based on historical quarterly data. Key steps include:

1. **Data Preparation**: Clean and structure historical sales data
2. **Model Training**: Fit a linear regression model to identify sales trends
3. **Prediction**: Generate future sales estimates with confidence intervals
4. **Export**: Append predictions to the source CSV for Power BI consumption

---

## 🛠️ Tech Stack

- **Power BI**: Dashboard design and visualization
- **Python / Jupyter Notebook**: Predictive modeling and data transformation
- **Pandas / Scikit-learn / NumPy**: Data manipulation and regression analysis

---

## 📁 Folder Structure

```
📁 tesla_spec_vs_sales_dashboard/
├── data/
│   └── tesla_sales_with_predictions.csv
├── notebooks/
│   └── tesla_sales_forecast_linear_regression.ipynb
├── assets/
│   └── dashboard_screenshot_home.png
│   └── dashboard_screenshot_models_overview.png
├── reports/
│   └── tesla_pbip_project_files
│   └── tesla_spec_vs_sales_dashboard.pbip
├── README.md

```

---

## 🚀 How to Use

1. Run the Jupyter notebook to generate linear regression predictions.
2. Export the updated .xlsx with predicted sales.
3. Clone the repo and open tesla_spec_vs_sales_dashboard.pbip in Power BI desktop
4. Save the file in .pbix format in a local recpository.
5. Repoint the source to .xlsx file location.
6. Share or embed the dashboard via Power BI service.

---

## 📬 Contact

For feedback, collaboration, or questions, feel free to reach out via GitHub or [LinkedIn](https://www.linkedin.com/in/nandha-kumar-sr-94063217b/).
