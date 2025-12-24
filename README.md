Google Play Store Apps Analysis
A comprehensive data analysis and preprocessing project exploring a dataset of over 2.3 million Google Play Store apps. This project demonstrates an end-to-end data science workflow, from data ingestion and rigorous cleaning to interactive exploratory visualization.

📌 Project Overview
The mobile app ecosystem is massive and highly dynamic. This project aims to clean the raw data and uncover patterns regarding app popularity, pricing strategies, and user ratings. By standardizing diverse metrics (like app size and install counts), we can better understand what defines a successful app in the modern marketplace.

🛠️ Tech Stack
Environment: Google Colab / Jupyter Notebook

Data Manipulation: Pandas, NumPy

Visualization: Matplotlib, Seaborn, Plotly Express (Interactive charts)

Utilities: Warnings (for clean output)

🗃️ Dataset Summary
The project analyzes a dataset containing 2,312,944 rows and 24 columns. Key features include:

Metadata: App Name, ID, Category, Developer info.

Metrics: Rating, Rating Count, Installs (Min/Max).

Business Logic: Free/Paid status, Price, Ad Support, In-App Purchases.

Technical Info: Size, Android version requirements, Release/Update dates.

🧹 Data Cleaning Process
The notebook focuses heavily on preparing the data for reliable analysis through the following steps:

Dimensionality Reduction: Dropped irrelevant columns such as Developer Email, Privacy Policy, and Scraped Time to optimize processing.

Missing Value Imputation:

Rating and Rating Count nulls were filled with 0.

Currency nulls and placeholder values (like "XXX") were standardized to "USD".

Released dates were filled using the dataset's mode.

Data Standardizing: * Converted "Released" and "Last Updated" columns to proper datetime objects.

Standardized the Size column by stripping units (M/K), converting KB to MB, and imputing the median for missing values.

Feature Encoding: Replaced boolean values in the "Free" column with descriptive strings ("Free" vs. "Paid") for better readability in charts.

📊 Exploratory Data Analysis (EDA)
The analysis includes visualizations to answer questions such as:

Which categories have the highest volume of apps?

How do user ratings vary across different app categories?

What is the distribution of "Free" vs "Paid" apps?

Does app size correlate with the number of installs?

🚀 Getting Started
Clone the repository:

Bash

git clone https://github.com/your-username/google-playstore-analysis.git
Install requirements:

Bash

pip install pandas numpy matplotlib seaborn plotly
Run the analysis: Open GOOGLE_PLAYSTORE (1).ipynb in Jupyter or Google Colab.

📈 Key Insights
Note: Based on your notebook outputs, you can add specific findings here, such as "Education and Tools are the top categories" or "Over 90% of apps are Free."
