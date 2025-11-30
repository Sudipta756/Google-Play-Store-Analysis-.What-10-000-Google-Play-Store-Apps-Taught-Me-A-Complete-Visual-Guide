# Google Play Store EDA: Uncovering the App Market 📱

## 📖 Overview
This project performs a comprehensive Exploratory Data Analysis (EDA) on a dataset of **2.3 million Google Play Store applications**. The goal is to uncover trends in app popularity, pricing strategies, and quality metrics to understand what drives success in the mobile ecosystem.

## 🔑 Key Insights
1.  **The "Freemium" Reality:** The market is 98% free. Only ~2% of apps are paid, and free apps get exponentially more downloads across every category.
2.  **Supply vs. Demand:** **Education** is the most crowded category (highest supply), but **Communication** and **Social** apps dominate in downloads (highest demand).
3.  **Popularity ≠ Quality:** There is a strong correlation (0.75) between downloads and the *number* of ratings, but a near-zero correlation (0.10) between downloads and the *actual star rating*. Viral success does not guarantee a good product.
4.  **The "Editor's Choice" Club:** This badge is extremely rare (0.04% of apps). **Games** receive this award far more often than any other category.
5.  **Price Ceiling:** For paid apps, the acceptable price range is effectively capped at **$10**. Anything higher is a statistical outlier.

## 📊 Visualizations
The analysis includes 17 visualizations covering:
- Category distribution and popularity
- Free vs. Paid market share
- Impact of ads on user ratings
- Correlation heatmaps of app metrics
- Price distribution analysis

*(See `images/` folder for full charts)*

## 📂 Project Structure
- `data/`: Raw and processed data files.
- `notebooks/`: Jupyter notebooks used for exploration.
- `scripts/`: Executable Python scripts for data cleaning.
- `images/`: Exported plots and charts.

## 🚀 How to Run
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/yourusername/google-play-store-eda.git](https://github.com/yourusername/google-play-store-eda.git)
    cd google-play-store-eda
    ```
2.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
3.  **Run the cleaning pipeline:**
    ```bash
    python scripts/clean_data.py
    ```
4.  **Launch the Notebook:**
    ```bash
    jupyter notebook notebooks/google_play_store_eda.ipynb
    ```

## 🛠️ Tech Stack
- **Python** (Pandas, NumPy)
- **Visualization** (Matplotlib, Seaborn, Plotly)
- **Environment** (Jupyter)

---
*Data Source: Google Play Store Dataset (2.3 Million Apps)*
