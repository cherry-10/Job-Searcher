🔍 Google Job Listings Scraper
This is a Python-based project that fetches real-time job listings from Google Jobs using SerpAPI. The tool allows users to input a job title and location (default: India) and returns a cleaned list of jobs including title, company, location, date posted, and an application link.

🚀 Features
Search job listings based on title and location

Uses SerpAPI to fetch results from Google Jobs

Displays job title, company, location, posting date, and apply link

Simple and clean command-line interface

🛠️ Technologies Used
Python

Requests library

SerpAPI

📦 How to Run
Install the required package:

pip install requests
Replace the api_key in the script with your SerpAPI key.

Run the script:


python job_scraper.py
Enter a job title when prompted, and view the top listings directly in the terminal.

📌 Output Example
markdown

Enter a job title: Data Analyst

Top 10 Job Listings:
--------------------------------------------------
1. Data Analyst at ABC Pvt Ltd
   Location: Bangalore, India
   Posted: 3 days ago
   Apply Link: https://www.google.com/...
--------------------------------------------------
