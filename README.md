# Udacity Exploratory Data Analysis
### What are the factors prolonging our longevity? Exploratory data analysis and data modeling.

## Task Description: 
The task of this project was to choose one of the Udacity-curated datasets and conduct data analysis using Python libraries. 

## The Aim of the Project: 
The aim of my project was to investigate the relationships between life expectancy (the dependent variable, DV) and specific life expectancy indicators (independent variables, IV). The analyses were performed separately for countries representing the most and the least developed areas of the world to check for the eventual discrepancies in indicators' significance. 

## Conducted Steps:
1. **Data Wrangling** (the aim of this section was the functional preparation of the data for further exploratory and regression analyses):
* data gathering from the database
* general visual and programmatic assessment of the data frames
* data cleaning: filling in the null values, merging multiple data frames together
2. **Exploratory Data Analysis** (the aim of this section was to increase the quality of the data frame by dealing with outliers, assumptions' checking (linearity), detecting the type of relationships between DV and IV): 
* data visualization including a longitudinal overview of IV 
* bar plots 
* KDE plots 
* scatter plots of calculated means and standard deviations
3. **Statistical Analyses** (the focus of this section laid on a statistical investigation of the relationship between life expectancy and its indicators, with detection of the best-fit model as end goal): 
* by using linear regression library of sklearn,  I calculated the values of the coefficients for all IV as well as R-squared
* next, I compare those results with analyses done using the OLS model in statsmodel library. To choose the model that fits data the best I defined a function, calculating the RSS and R-squared for all possible combinations of IV (32). 
4. **Discussion**: In the last section I summarized my finding and described the major limitations of my analyses. 


