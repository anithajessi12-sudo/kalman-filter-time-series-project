# Time Series State-Space Project

## 📁 Project Structure

project-root/
│
├── data/
│     └── time_series_dataset.csv
│
├── notebooks/
│     └── TimeSeries_StateSpace_Project.ipynb
│
├── src/
│     ├── kalman_filter.py
│     ├── state_space_model.py
│     ├── em_estimator.py
│     ├── sarima_baseline.py
│     └── utils.py
│
├── results/
│     ├── final_full_project_report.pdf
│     ├── time_series_full_report_with_image.pdf
│     ├── raw_timeseries_plot.png
│     ├── acf_plot.png
│     ├── pacf_plot.png
│     └── diff_series.png
│
└── README.md

## 📌 Overview

This project implements:

- State-space model  
- Kalman Filter  
- RTS Smoother  
- EM algorithm  
- SARIMA baseline  
- Full EDA (ACF, PACF, ADF test)

## 🚀 How to Run

1. Open: notebooks/TimeSeries_StateSpace_Project.ipynb  
2. Ensure dataset in: data/time_series_dataset.csv  
3. Run cells top to bottom  
4. For script version: python src/main.py

## 📊 Results

All plots + PDF reports inside `results/`
