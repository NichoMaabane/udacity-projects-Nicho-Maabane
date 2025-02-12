Employee Work Arrangement Analysis

Overview

This project aims to analyze the factors that influence whether an employee works remotely, in-person, or in a hybrid arrangement. By using a Decision Tree model, we identify the most significant predictors of work arrangements, such as job role, work experience, and education level. Additionally, we explore the relationship between job satisfaction and work arrangements, and analyze the distribution of work arrangements across different age groups and employment types.

 Blog post link
https://medium.com/@nichomaabane46/unveiling-the-dynamics-of-work-arrangements-insights-from-data-analysis-19a7ac3b79b1

Installation

To run the code, you need the Anaconda distribution of Python. The code is compatible with Python 3.x versions and should execute without any issues. Additionally, you need to install the following libraries using pip:

pip install -r requirements.txt
The requirements.txt file includes:

pandas
numpy
scikit-learn
matplotlib
seaborn
Usage
To use this project, follow these steps:

Clone the repository to your local machine.
Install the required libraries as mentioned in the Installation section.
Open the Jupyter Notebook BlogPost.ipynb to explore the data analysis and visualizations.
Review the 2024 Developer Survey.pdf for a summary of the survey results.
Use the survey_results_public.csv and survey_results_schema.csv files for further analysis.

Project Motivation

For this project, I was interested in understanding the factors that influence an employee's work arrangement, whether it be remote, in-person, or hybrid. By analyzing data through a Decision Tree model, I aimed to uncover the most significant predictors of work arrangements, such as job role, work experience, and education level.

Additionally, I sought to explore the relationship between job satisfaction (JobSat) and work arrangements. By investigating job satisfaction scores, I aimed to determine if higher or lower job satisfaction is associated with a particular work arrangement.

Furthermore, I wanted to analyze the distribution of work arrangements across different age groups and employment types. By examining both the model's predictions and the actual data, I aimed to understand how work arrangements vary among different age groups (e.g., under 18, 35-44 years old) and employment types (e.g., full-time, student).

Key Findings
Factors Influencing Work Arrangements:

Employment type: Students, job seekers, and freelancers experience different levels of flexibility.
Work experience: More experienced employees may have more negotiating power over their work setup.
Job satisfaction: Employees in fulfilling jobs are more likely to have flexible arrangements.
Job Satisfaction and Work Arrangements:

The correlation coefficient between JobSat and WorkArrangementNumeric is -0.065555, indicating a very weak negative correlation.
This suggests that changes in work arrangement have little to no impact on job satisfaction in this dataset.
Distribution of Work Arrangements:

Full-time employees in the 18-24 age group are more likely to work in hybrid or in-person arrangements, while remote work is less common.
For those under 18, hybrid work is more common among part-time students, while in-person and remote work are rare.

File Descriptions

BlogPost.ipynb: This Jupyter Notebook contains code, data analysis, and visualizations related to the developer survey. It might be used to generate insights and figures for a blog post.
2024 Developer Survey.pdf: This PDF document includes the full report or summary of the 2024 developer survey results, providing an overview of the findings and key statistics.
README.txt: This text file usually contains information about the project, including instructions on how to use the files, dependencies, and any other relevant details.

survey_results_public.csv: This CSV file contains the raw data collected from the developer survey, including responses from participants.
survey_results_schema.csv: This CSV file probably includes the schema for the survey results, detailing the structure of the data, such as column names and data types.

Licensing, Authors, Acknowledgements
This project used data from Stack Overflow. Special thanks to the contributors and data providers(https://survey.stackoverflow.co/)
https://learn.udacity.com/
