# BlinkIT Sales Forecasting & Interactive Dashboard

## Overview
This project involves analyzing BlinkIT grocery data to forecast sales trends and create an interactive Power BI dashboard for visual insights. The data was cleaned and preprocessed using Python, with linear regression modeling for predictions. The interactive dashboard, built with Power BI, visualizes key sales metrics and trends, enhancing data-driven decision-making.

## Tech Stack
- **Python**: Data cleaning, preprocessing, and forecasting.
- **Pandas**: Data manipulation and preprocessing.
- **Matplotlib**: Visualization of forecast charts.
- **Scikit-learn**: Linear regression model for forecasting.
- **Power BI**: Interactive dashboard creation.

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557D?style=for-the-badge&logo=matplotlib&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)

## Project Workflow

### Step 1: Data Cleaning & Preprocessing (Python)
- Loaded and explored the dataset.
- Handled inconsistencies in the `Item Fat Content` column, converting variations into two categories: `Low Fat` and `Regular`.
- Checked and removed null values to ensure clean data.

### Step 2: Sales Forecasting (Python)
- Implemented a linear regression model using `scikit-learn` for sales predictions.
- Forecasted sales for the next 30 days based on historical data.

### Step 3: Interactive Dashboard (Power BI)
- Created an interactive Power BI dashboard to visualize sales data, ratings, and trends.
- Added features like multi-select filters and real-time visualizations to enhance user interactivity.

## Screenshots and Demo
### Dashboard Preview
![Dashboard Screenshot](https://github.com/yogesh43221/Blinkit-Sales-Data-Analytics/blob/main/image.png)

### Forecast Chart
![Forecast Chart](https://github.com/yogesh43221/Blinkit-Sales-Data-Analytics/blob/main/sales_forecast.png)

## Key Features
- **Data Cleaning**: Standardized `Item Fat Content` values and removed nulls.
- **Forecasting Model**: Linear regression used for predicting sales over time.
- **Interactive Visualizations**: Power BI dashboard with filters and detailed analysis.
- **Reduced Analysis Time**: Interactive dashboard that reduced data review time by 40%.

## Getting Started
### Prerequisites
Ensure the following Python libraries are installed:
- `python`
- `pandas`
- `matplotlib`
- `scikit-learn`
- `power bi`

```bash
pip install pandas matplotlib scikit-learn
