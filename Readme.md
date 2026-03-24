# 🛒 Amazon Sales Dataset Exploratory Data Analysis (EDA)

📌 Project Overview

This project performs an in-depth Exploratory Data Analysis (EDA) on an Amazon sales dataset containing over 1,400 products. The analysis focuses on identifying pricing trends, discount impacts, and customer satisfaction metrics across various product categories such as Electronics, Home & Kitchen, and Computers & Accessories.

🛠️ Technologies & Libraries

The following Python stack was used for data processing and visualization:

Data Manipulation: pandas, numpy

Visualization: matplotlib, seaborn, plotly.graph_objs, plotly.express

Statistical Analysis: scipy

📊 Dataset Features

The dataset includes detailed information for each product, such as:

Identifiers: product_id, product_name, user_id, review_id.

Pricing: actual_price, discounted_price, and discount_percentage.

Ratings: rating and rating_count.

Content: about_product, review_title, and review_content.

🔍 Key Analysis Steps

Data Cleaning: Setting display options for high-dimensional data viewing.

Descriptive Statistics: Analyzing numerical distributions for prices and ratings using .describe().

Category-Wise Analysis: Grouping data by category to find top-performing segments by average rating.

Correlation Analysis: Investigating the relationship between pricing (e.g., discounted_price) and customer ratings.

Interactive Visualization: Using Plotly to create responsive charts, including box plots for price distribution across different categories.

🚀 Getting Started

1. Clone the repository:

Bash

git clone https://github.com/your-username/amazon-sales-eda.git

2. Install dependencies:

Bash

pip install pandas numpy matplotlib seaborn scipy plotly

3. Run the analysis:

Open Amazon Sales Dataset EDA.ipynb in Jupyter Notebook or Google Colab.

📈 Sample Insights

The analysis highlights categories with the highest average customer satisfaction.

Visualizations reveal how discount depth correlates with product popularity and rating counts.
