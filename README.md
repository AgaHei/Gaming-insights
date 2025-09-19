# 🎮 Steam Game Market Analysis

Welcome to my Steam project, completed as part of the Jedha Fullstack Data program. This notebook explores the Steam game marketplace using a rich dataset of over 54,000 titles, with the goal of uncovering trends in pricing, popularity, platform distribution, and estimated revenue.

🔗 View the full notebook on Databricks: Steam_Project_AH_18_sept_2025:
https://dbc-5e06cba2-8c74.cloud.databricks.com/editor/notebooks/4036110302751698?o=2931884495904849


# 📌 Project Objectives

This analysis is structured around three key axes:

1. Macro-Level Trends

    Release patterns over time

    Impact of global events (e.g. COVID-19) on game publishing

    Distribution of pricing and discount strategies

2. Genre Insights

    Most positively rated genres

    Genre-specific revenue estimates

    Platform availability by genre

3. Platform Analysis

    Windows, Mac, and Linux support across genres

    Market share implications for developers and publishers

# 📊 Methodology

* Data cleaning and sanity checks to ensure reliability

* Revenue estimation using both raw owner counts and realistic conversion factors (10–30%)

* Visualizations built with Pandas and Seaborn for GitHub compatibility

* Annotation of key assumptions and limitations for transparency

# 💡 Key Findings
* Game releases peaked during the COVID-19 period (2019–2021), confirming a surge in home entertainment demand

* Top games show estimated revenues exceeding $200M, though actual sales likely represent a fraction of owner counts

* Certain genres (e.g. Strategy, Indie) show strong platform preferences, which may guide future development decisions

# 📁 Repository Structure

    📦 steam-project/
    ├── notebook/                            # Main notebook
    └── README.md                            # This file

# 🚀 Tools & Technologies

Python (Databricks environment)

PySpark for scalable data manipulation

Seaborn & Pandas for visualization

GitHub for version control and documentation


# 🧠 Notes for Reviewers

This notebook is designed to be readable and reproducible. Key assumptions are annotated, and revenue calculations are benchmarked against public figures (e.g. Portal 2, Counter-Strike 2) for credibility. All visualizations are compatible with GitHub rendering.