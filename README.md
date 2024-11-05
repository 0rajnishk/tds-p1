# GitHub Users Analysis in Delhi

This project is a data science tool developed as part of a coursework project for **TDS Project 1**. The project focuses on analyzing GitHub users in Delhi, specifically targeting users with more than 100 followers. Using the GitHub API, it retrieves both user and repository data to facilitate in-depth analysis of open-source trends, developer activity, and community engagement within the Delhi region.

## Project Overview

The repository provides an insightful look at GitHub developer dynamics, emphasizing:

- **Data Collection Notebook** (`tds-notebook.ipynb`): A Jupyter Notebook that leverages the GitHub API to retrieve user and repository data.
- **Data Files**:
  - `users.csv`: Detailed information on GitHub users in Delhi with over 100 followers.
  - `repositories.csv`: Data on up to 500 of the latest repositories for each user.
  
This dataset enables exploration of topics like popular programming languages, license preferences, and repository trends within the Delhi-based GitHub community.

## Features and Analysis

The project includes various analyses that uncover insights about the developer community, such as:

1. **Top Users** by follower count and identification of the earliest registered GitHub users.
2. **Popular Licenses and Languages** used across Delhi-based repositories.
3. **Repository Trends**, including correlations between forks and repository longevity.
4. **Community Engagement Factors**: The impact of documentation, open issues, and bio details on user engagement.
5. **User Characteristics**: Common company affiliations, bio lengths, and whether users are available for hiring.

## Data Collection Process

- **Script**: The `tds-notebook.ipynb` notebook employs Python’s `requests` library to query the GitHub API. Each user’s details and repository information are accessed through pagination, ensuring comprehensive data retrieval.
- **Storage**: Collected data is stored in CSV format, with `users.csv` containing user information and `repositories.csv` containing repository details, ready for data analysis.

## Key Findings

### Top Findings

1. **Popular Programming Languages**: JavaScript and Python lead in usage among GitHub users in Delhi, reflecting their widespread appeal for web and data science projects.
2. **Top License Choice**: The MIT License is the most preferred license among these users, encouraging collaboration with its permissive terms.
3. **Correlation between Forks and Repository Longevity**: Repositories with higher fork counts demonstrate better maintenance and continued usage over time.
4. **Bio Length and Follower Count**: Users with more detailed bios generally attract more followers, likely due to perceived engagement and professionalism.
5. **Weekend Repository Creation**: Certain users show a trend toward creating repositories during weekends, hinting at personal or side projects.


## License

This project is licensed under the MIT License, making it freely available for modification and distribution within the terms of this permissive license.
