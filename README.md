# Pulsegen Review Scraper

## Overview
This project is a Python script that scrapes SaaS product reviews from platforms
like G2 and Capterra. The script accepts a company name, start date, end date,
and review source as inputs and outputs the reviews in JSON format.

## Features
- Accepts company name, start date, end date, and source as input
- Scrapes available reviews from the selected platform
- Filters reviews based on the given date range
- Outputs structured review data in JSON format
- Includes extensible structure for an additional SaaS review source

## Technologies Used
- Python
- Requests
- BeautifulSoup

## How to Run

### Install Dependencies
```bash
pip install -r requirements.txt

Run the Script
python scraper.py microsoft-teams 2024-01-01 2024-06-30 g2
If command-line arguments are not provided, default values are used.
Output
The script generates a file named:
sample_output.json
