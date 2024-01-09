# Airplane Incidents Analysis

## Overview

This project involves the analysis of a comprehensive dataset detailing the history of airplane crashes and fatalities worldwide from 1908 to 2023. The goal is to derive insights into trends, patterns, and factors contributing to airplane incidents over time.

## Dataset

- **Dataset Source**: [Airplane_Crashes_and_Fatalities_Since_1908_t0_2023.csv](https://www.kaggle.com/datasets/nayansubedi1/airplane-crashes-and-fatalities-upto-2023)
- **Columns**: Date, Time, Location, Operator, Flight #, Route, AC Type, Registration, Aboard, Aboard Passengers, Aboard Crew, Fatalities, Fatalities Passengers, Fatalities Crew, Ground, Summary

## Analysis Process

### 1. Initial Exploration

- Loaded the dataset and reviewed its structure.
- Checked for missing values and handled them appropriately.
- Identified and dropped unnecessary columns for analysis.

### 2. Temporal Analysis

#### 2.1 Yearly Trends

- Converted the 'Date' column to datetime format.
- Created a 'Year' column by extracting the year from the 'Date'.
- Grouped the data by year and analyzed the trends in the number of airplane incidents.

#### 2.2 Seasonal Patterns

- Extracted the month from the 'Date' column and analyzed the seasonal patterns in airplane incidents.

### 3. Geographical Analysis

#### 3.1 Global Distribution

- Grouped the data by location to identify the location with the highest number of airplane incidents.

#### 3.2 Location-specific Factors

- Extracted city information from the 'Location' column and identified cities with a higher incidence of airplane incidents.

### 4. Aircraft and Operator Analysis

#### 4.1 Common Aircraft Types

- Identified the most common aircraft types involved in incidents.

#### 4.2 Operator Patterns

- Analyzed operators with the highest and lowest incident rates.
- Explored trends related to the operator's region or country.

### 5. Fatality Analysis

#### 5.1 Fatalities Over Time

- Examined trends in the number of fatalities over the years.

#### 5.2 Periods with Higher Fatality Rate

- Calculated and analyzed the fatality rate over time.
- Identified specific periods with a higher fatality rate.

### 6. Potential Causes and Factors

#### 6.1 Probable Causes

- Processed and tokenized the 'Summary' column.
- Analyzed the most common probable causes of airplane incidents.

#### 6.2 Temporal Analysis of Probable Causes

- Extended the analysis to identify shifts in predominant causes over time.
- Visualized changes in the most common probable causes over the years.

## Challenges Faced

- Dealing with missing values and deciding on appropriate handling strategies.
- Ensuring proper tokenization and text processing for the 'Summary' column.
- Addressing potential conflicts with duplicate column names during the analysis.

## Conclusions

- Yearly trends suggest fluctuations in the number of airplane incidents, indicating potential factors influencing aviation safety.
- Geographical analysis reveals insights into regions and cities with higher incident rates.
- Common aircraft types and operators associated with incidents are identified.
- Fatality analysis indicates periods with higher fatality rates, prompting further investigation into contributing factors.
- Analysis of probable causes provides valuable insights into recurrent issues, helping inform safety measures.

## Usage

Run the Python scripts for each task in the project. Modify and customize the scripts as needed for specific analyses and visualizations.

## Contributing

Contributions to this project are welcome! Please follow the standard GitHub workflow:

1. Fork the project.
2. Create a new branch.
3. Make your changes and commit them.
4. Create a pull request.

## Author

- Name: [Mohammed Mebarek Mecheter](https://www.linkedin.com/in/mohammed-mebarek-mecheter/)
- Email: mohammedmecheter@gmail.com
