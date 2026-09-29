🎬 Netflix Real-Time Content & Audience Analytics

An end-to-end data analytics project analyzing Netflix's global catalog, audience ratings, and multi-year growth trends. This project integrates data cleaning in Python, relational SQL querying, and a dynamic 4-page Power BI dashboard.


📊 Dashboard Previews

1. Content Overview
![Overview](Screenshot%202026-09-29%20233051.png)

2. Content Trends
![Content Trends](Screenshot%202026-09-29%20233108.png)

3. Geography & Ratings
![Geography and Ratings](Screenshot%202026-09-29%20233122.png)

4. Key Insights
![Key Insights](Screenshot%202026-09-29%20233137.png)


🛠️ Tech Stack & Pipeline

Python, Pandas & NumPy:
  - Handled missing values across ratings, countries, and languages.
  - Parsed date timestamps into `year_added` and `month_added` features.
  - Separated runtimes into numeric minutes for movies and season counts for TV shows using NumPy vectorization.
SQL (SQLite Queries):
  - Computed top-level catalog KPIs and content distributions.
  - Aggregated top-performing countries and genres.
  - Applied window functions (`LAG()`) to calculate Year-over-Year (YoY) content growth.
Power BI:
  - Designed a dark-themed Netflix UI with custom red branding and dynamic left-navigation tabs.
  - Built custom DAX measures for KPI summaries and growth rates.
  - Visualized insights using treemaps, matrix tables, donut charts, scatter plots, and stacked bars.


📂 Repository Contents

- `NETFLIX_PROJECT.ipynb` - Complete Python, Pandas, NumPy & SQL data pipeline.
- `netflix_real_time_project_dataset.csv` - Raw source catalog data.
- `netflix_cleaned_final.csv` - Cleaned and transformed dataset.
- `NETFLIX FINAL PROJECT.pbix` - Multi-page Power BI workbook.
