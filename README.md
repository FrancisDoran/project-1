# project-1
This is my repository for project 1
Project Proposal

Title: "Voting Behavior Analysis Among Oaklanders"

Team Member: Francis Doran

Project Description/Outline:

This project aims to analyze the factors that influence voting behaviors in Oakland residents. By examining voting data and responses from the American Community Survey, we intend to identify and understand significant correlations that may exist between demographic, economic, and social factors and the tendency to vote or abstain.

Our analysis will specifically look at attributes like age, income, level of education, race, and marital status, among other variables, to identify any potential trends or patterns in the voting behavior of Oakland residents. The outcome of this project will provide valuable insights into voter demographics and behavior and could be instrumental in informing future civic engagement campaigns, political strategy, and public policy.

Research Questions to Answer:

What factors significantly affect the likelihood of an Oakland resident to vote or not vote?
Is there a correlation between socioeconomic status and voting behavior among Oakland residents?
How does the level of education influence the voting behavior of residents?
Is there a significant relationship between age, race, or marital status and the voting patterns of Oakland residents?
Datasets to be Used:

The American Community Survey from the U.S Census Bureau
This is availiable on the web from data.census.gov
Voting and address dataset from the Oakland Public Ethics Commission
This is a private dataset I have access to through my internship and I have cleared this with my boss.
Rough Breakdown of Tasks:

Data Acquisition: Procure the necessary datasets from the American Community Survey and the Oakland Public Ethics Commission.

Data Anonymization: To respect privacy and abide by ethical standards, we will replace all names with unique identifiers and street addresses with their corresponding census tracts.

Data Cleaning and Preprocessing: This includes handling missing data, outliers, and unnecessary variables to prepare the datasets for analysis.

Data Integration: Merge the two datasets for a comprehensive dataset ready for analysis. This involves aligning common identifiers like the unique identifiers and census tracts.

Exploratory Data Analysis: Investigate the data to understand the distribution, trends, and patterns.

Statistical Analysis: Implement statistical tests to identify significant correlations and answer research questions.

Data Visualization: Create intuitive graphs and charts to represent the findings.

Report Writing: Document the project process, methodologies, findings, and conclusions.

Presentation: Asemmble visualization in a sensical way to tell the story of the data.
<<<<<<< HEAD

Voter Demographics & Behavior Analysis
This repository contains a Python script that merges voting data with census and ACS data on the census tract level. It allows for the exploration and analysis of voter registration, demographics, and voting behavior across different geographic and demographic groups.

Overview
The script reads and processes several data files containing voter registration and turnout data and census tract level demographic data. It cleans and merges these datasets and generates new variables of interest. The output of the script is a merged data file that can be used for statistical analysis.

How to Use
Ensure that Python 3 and necessary libraries (requests, pandas, numpy, matplotlib, scipy.stats) are installed on your computer.

Place your voter data and census data in the correct directories. Update the paths in the script as necessary.

You will need to obtain your own voter data as it contains the personal information of private individuals, you can request the voter file data from the City of Oakland if you can justify it's use and don't publish the personal info.

Run the script.

Project Structure
The script first downloads and saves geocoding data from the Census Bureau for each voter in the voter file using the Census Bureau's batch geocoding API.

The script then merges the voter file with the geocoding results, calculates voters' ages, and filters down to census tracts with more than 100 registered voters.

The script generates several variables of interest, including the total number of voters in each tract, the median voter age in each tract, and the average voter participation rate in each tract.

The script merges the voter data with demographic data from several tables in the 2020 Decennial Census and the 2021 ACS 5-Year Estimates.

The script generates several additional variables of interest based on the merged data, including percentages of the population with limited English proficiency, poverty rates, and educational attainment levels.

The script then creates a correlation matrix and various summary statistics for differnt population from which one can create graphs.

Libraries Used
requests : Used for making HTTP requests to the Census Bureau's geocoding API.
pandas : Used for data manipulation and analysis.
numpy : Used for numerical computations.
matplotlib : Used for creating static, animated, and interactive visualizations in Python.
scipy.stats : Used for statistical computations.
Data Used
The script uses voter data, geocoding data from the Census Bureau, and data from the 2020 Decennial Census and the 2021 ACS 5-Year Estimates.

The script expects the voter data to be in a CSV file with a specific format. The required format includes columns for voter ID, voter address, and voter demographics and voting history.

The script also expects the census data to be in specific tables from the 2020 Decennial Census and the 2021 ACS 5-Year Estimates. The required tables include data on total population, age distribution, race distribution, English proficiency, poverty status, and educational attainment.

Output
The script out puts various csv's throughout the proccess allowing one to effectively view these very large datasets.
findings.txt is my write up about the project and my conclusion, presentation.odp is my powerpoint, /census and /acs are just data from the census bureau, '/Censored data' is where the main project is it's censored since the voter info and api request and response are all gone, but if you put some real addresses in it should all still work, and the anonymized (which is the useful data anyway) is all still there.

Thanks.
=======
>>>>>>> 57b52ac7397df6b368e7c552f04c9a5c15130996
