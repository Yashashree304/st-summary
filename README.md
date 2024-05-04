## Overview
This app fetches and summarizes articles using keywords, category, and date range inputs provided by the user.

## Features
- User inputs:
  - Keywords (comma-separated)
  - Category
  - Start Date (YYYY-MM-DD)
  - End Date (YYYY-MM-DD)
- Fetches articles based on user inputs from Event Registry.
- Summarizes each article using the Facebook BART model.
- Displays fetched articles with summaries.

## Setup
To run this Streamlit app locally, follow these steps:

1. Clone the GitHub repository:
   git clone https://github.com/Yashashree304/st-summary.git
2.  cd st-summary
3.  pip install -r requirements.txt
4.  streamlit run stapp.py
