Overview:
This project includes a set of tools for scraping, cleaning, visualizing, and analyzing job listings from Indeed, as well as an LLM-powered recommendation system that suggests job titles based on user-provided skills. The project is built in Python and works with a CSV file containing job data.
Project Structure
app_LLM.py: This script leverages a Large Language Model (LLM) to:

Extract relevant skills from job descriptions using regex.
Filter job listings based on user input or generated skills.
Provide job recommendations.
scrape_cleaning_indeed.py: This script handles the scraping of job data from Indeed and cleans the data for analysis.

Indeed_Jobs.csv: A CSV file containing the scraped job data, including columns such as:

job_title: The title of the job.
salary: Salary information (if available).
company_name: The name of the company offering the job.
company_rating: The company's rating (if available).
description: A detailed description of the job.
Visualizations: Code for generating visual representations of the job data (e.g., salary distributions, company ratings, job frequency by title, etc.).

Features:
Job Filtering:

Enter a skill or set of skills, and the system will recommend relevant job listings based on those skills.
The program will extract skills from job descriptions and compare them with user input to filter jobs.
Web Scraping:

Scrapes job data from Indeed and cleans the dataset for further analysis.
LLM Recommendations:

Uses an LLM to generate skill suggestions based on job descriptions.
Data Visualizations:

Generate visual insights into the job data, including:
Salary distribution plots.
Company rating histograms.
Job frequency by title and location.
More depending on the available data and visualizations.
