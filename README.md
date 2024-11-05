GitHub Users Analysis in Delhi
This project is a data science tool developed as part of a coursework project for TDS Project 1. The project focuses on analyzing GitHub users in Delhi, specifically targeting users with more than 100 followers. Using the GitHub API, it retrieves both user and repository data to facilitate in-depth analysis of open-source trends, developer activity, and community engagement within the Delhi region.

Project Overview
The repository provides an insightful look at GitHub developer dynamics, emphasizing:

Data Collection Notebook (tds-notebook.ipynb): A Jupyter Notebook that leverages the GitHub API to retrieve user and repository data.
Data Files:
users.csv: Detailed information on GitHub users in Delhi with over 100 followers.
repositories.csv: Data on up to 500 of the latest repositories for each user.
This dataset enables exploration of topics like popular programming languages, license preferences, and repository trends within the Delhi-based GitHub community.

Features and Analysis
The project includes various analyses that uncover insights about the developer community, such as:

Top Users by follower count and identification of the earliest registered GitHub users.
Popular Licenses and Languages used across Delhi-based repositories.
Repository Trends, including correlations between forks and repository longevity.
Community Engagement Factors: The impact of documentation, open issues, and bio details on user engagement.
User Characteristics: Common company affiliations, bio lengths, and whether users are available for hiring.
Data Collection Process
Script: The tds-notebook.ipynb notebook employs Python’s requests library to query the GitHub API. Each user’s details and repository information are accessed through pagination, ensuring comprehensive data retrieval.
Storage: Collected data is stored in CSV format, with users.csv containing user information and repositories.csv containing repository details, ready for data analysis.
Key Findings
Top Findings
Popular Programming Languages: JavaScript and Python lead in usage among GitHub users in Delhi, reflecting their widespread appeal for web and data science projects.
Top License Choice: The MIT License is the most preferred license among these users, encouraging collaboration with its permissive terms.
Correlation between Forks and Repository Longevity: Repositories with higher fork counts demonstrate better maintenance and continued usage over time.
Bio Length and Follower Count: Users with more detailed bios generally attract more followers, likely due to perceived engagement and professionalism.
Weekend Repository Creation: Certain users show a trend toward creating repositories during weekends, hinting at personal or side projects.
Developer Recommendations
Licensing: Using the MIT License can attract more collaborators, as it’s recognized and permissive.
Documentation: Providing comprehensive documentation and contribution guidelines can boost engagement and contributions.
Community Engagement: Keeping issues open and inviting contributions can foster an active project community.
Repository Structure
README.md: Detailed description of the project, setup instructions, and usage guidelines.
tds-notebook.ipynb: Jupyter Notebook containing the data collection and analysis code.
users.csv: CSV file with user data for GitHub users in Delhi with 100+ followers.
repositories.csv: CSV file with data for up to 500 repositories per user.
How to Run the Project
Clone the Repository:

bash
Copy code
git clone https://github.com/your-username/your-repo-name.git
Set Up Your GitHub API Token:

Replace 'Your Token' in tds-notebook.ipynb with your GitHub API token to enable data access.
Run the Jupyter Notebook:

Execute tds-notebook.ipynb to fetch data and perform analysis.
Ensure required Python packages are installed:
bash
Copy code
pip install requests pandas
View Results:

Collected data is saved in users.csv and repositories.csv.
Additional insights and analysis results are viewable within the notebook cells or can be exported as desired.
Dependencies
Python 3.x
requests library for making API calls to GitHub
pandas library for data handling and analysis
License
This project is licensed under the MIT License, making it freely available for modification and distribution within the terms of this permissive license.
