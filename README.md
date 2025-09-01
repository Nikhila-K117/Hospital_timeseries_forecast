**Project Overview**

•This project applies time series forecasting to hospital admission data to predict patient inflows and support healthcare resource planning. The workflow covers data preprocessing, model development, evaluation, and dashboarding in Python and Power BI.

**Dataset**

•15,000+ hospital admission records.
•Includes admission/discharge dates, demographics, diagnoses, and duration of stay.
•Cleaned for date mismatches, missing values, and outliers to ensure reliable forecasts.

**Methodology**

•Data Preparation – Converted raw hospital records into weekly admission counts.
•Modeling – Implemented ARIMA, Prophet, and a Hybrid model.
•Evaluation – Compared performance using MAE and RMSE.
•Visualization – Built plots in Python and an interactive Power BI dashboard.

**Key Results**

•Prophet model performed best with RMSE 17.3 and MAE 14.4.
•Hybrid forecasts provided balanced accuracy.
•Dashboard enabled comparison of model performance and trend insights.

**Tech Stack**

•Python: Pandas, NumPy, Statsmodels, pmdarima, Prophet, Matplotlib, Seaborn
•Visualization: Power BI (interactive dashboard with DAX measures)
•Tools: Jupyter Notebook, GitHub

**Project Structure**
📂 hospital-time-series-forecast
├── notebook.ipynb      # Jupyter Notebook with full workflow
├── model_forecasts.csv # Forecast outputs for Power BI
├── dashboard.pbix      # Power BI dashboard file
└── README.md           # Project documentation

**Future Work**

•Add external factors (seasonality, holidays, epidemics).
•Automate pipeline for real-time hospital admission forecasting.
•Extend dashboard to predict bed occupancy and resource allocation.
