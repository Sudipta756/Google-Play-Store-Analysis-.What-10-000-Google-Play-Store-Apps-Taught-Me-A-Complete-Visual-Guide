# Google-Play-Store-Analysis-.What-10-000-Google-Play-Store-Apps-Taught-Me-A-Complete-Visual-Guide
# Google Play Store EDA: Analyzing 2.3 Million Apps 📱

## 📖 Overview
This project performs a comprehensive exploratory data analysis (EDA) on a dataset of **2.3 million Google Play Store applications**. The goal was to uncover trends in app popularity, pricing models, and quality assurance.

## 🔑 Key Insights
1.  **The "Freemium" Rule:** 98.02% of all apps are free. Paid apps make up less than 2% of the market.
2.  **Supply vs. Demand:** "Education" is the most crowded category (highest supply), but "Communication" and "Social" apps receive the most downloads (highest demand).
3.  **Popularity ≠ Quality:** There is a strong correlation (0.75) between downloads and rating count, but a near-zero correlation (0.10) between downloads and the actual star rating. Viral apps aren't always good apps.
4.  **The "Editor's Choice" Standard:** Only 0.04% of apps receive this badge. "Games" is the most awarded category.
5.  **Price Ceiling:** The vast majority of paid apps cost between $1 and $5. Apps over $10 are statistical outliers.

## 📂 Repository Structure
- `data/`: Contains raw and processed datasets.
- `notebooks/`: Jupyter notebooks used for exploration and visualization.
- `scripts/`: Python scripts for reproducible data cleaning.
- `images/`: Saved charts and graphs generated from the analysis.

## 🚀 How to Run
1.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
2.  **Run the cleaning script:**
    ```bash
    python scripts/clean_data.py
    ```
3.  **Explore the notebook:**
    Open `notebooks/analysis.ipynb` to view the visualizations.

## 📊 Visualizations
Key charts (like the Correlation Matrix and Category Distribution) can be found in the `images/` folder.

---
*Data Source: Google Play Store Dataset (2.3 Million Apps)*
