📊 Google Play Store Apps — Complete Exploratory Data Analysis (18 Charts)

This repository contains a complete Exploratory Data Analysis (EDA) of the Google Play Store Apps dataset, featuring 18 polished visualizations, full data cleaning, preprocessing, insights, and a modular Python structure for reproducibility.

This project is ideal for data analytics portfolios, blog content, market research, and EDA case studies.

📁 Repository Structure
📦 google-playstore-analysis
├── README.md
├── BLOG.md
├── requirements.txt
├── data/
│   └── Google-Playstore.csv
├── notebook/
│   └── GOOGLE_PLAYSTORE.ipynb
├── charts/
│   ├── chart01_top15_apps.png
│   ├── chart02_top15_categories.png
│   ├── chart03_free_vs_paid.png
│   ├── chart04_avg_installs_top10.png
│   ├── chart05_rating_distribution.png
│   ├── chart06_review_log_distribution.png
│   ├── chart07_price_distribution.png
│   ├── chart08_installs_vs_rating.png
│   ├── chart09_size_vs_rating.png
│   ├── chart10_apps_released_per_year.png
│   ├── chart11_last_updated_year.png
│   ├── chart12_installs_by_category_boxplot.png
│   ├── chart13_correlation_heatmap.png
│   ├── chart14_top10_apps_installs.png
│   ├── chart15_rating_vs_price.png
│   ├── chart16_category_avg_rating.png
│   ├── chart17_revenue_proxy.png
│   └── chart18_update_trend_over_years.png
└── src/
    ├── __init__.py
    ├── cleaning.py
    ├── visualization.py
    └── analysis.py

📄 Project Overview

This project analyzes a snapshot of the Google Play Store to uncover patterns in:

Ratings

Installs

Pricing behavior

Category performance

App size

User engagement

Release/update trends

Revenue potential

It includes:

✔️ A fully cleaned dataset
✔️ 18 detailed charts
✔️ A complete Jupyter Notebook
✔️ Modular Python scripts
✔️ A ready-made blog (BLOG.md)

📦 Dataset

Place your dataset at:

data/Google-Playstore.csv


Common columns include:

App Name

Category

Rating

Reviews

Installs

Price

Size

Released

Last Updated

Free/Paid

In-app purchases

If your column names differ, update cleaning.py.

🛠 Installation
1️⃣ Clone the repository
git clone https://github.com/<your-username>/google-playstore-analysis.git
cd google-playstore-analysis

2️⃣ Install dependencies
pip install -r requirements.txt

3️⃣ Add dataset
data/Google-Playstore.csv

4️⃣ Run the notebook
notebook/GOOGLE_PLAYSTORE.ipynb


or run the automated script:

python src/analysis.py

📊 Visualizations (18 Charts)

This analysis produces 18 high-quality plots:

Top 15 Apps

Top 15 Categories

Free vs Paid

Average Installs (Top Categories)

Rating Distribution

Log Review Distribution

Price Distribution

Installs vs Rating

Size vs Rating

Apps Released per Year

Last Updated Year

Category-wise Install Distribution (boxplot)

Correlation Heatmap

Top 10 Apps by Installs

Rating vs Price

Category Average Rating

Revenue Proxy (Price × Installs)

Update Trends by Year

Charts are exported automatically to:

charts/

🧹 Data Cleaning Summary

The project cleans and prepares the dataset by:

Converting numeric text (e.g., "1,000+" → 1000)

Cleaning prices ("$4.99" → 4.99)

Converting sizes ("12M" → 12, "1.2G" → 1228)

Parsing dates

Handling missing values

Creating new fields:

Size_MB

Release_Year

Last_Updated_Year

Revenue_Proxy

🧪 Modular Code (src folder)
cleaning.py

Handles all transformations:

Installs, price, size cleaning

Date parsing

New feature creation

visualization.py

Contains reusable plotting functions for all charts.

analysis.py

Runs full pipeline:

Load → Clean → Analyze → Save Plots

📈 Key Insights

Free apps dominate (~90%+)

Ratings cluster around 4.0–4.5

Price does not correlate with rating

Installs vary drastically across categories

App size is not a predictor of quality

Recently updated apps perform better

Communication, Social, Entertainment are top-performing categories

📜 Requirements
pandas
numpy
matplotlib
seaborn
plotly
jupyterlab
notebook

