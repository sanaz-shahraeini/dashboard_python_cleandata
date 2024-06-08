# 📊 Sales Dashboard

This project is a Streamlit-based interactive dashboard for visualizing sales data. It allows users to upload a sales data file, perform exploratory data analysis (EDA), and visualize key metrics and trends using Plotly and DuckDB.

## ✨ Features

- **📂 Data Upload:** Upload an Excel file containing sales data.
- **🔍 Exploratory Data Analysis (EDA):** Visualize relationships between different features and sales figures.
- **📈 Visualization:** Plot various sales metrics and trends using interactive Plotly charts.
- **💾 Data Caching:** Efficiently load and cache data to optimize performance.

## 📋 Requirements

- Python 3.7+
- Streamlit
- Pandas
- Plotly
- DuckDB

## 🚀 Installation

1. **Clone the repository:**

    ```sh
    git clone https://github.com/sanaz-shahraeini/dashboard_python_cleandata
    cd sales-dashboard
    ```

2. **Create a virtual environment:**

    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required packages:**

    ```sh
    pip install -r requirements.txt
    ```

4. **Run the Streamlit app:**

    ```sh
    streamlit run main.py
    ```

## 📚 Usage

1. **Upload a File:** Use the file uploader in the Streamlit app sidebar to upload your sales data Excel file.
2. **Explore the Data:** View the raw data and various charts to understand sales trends and key metrics.
3. **Visualize Metrics:** The app will generate several visualizations, including bar charts, line charts, and gauges, to help you analyze the sales data.

## 📝 Example Data Format

The Excel file should have the following columns:

- `Scenario`
- `business_unit`
- `Account`
- `Year`
- Monthly sales columns (e.g., `Jan`, `Feb`, `Mar`, etc.)

## 📷 Screenshots

### Dashboard Overview

![Dashboard Overview](./images/dashboard_overview.png)

### Sales for Year 2023

![Sales for Year 2023](./images/sales_2023.png)

### Monthly Budget vs Forecast 2023

![Monthly Budget vs Forecast 2023](./images/monthly_budget_vs_forecast_2023.png)
