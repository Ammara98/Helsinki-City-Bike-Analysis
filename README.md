# Helsinki City Bike Network Analysis

This project analyzes the Helsinki City Bike system using trip-level open data. It includes data cleaning, feature engineering, exploratory analysis, and visualizations to understand ridership patterns, station activity, and temporal trends within the bike-sharing network.

---

## Project Overview

The analysis includes:

- Loading and preparing the Helsinki City Bikes dataset
- Handling missing and inconsistent values
- Feature engineering (trip duration, time-of-day grouping, weekday/weekend flags)
- Exploratory analysis of:
  - Station popularity
  - Temporal usage patterns (hourly, daily, monthly)
  - Trip duration and distance distributions
  - Inbound and outbound station flows
- Data visualizations to support interpretation
- Summary insights about user behavior and system usage

---

## Repository Structure

```
.
├── Ammara_Helsinki_Bike_Analysis.ipynb   # Main notebook for analysis
└── README.md                                 # Project documentation
```

---

## Features and Analyses Included

- Trip duration analysis
- Most frequent departure and return stations
- Time-based ridership patterns
- Seasonal and monthly trends
- Flow direction patterns and station usage asymmetry
- Correlation exploration between trip attributes
- Visualizations using Matplotlib, Seaborn, and optional Plotly

---

## Requirements

Install the required Python packages:

```bash
pip install pandas numpy matplotlib seaborn plotly
```

If needed:

```bash
pip install jupyter
```

---

## How to Run the Notebook

1. Download the dataset from:  
   https://www.kaggle.com/datasets/geometrein/helsinki-city-bikes

2. Extract the files and place `database.csv` in the working directory.

3. Open the notebook:

```bash
jupyter notebook Ammara_Helsinki_Bike_Analysis.ipynb
```

4. Run all cells in sequence.

---

## Example Insights

The analysis identifies patterns such as:

- Peak usage during morning and evening commute hours
- High-demand stations within the city center
- Seasonal variation with higher usage in warmer months
- Typical trip duration and distance ranges
- Differences between departure and return station usage

Refer to the notebook for complete findings.

---

## Notes

- Ensure the dataset file is named `database.csv` or update the path in the notebook.
- Large datasets may require additional memory to process efficiently.

---

## License

This project is available for analytical and educational purposes. You may modify or extend the notebook as needed.
