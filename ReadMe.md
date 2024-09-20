# ReadMe
Author: Danyang Zhang
# Class 1 Survey Analysis Project
## Project Description
This project is designed to analyze survey data from students at Brown School, collected during the Fall semester of 2024. The objective is to explore students' preferences, habits, and backgrounds using statistical techniques and visualizations. This comprehensive analysis aims to reveal insights into various aspects of student life and their academic environment.

## Code Description
The project includes an R Markdown file named `class 1 survey demo.Rmd`, which encompasses the following functionalities:
- **Data Importation**: Survey data is imported from a specified GitHub repository, ensuring a reproducible and accessible dataset source.
- **Data Cleaning and Preprocessing**: The dataset undergoes several preprocessing steps, such as renaming variables for clarity, handling missing or unusual values, and converting data types for appropriate analysis.
- **Descriptive Statistics**: The script calculates and displays the number of observations and variables in the dataset. It also assesses the data structure by identifying the types of variables (factor, integer, numeric, character).
- **Advanced Data Handling**: Specifically focuses on date-related variables by checking for anomalies in birth dates and months, correcting these, and computing median values.
- **Seasonal Analysis**: A new variable representing the meteorological season of each respondent's birth month is created and validated against the data.
- **Visualization and Further Analysis**: The distribution of coding experience among the respondents is analyzed and visualized through histograms. This section provides a deeper look into the students' technical skills.

## Dataset Description
The dataset, named `Class 1 Survey Fall 2024_di.csv`, includes responses from a diverse group of students. It features a variety of variables, such as:
- Preferences (pets, food, drinks)
- Habits (daily routines, favorite seasons)
- Academic and personal background (program of study, area of specialization, level of comfort with statistical software)
- Demographic information (birth dates, country, state, city)

## Installation and Usage Instructions
- Ensure that R and RStudio are installed on your computer.
- Required R packages include `dplyr`, `ggplot2`, `tidyr`, `readr`, and `lubridate`. Install these packages using R commands such as `install.packages("dplyr")`.
- Open the `.Rmd` file in RStudio and execute the code chunks sequentially to reproduce the analysis.

## Dependencies
This project requires the following R packages for data manipulation, analysis, and visualization:
- `dplyr`: For data manipulation
- `ggplot2`: For creating visualizations
- `tidyr`: For tidying the data
- `readr`: For reading CSV data
- `lubridate`: For handling date variables

## Additional Notes
This analysis was conducted as part of ADA course at Washington University in St. Louis. All personal information within the dataset has been anonymized in accordance with ethical guidelines provided in the course syllabus, ensuring that the data is used strictly for educational purposes.
Contributors can fork the repository, make proposed changes, and submit a pull request for review. Please ensure that all modifications adhere to the existing coding style and that new features are accompanied by descriptive comments.

