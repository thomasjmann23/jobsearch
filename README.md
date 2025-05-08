# jobsearch
A Streamlit app that aggregates job listings from Greenhouse-hosted careers pages for multiple companies and provides direct access to each job post.

# Job Search Aggregator

A Streamlit-based job search tool that pulls live job listings from multiple company careers pages hosted on Greenhouse and displays them in a searchable, filterable table with direct links.

## Features
- Accepts a list of company Greenhouse handles (e.g., `airbnb`, `stripe`)
- Fetches and parses job listings including:
  - Title, department, location, and posting URL
- Displays jobs in a clean Streamlit interface
- Export results to CSV (optional)

## How to Run
```bash
pip install -r requirements.txt
streamlit run app.py
