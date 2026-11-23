# Olist E-commerce Sales Dashboard

A data visualization project built for the **CodeAlpha Data Analytics Internship (Task 3)**. It analyses Brazilian e-commerce orders from the Olist dataset and presents the results in an interactive Tableau Public dashboard.

## Live Dashboard
👉 **[View the dashboard on Tableau Public]((https://public.tableau.com/app/profile/sayan.bhadra/viz/Book1_17954159039400/Dashboard1?publish=yes))[*]

![Dashboard](dashboard.png)

## Dataset
- **Source:** Olist Brazilian E-Commerce Public Dataset (Kaggle)
- **Size:** about 96,000 orders after cleaning
- Several tables (orders, payments, reviews, products, customers) were merged into one clean file, `clean_olist.csv`.

## Tools Used
- **Python** (pandas, matplotlib / seaborn) for cleaning, merging and exploratory charts
- **Tableau Public** for the interactive dashboard
- **Jupyter Notebook** for the analysis

## What I Did
1. Cleaned and merged the raw Olist tables in Python (`visualization.ipynb`).
2. Created 5 exploratory charts in the notebook.
3. Exported the final dataset as `clean_olist.csv`.
4. Built 6 sheets in Tableau and combined them into one dashboard.

## Dashboard Contents
| Section | What it shows |
|---------|---------------|
| Total Revenue | Overall revenue across all orders |
| Total Orders | Number of unique orders (96,470) |
| Average Review | Mean customer review score (about 4.08) |
| Monthly Trend | Revenue over time, 2017 to 2018 |
| Top Categories | Product categories ranked by revenue |
| Orders by State | Map of order counts across Brazilian states |

## Key Insights
- Revenue grew steadily through 2017 and levelled off in 2018.
- **São Paulo** has by far the most orders of any state.
- **health_beauty**, **watches_gifts** and **bed_bath_table** are the top revenue categories.
- The average review score is about **4.1 out of 5**, so customers are generally satisfied.

## Project Structure




## Author
**Sayan Bhadra**
B.Sc. Data Science, Techno India University
GitHub: [sayan-bhadra](https://github.com/sayan-bhadra)
