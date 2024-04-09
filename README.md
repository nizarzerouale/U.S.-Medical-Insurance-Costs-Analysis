# U.S. Medical Insurance Costs Analysis

## Project Overview
This is a Codecademy portfolio project from the Data Scientist career path, that aims to analyze medical insurance costs data to uncover insights into patient demographics and identify factors that significantly influence insurance charges in the U.S. Utilizing Python fundamentals, including CSV data handling and basic statistical analysis, the project investigates various attributes within the `insurance.csv` dataset.

## Objectives
- Analyze patient demographics such as age, sex, BMI, number of children, smoking status, and geographical region.
- Calculate average patient age, the distribution of sexes, unique regions, and average yearly medical insurance charges.
- Determine the correlation between patient age and yearly medical insurance charges.
- Organize patient data into a structured format for easier analysis.

## Technologies Used
- Python
- CSV library for data handling
- Math library for statistical analysis

## Data Overview
The dataset, `insurance.csv`, comprises several columns representing patient attributes:
- Patient Age
- Patient Sex
- Patient BMI
- Patient Number of Children
- Patient Smoking Status
- Patient U.S. Geographical Region
- Patient Yearly Medical Insurance Cost

There are no missing values in the dataset, ensuring a comprehensive analysis.

## Implementation
### Data Loading
A helper function `load_list_data` efficiently loads data from the CSV file into separate lists for each patient attribute.

### Data Analysis
The `PatientsInfo` class encapsulates methods for analyzing patient data:
- `analyze_ages()`: Calculates the average age, age range, and standard deviation.
- `analyze_sexes()`: Counts the number of males and females.
- `unique_regions()`: Identifies unique geographical regions.
- `average_charges()`: Calculates the average yearly medical insurance charges.
- `correlation_between_age_and_charges()`: Determines the correlation between patient age and insurance charges.
- `create_dictionary()`: Organizes all patient data into a dictionary for further analysis.

### Insights
- The analysis provides an overview of patient demographics, highlighting the average age, sex distribution, and regional spread.
- It calculates the average yearly medical insurance charge, offering a baseline for financial analysis.
- A correlation analysis between patient age and yearly charges provides insights into how age influences insurance costs.

## Conclusion
This project demonstrates the power of Python for data analysis, offering valuable insights into the U.S. medical insurance landscape. The findings can help stakeholders understand key factors affecting insurance costs and support informed decision-making in healthcare policy and insurance product development.

## Future Directions
- Extend the analysis to include other factors like BMI, smoking status, and the number of children to identify their impact on insurance charges.
- Employ more advanced statistical methods and machine learning models for predictive analysis.
- Explore data visualization techniques to present findings more intuitively.

