# Olympics Gold Medalists Data Analysis (2000s) using Excel

This repository contains an analysis of Olympic gold medalists data from the 2000s. The analysis explores various factors related to athlete demographics and Olympic performance.

## Files

`olympics_gold_medalists.xlsx`: This Excel file contains the dataset used for the analysis. It includes the raw data and all calculations, descriptive statistics, analysis, and visualizations presented in the associated PDF report. The analysis is organized into separate sheets within the Excel file.
`Data Exploration Mathematics.pdf`: This document provides a detailed report of the data exploration, statistical analysis, and findings. It includes a data dictionary, descriptive statistics, univariate analysis, and visualizations.

## Data Description

The dataset focuses on gold medal-winning athletes from the 2000s Olympic Games (both Summer and Winter).

The dataset includes the following variables:

`UniqueGameID`: Unique identifier for each athlete.  
`Name`: Athlete's name.  
`Sex`: Athlete's gender.  
`Age`: Athlete's age.  
`Height`: Athlete's height (cm).  
`Weight`: Athlete's weight (kg).  
`Team`: Athlete's team name.  
`NOC`: National Olympic Committee (country code).  
`Games`: Year and season of the Olympic Games.  
`Year`: Year of the Olympic Games.  
`Season`: Season of the Olympic Games (Summer or Winter).  
`City`: Host city of the Olympic Games.  
`Sport`: Sport in which the athlete participated.  
`Event`: Specific event within the sport.  
`Medal`: Medal type (all entries are "Gold" in this dataset).  


## Analysis Performed

The analysis in "Data Exploration Mathematics.pdf" includes:

* **Descriptive Statistics:** Calculation of mean, median, mode, standard deviation, etc., for numerical variables like age, height, and weight.
* **Univariate Analysis:** Analysis of individual variables, including:
    * Mean age of athletes by gender.
    * Median height of athletes.
    * Mode of athlete weight.
    * Frequency distribution of athlete age.
    * Count of sports by city.
    * Medal count by the National Olympic Committee (NOC).
    * Medal count by team.
    * Pie chart analysis of wins by season (Summer/Winter).
* **Hypothesis Testing:** Includes odds ratio, risk ratio, chi-square test, t-tests, and ANOVA tests (See "Data Exploration Mathematics.pdf" for details).

## Key Findings (from "Data Exploration Mathematics.pdf")

* Age is a significant factor in winning gold medals, with a decreasing probability of winning after age 30.
* Venue location influences the probability of winning.
* The Summer season has a significantly higher share of wins compared to the Winter season.
## Assumptions (from "Data Exploration Mathematics.pdf")

* The data was obtained from Kaggle and is assumed to be suitable for data science education.
* The dataset is considered complete for the 2000-2010 Olympic Games.
* Units of measurement are known for all variables.

## Usage

To reproduce the analysis:

1.  Download the `olympics_gold_medalists.xlsx` file.
2.  Open the file in Microsoft Excel or a compatible spreadsheet program.
3.  Navigate through the sheets to view the raw data, calculations, and visualizations.
4.  Refer to the `Data Exploration Mathematics.pdf` document for detailed explanations and interpretations.
