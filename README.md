# Netflix Content Strategy — Exploratory Data Analysis

## Overview
Exploratory Data Analysis on Netflix's content library (8,800+ titles) to uncover actionable insights for content strategy, production decisions, and market expansion.

## Business Problem
Netflix needs to decide:
- Which type of content to produce (Movies vs TV Shows)?
- Which countries/markets to focus on?
- What genres have the highest global appeal?
- When is the best time to launch a new TV show?

## Dataset
- **Source:** `netflix.csv`
- **Size:** 8,807 titles × 12 features
- **Features:** show_id, type, title, director, cast, country, date_added, release_year, rating, duration, listed_in, description

## Tools & Libraries
- Python, Pandas, NumPy, Matplotlib, Seaborn

## Key Insights
- TV Shows growing faster than Movies post-2018 — better for subscriber retention
- India ranks 2nd in content volume but is massively underserved given its 1.4B population
- TV-MA and TV-14 make up ~60% of the library — Netflix targets mature audiences
- July and December are peak months to launch TV shows
- International Drama is the #1 genre by volume with cross-market appeal
- Korean and Japanese content delivers outsized global engagement

## Project Structure

netflix-eda-analysis/
├── Netflix_EDA_Analysis.ipynb   # Main analysis notebook
├── netflix.csv                  # Dataset
└── README.md
