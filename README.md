# Reddit Data Scraping Analysis

## Project Overview
This project collects and organizes Reddit post and comment data from the r/food subreddit using Python, requests, JSON parsing, and pandas. The notebook demonstrates foundational experience working with real-world web data, recursive functions, and data cleaning workflows.

## Note
This project was completed earlier in my data analytics learning journey. While my coding practices and technical skills have improved since creating this notebook, I chose to include it because it demonstrates foundational experience with data collection, JSON parsing, pandas, and exploratory data analysis.

## Objectives
- Collect Reddit post data from the r/food subreddit
- Extract and organize post metadata
- Convert JSON responses into structured pandas DataFrames
- Export cleaned datasets to CSV
- Collect Reddit comment threads and nested replies
- Practice recursive function design

## Tools Used
- Python
- Jupyter Notebook
- pandas
- requests
- JSON

## Skills Demonstrated
- Data collection
- JSON parsing
- Data cleaning
- Recursive functions
- Pandas DataFrames
- CSV export
- Web data extraction

## Repository Structure
```text
reddit-data-scraping-analysis/
│
├── README.md
├── requirements.txt
├── .gitignore
│
├── notebooks/
│   └── reddit.ipynb
```

## What the Notebook Does
The notebook connects to Reddit’s public JSON endpoint and retrieves top posts from the r/food subreddit. It extracts metadata such as author names, post IDs, scores, URLs, creation dates, and subreddit information before organizing the results into a pandas DataFrame.

The project also collects comment data from a Reddit thread and uses recursive logic to gather nested replies and discussions. The cleaned data is then exported into CSV format for additional analysis.

## What I Would Improve Today
If rebuilding this project now, I would:
- Refactor repeated code into reusable functions
- Improve notebook organization and markdown documentation
- Add stronger request error handling
- Include visualizations and exploratory analysis
- Separate data collection and analysis into modular scripts

## Key Takeaway
This project helped build foundational experience with Python-based data collection, cleaning, and structuring of web data. It also introduced important concepts such as recursive logic and working with nested JSON structures.
