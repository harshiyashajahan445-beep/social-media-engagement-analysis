# social-media-engagement-analysis
Python-based exploratory data analysis and multi-library visualization pipeline processing a 5,000-row social media dataset using Pandas, NumPy, Matplotlib, Seaborn, and Plotly.

A data visualization and exploratory analysis project using Python, Pandas, Matplotlib, Seaborn, and Plotly to explore and analyze social media post performance.
This project explores the social media engagement dataset using Python to clean, analyze, and visualize user interaction trends, post types, and audience demographics.

## Key Features & Libraries Used
* **Languages & Libraries:** Python, Pandas, NumPy, Matplotlib, Seaborn, Plotly
* **Data Preprocessing:** Handled missing values, formatted timestamps, and corrected negative metric anomalies to ensure data integrity.
* **Feature Engineering:** Engineered a custom weighted `engagement_score` formula: `(likes*1) + (comments*2) + (shares*3)`.
* **Matplotlib Visualizations:** Scatter plot (Likes vs. Impressions), Line chart (Daily engagement trend), Bar chart (Posts by type), Pie chart (Gender distribution), Histogram (Age distribution), and Box plot (Engagement rate).
* **Seaborn & Plotly Visualizations:** Count plot (Sentiment count by post type), Box plot (Engagement score distribution across countries), and an interactive Plotly scatter chart (Likes vs. Impressions by post type).
