# U.S. Data Science Job Market Trends & Forecasting

This project explores the U.S. data science job market across the top 10 metropolitan areas from 2022 to 2024 using employment and salary data. It includes visual insights built in Tableau and machine learning models for forecasting job demand and salary expectations through 2027.

# Project Objectives

* Analyze job trends for data scientist roles.
* Identify top 10 metropolitan areas by total employment in 2024.


Forecast:
* Total employed in top metro areas for the next 3 years.
* Average salary growth for data science roles.
* Create an interactive Tableau dashboard to visualize trends.


├── data/


│      └── data_scientist_forecast.csv


│      └── employment_forecast_tableau.csv


│      └── salary_forecast_tableau.csv


│      └── historical_data_for_tableau.csv


│      └── forecast_data_for_tableau.csv


│      └── MSA_M2022_dl.xlsx


│      └── MSA_M2023_dl.xlsx


│      └── MSA_M2024_dl.xlsx


├── notebooks/


│      └── top_10_jobs.ipynb


│      └── 2022-2024_trends.ipynb


|      └── Data_Scientist_Job_Forecast.ipynb


├── images/


│      └── tableau_dashboard_screenshot.png


├── README.md


└── requirements.txt


# Key Insights

* Top 10 metro areas by total data science employment in 2024.
* Projected salary growth and hiring trends (2025–2027).

# Tableau Dashboard

Explore the interactive Tableau dashboard here: [Link to Tableau Public](https://public.tableau.com/views/DataScienceJobTrends_17533306711200/MetroEmploymentForecast?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)


Features:
* Filter by job title or metro area
* Year-over-year percentage changes
* Forecasted trends based on ML models

# Machine Learning

Models were built using Scikit-learn to forecast:
* Total Employed (per metro area, per job title)
* Mean Salary (nationally and regionally)


Model Type: Linear Regression


Evaluation Metric: Mean Absolute Error (MAE)


Data Split: 80/20 train-test

# How to Run

Clone the repo:
git clone https://github.com/jillmaise/data-science-job-trends.git


cd data-science-jobs-trends

Install dependencies:


pip install -r requirements.txt

Launch the notebook:


jupyter notebook notebooks/job_insights.ipynb

# Dependencies

* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn
* Tableau (for dashboard creation)

# Data Source

U.S. Bureau of Labor Statistics - OES survey data from 2022–2024.

# Skills Demonstrated

✅ Data wrangling & analysis


✅ Visualization (Tableau, matplotlib)


✅ Forecasting using regression models


✅ End-to-end project lifecycle


✅ GitHub project structuring

# Contact

Made by Jill S. Maisel


Connect with me on [LinkedIn](https://www.linkedin.com/in/jill-maisel/)

