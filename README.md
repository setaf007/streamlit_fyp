# Streamlit app for FYP
Used to visualize weather data in csv format
Functionality list:
# Weather Data Visualization App

This project is a Streamlit web application for interactive visualization and analysis of weather data. It allows users to filter, summarize, and visualize weather data from a CSV file using a variety of plots.

## Features

- **Data Filtering:** Filter the weather dataset by any column, including numeric, categorical, and datetime types.
- **Data Summary:** View summary statistics for both numerical and object columns, and inspect unique value counts.
- **Visualization Options:** Choose from multiple plot types:
  - BoxPlot
  - PieChart
  - ScatterPlot
  - LinePlot
  - BarChart
  - ViolinChart
  - HeatMap
  - 3D Scatter
  - BubbleChart
  - Choropleth Map (country-level visualization)
- **Customizable Plots:** Many plots allow for category separation, animation, and more.

## How to Run

1. **Install dependencies:**
   ```
   pip install -r requirements.txt
   ```
2. **Start the app:**
   ```
   streamlit run app.py
   ```

## File Descriptions

- `app.py`: Main Streamlit application. Handles data loading, filtering, summary, and all visualizations.
- `combined_csv.csv`: The weather dataset used for analysis and visualization.
- `requirements.txt`: Python dependencies for the project.

## Example Data Columns

The CSV includes columns such as:
- `name` (country)
- `datetime`
- `tempmax`, `tempmin`, `temp`
- `humidity`, `precip`, `windgust`, `windspeed`
- `conditions`, `description`, etc.

## Requirements

- Python 3.7+
- See `requirements.txt` for all required packages.

