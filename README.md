# Amazon Retail Sales Analysis

This repository contains an exploratory data analysis (EDA) of an Amazon retail sales dataset. The project leverages Python, Pandas, Matplotlib, and Seaborn to clean and analyze e-commerce product data.

## Project Goals
- **Data Cleaning:** Clean string-formatted pricing, handle missing rating data, and standardize column names.
- **Feature Engineering:** Extract meaningful high-level categories from complex category strings.
- **Exploratory Data Analysis:** Examine top product categories and understand inventory distribution.
- **Customer Preferences:** Analyze the distribution of product ratings and how they correlate with pricing.
- **Visualization:** Create clear and intuitive charts to support inventory planning and decision-making for buyers and sellers.

## Structure
- `notebooks/`: Contains the main Jupyter Notebook with the full analysis (`Amazon_Retail_Sales_Analysis.ipynb`).
- `data/`: Directory for the raw CSV dataset (ignored in git to keep the repository lightweight).
- `output/`: Generated visualizations and charts.

## Setup Instructions
To run this project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/Akanksh-V/Amazon-Retail-Sales-Analysis.git
   cd Amazon-Retail-Sales-Analysis
   ```
2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the setup script to download the dataset and build the notebook:
   ```bash
   python setup_project_2.py
   ```
5. Launch Jupyter Notebook to explore the findings:
   ```bash
   jupyter notebook notebooks/Amazon_Retail_Sales_Analysis.ipynb
   ```

## Key Findings
- **Inventory Patterns:** Specific tech and home appliance categories dominate the product listings. Inventory planning should prioritize these high-volume areas.
- **Rating Trends:** Customers generally leave positive ratings, but items that fall below 3.5 stars often have specific quality complaints that should be addressed.
- **Price Insights:** Higher prices do not guarantee better ratings. Customers often favor mid-range items that offer the best perceived value.
