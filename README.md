# Google Play Store Data Analysis

An end-to-end data analysis project exploring app performance, category trends, user ratings, and pricing models on the Google Play Store. This repository covers data cleaning, exploratory data analysis (EDA) in Python, and interactive visualization in Tableau.

## 📁 Repository Structure

| File | Description |
| :--- | :--- |
| `google_play_store_dataset.csv` | The original, raw dataset containing Google Play Store app metrics. |
| `play_store_analysis.ipynb` | Jupyter Notebook containing data cleaning, preprocessing, and exploratory data analysis. |
| `play_store_cleaned.csv` | Processed and cleaned dataset ready for analysis and visualization. |
| `Category Summary.csv` | Aggregated summary metrics grouped by app category. |
| `Book1.twb` | Tableau Workbook containing interactive charts and dashboards built from the cleaned data. |

## 🛠️ Tools & Technologies

* **Python (Jupyter Notebook):** Data cleaning, manipulation, and statistical analysis (`pandas`, `numpy`, `matplotlib`/`seaborn`).
* **Tableau:** Data visualization and interactive dashboard creation.
* **CSV / Excel:** Data storage and summary reporting.

## 🔄 Project Workflow

1. **Data Cleaning & Preprocessing (`play_store_analysis.ipynb`):**
   * Handled missing values, duplicate entries, and inconsistent formatting (e.g., installs, app sizes, and prices).
   * Exported the finalized dataset to `play_store_cleaned.csv` and generated category-level aggregations in `Category Summary.csv`.
2. **Exploratory Data Analysis (`play_store_analysis.ipynb`):**
   * Analyzed distributions across app categories, content ratings, and free vs. paid pricing models.
   * Evaluated relationships between installs, user reviews, and overall app ratings.
3. **Data Visualization (`Book1.twb`):**
   * Built visual dashboards in Tableau to highlight top-performing categories and key market trends.

## 📊 Key Findings

> *Add 3–5 bullet points summarizing the main insights from your notebook and Tableau dashboard here.*
* **Top Categories:** [e.g., Family and Game categories account for the highest volume of apps...]
* **Ratings & Reviews:** [e.g., Apps with higher review counts tend to maintain ratings above X...]
* **Free vs. Paid:** [e.g., Over X% of apps are free, while paid apps dominate in...]

## 🚀 How to Use

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Muielvis/Google-data-analysis.git
   cd Google-data-analysis
   ```
2. **Explore the Notebook:**
   Open `play_store_analysis.ipynb` using Jupyter Notebook, JupyterLab, or VS Code to review the code and run the analysis.
3. **View the Visualizations:**
   Open `Book1.twb` in **Tableau Desktop** or **Tableau Public** (connect it to `play_store_cleaned.csv` or `Category Summary.csv` if prompted for the data source).

## 👤 Author

**Muielvis**
* GitHub: [@Muielvis](https://github.com/Muielvis)
