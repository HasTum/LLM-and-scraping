**Job Listings Analysis and LLM-Powered Recommendation System**

**Overview:**

This project provides a comprehensive suite of tools for collecting, cleaning, analyzing, and visualizing job listings from Indeed, coupled with an advanced LLM-based recommendation system. The recommendation system filters job listings by extracting skills from job descriptions and matching them with user-provided skills. The project is implemented in Python and operates on a CSV dataset containing job-related information.

**Project Structure:**

The project directory is organized as follows:

app_LLM.py:
A script that utilizes a Large Language Model (LLM) to:

Extract relevant skills from job descriptions using regex.
Filter job listings based on user input or LLM-generated skill recommendations.
Provide personalized job recommendations.
scrape_cleaning_indeed.py:
A script dedicated to:

Scraping job data from Indeed using Python tools like BeautifulSoup.
Cleaning and preprocessing the scraped data for analysis.
Indeed_Jobs.csv:
A CSV file containing the cleaned and preprocessed job data. Key columns include:

job_title: Title of the job.
salary: Salary information (if available).
company_name: The company offering the job.
company_rating: Rating of the company (if available).
description: Detailed job description.

**Visualizations Code:**

Scripts for generating data visualizations such as:

Salary distribution plots.
Company rating histograms.
Job frequency by title, skill, and location.

**Features:**

**1. Job Filtering:**
Users can input a skill or a set of skills.
The program matches user-provided skills against skills extracted from job descriptions.
Filters and displays job listings that align with the user's skill set.
**2. Web Scraping:**
Scrapes job listings from Indeed, collecting details like job titles, salaries, company ratings, and descriptions.
Processes raw data into a structured format, saving it in a CSV file for further use.
**3. LLM-Powered Recommendations:**
The system uses an LLM to:
Identify and extract skills from job descriptions.
Suggest additional skills based on job trends.
Match job listings to user-provided or LLM-suggested skills.
**4. Data Visualizations:**
Provides visual insights into the dataset:
Salary Distributions: Visualizes salary ranges and averages.
Company Ratings: Displays distributions of company ratings to help users gauge employer quality.
Job Frequencies: Analyzes the frequency of job titles and skills across listings.
Additional visualizations can be generated based on available data.

**Getting Started:**

Clone the Repository:

Clone the project repository to your local system.
Install Dependencies:

Use pip install -r requirements.txt to install the required Python libraries.
Run the Web Scraper:

Execute scrape_cleaning_indeed.py to scrape and clean job data from Indeed.
Generate Visualizations:

Use the visualization scripts to analyze trends and patterns in the dataset.
Run the LLM-based Recommendation System:

Launch app_LLM.py to filter and recommend jobs based on input skills or LLM suggestions.

**Future Enhancements and Suggestions:**

Integration with Airflow:

Automate the scraping, cleaning, and analysis workflows using Apache Airflow for scheduling and dependency management.
Poetry for Dependency Management:

Use Poetry instead of requirements.txt for a more structured and Pythonic dependency management system.
Pre-commit Hooks:

Set up pre-commit hooks for code quality checks, linting, and formatting using tools like black and flake8.
Dashboard for Insights:

Develop an interactive dashboard (e.g., Streamlit) for users to explore job trends and recommendations dynamically.
Advanced LLM Features:

Incorporate advanced LLM capabilities to generate cover letter drafts tailored to recommended jobs.

**Conclusion:**

This project streamlines the process of analyzing and finding suitable job listings by combining robust data scraping, cleaning techniques, and the power of LLMs. The visualizations provide meaningful insights, while the recommendation system enhances user experience by aligning job opportunities with individual skill sets.






