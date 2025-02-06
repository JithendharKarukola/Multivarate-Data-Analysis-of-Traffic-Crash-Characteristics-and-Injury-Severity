# Traffic Crash Characteristics and Injury Severity Analysis in San Jose

This repository contains the code and analysis for a study examining the relationship between traffic crash characteristics and injury severity in San Jose, CA.  The analysis uses a dataset of over 25,000 crash records to explore factors contributing to different levels of injury (minor, moderate, and fatal).

## Project Overview

This project uses multivariate statistical methods to analyze traffic crash data. The key objectives are:

* Identify factors associated with different injury severity levels.
* Explore relationships between crash characteristics (e.g., speeding, hit-and-run, location) and injury outcomes.
* Develop models to predict injury severity based on crash characteristics.
* Provide insights for urban planners and policymakers to improve traffic safety.

## Data

The dataset used in this analysis contains records of traffic crashes in San Jose.  It includes information on crash characteristics (e.g., time of day, location, weather conditions), vehicle information, and injury details.  Due to privacy concerns, the raw dataset is not included in this repository.  A synthetic or anonymized version of the data, or a description of the data structure, might be made available upon request, depending on data sharing agreements.

## Analysis Methods

The analysis involved several stages:

1. **Data Cleaning and Preprocessing:** The raw data was cleaned and preprocessed, including handling missing values, recoding variables, and transforming data as needed.

2. **Descriptive Statistics:** Descriptive statistics were calculated to summarize the data and identify initial trends.

3. **Regression Modeling:** Regression models were developed to predict injury severity based on crash characteristics.

4. **Factor Analysis:** Factor analysis was used to reduce the dimensionality of the data and identify underlying factors contributing to crashes.

5. **Cluster Analysis:** Cluster analysis was performed to group crashes with similar characteristics.

## Repository Contents

* `data/`:  (Placeholder -  Raw data not included.  May contain a data dictionary or a small sample dataset).
* `code/`: Contains the SAS code used for the analysis (`crash_analysis.sas`).
* `outputs/`: Contains the results of the analysis, including model outputs, tables, and figures.  (e.g., `regression_results.txt`, `cluster_profiles.csv`).
* `reports/`: Contains reports or presentations summarizing the findings. (e.g., `traffic_crash_analysis_report.pdf`).
* `README.md`: This file.

## Software

* SAS

## How to Run the Code

1. Clone the repository: `git clone https://github.com/your-username/traffic-crash-analysis.git`
2. Install SAS.
3. Place the (appropriately anonymized or sample) data file in the `data/` directory. Adjust the file paths within the SAS code as needed.
4. Navigate to the `code/` directory and run the SAS code (`crash_analysis.sas`).

## Results

The results of the analysis are available in the `outputs/` directory.  Key findings include:  (Summarize 2-3 key findings here).

* *Finding 1:*  (e.g., Crashes at intersections are more likely to result in moderate or severe injuries.)
* *Finding 2:*  (e.g., Speeding is a significant contributing factor to fatal crashes.)
* *Finding 3:* (e.g.,  Specific weather conditions are associated with a higher incidence of certain types of crashes.)

## Contributing

Contributions are welcome. Please open an issue or submit a pull request.
