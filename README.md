# Assignment-

1. Data Cleaning
Check for missing values in all three datasets and address them.
Remove duplicate rows from each dataset.
Ensure consistency in date formats, IDs, and field names.
2. Data Merging
Merge CookingSessions and OrderDetails using Session ID.
Combine the merged dataset with UserDetails using User ID.
3. Data Analysis
Explore the relationship between cooking sessions and user orders:
Average duration of sessions leading to successful orders.
Rating trends of dishes from CookingSessions and OrderDetails.
Identify popular dishes:
Frequency of each dish in OrderDetails.
Analyze demographic factors:
Explore user age groups and their preferred meal types or dishes.
Geographic trends in cooking and order behavior.
4. Visualizations
Create visualizations to showcase insights:
Bar charts for most popular dishes.
Pie charts for meal type preferences.
Line graphs for order trends over time.
5. Recommendations
Summarize findings in a report.
Provide business recommendations based on data insights.
6. Organizing the GitHub Repository
Structure the repository as follows:

lua
Copy code
|-- README.md
|-- Data/
|   |-- UserDetails.csv
|   |-- CookingSessions.csv
|   |-- OrderDetails.csv
|-- Analysis/
|   |-- data_cleaning.ipynb
|   |-- data_analysis.ipynb
|   |-- visualizations.ipynb
|-- Report/
|   |-- findings_report.pdf
|-- LICENSE

# User Behavior and Order Analysis

## Overview
This project analyzes user behavior, cooking preferences, and order trends using three datasets: `UserDetails`, `CookingSessions`, and `OrderDetails`. It includes data cleaning, merging, analysis, and visualization to derive actionable insights.

## Project Structure
- **Data/**: Contains raw datasets.
- **Analysis/**: Jupyter notebooks for cleaning, analysis, and visualizations.
- **Report/**: Final summary of findings and recommendations.

## Key Findings
- Top 5 popular dishes.
- Demographic factors influencing meal preferences.
- Recommendations for increasing user engagement.

## How to Run
1. Clone the repository: `git clone <repository_url>`
2. Open notebooks in Jupyter or any compatible environment.
3. Review the findings and report in the `Report/` directory.

## License
[MIT License](LICENSE)
