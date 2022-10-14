
# DATA EXPLORATION USING SQL

- Introduction
- Data gathering
- Data assessing
- Data cleaning
- Exploratory Data analysis

## INTRODUCTION 

Data exploration is the first step in data analysis involving the use of data visualization tools and statistical techniques to uncover data set characteristics and initial patterns.

In this SQL project I will exploring the Covid-19 data in MySQL Workbench. In my Workbench, I wrote some of the SQL queries to find hidden pattern and generate some useful insights from the data set.


## DATA GATHERING 

In this phase, two datasets were indicated to be necesary for the analysis.

- Coronavirus (COVID-19) Deaths: This data set was downloaded from https://ourworldindata.org/covid-deaths This dataset contains all deaths resulting from the infection of Covid-19. The dataset contains the following information; Continents, Location, Total Deaths, New Cases, Dates etc.
- Coronavirus (COVID-19) Vaccination: This data set was downloaded from https://ourworldindata.org/covid-Vaccinations This dataset contains Vaccination resulting from the deaths of Covid-19. This dataset contains the following information; Total Vaccination, People Vaccinated, People Fully Vaccinated etc.

## DATA ASSESSING 

For this phase, I had to look at the two datasets both visually and programmatically to be able to notice and assess any possible quality or tidiness issue in the datasets before cleaning them in the next phase. A couple of issues were noted and documented in preparation for the cleaning phase. As with most data set, there were two majoy types of issues with the dataset, tidiniess and quality issues. The documented assessment is given below;

QUALITY ISSUES 

- The date column was extracted and populated wrongly, as some rating were not extracted correctly
- Some columns were found empty; this will result in wrong analysis as no data were found in them.
- Drop unwanted columns that aren't necessary for analysis.

TIDINESS ISSUES

- The file downloaded was saved in a CSV format.
- The two datasets should be merged into one dataset as all the two datasets are part of the same observational unit.
- After documenting the issues that were noted, I proceeded to cleaning the datasets in the next phase.

## DATA CLEANING 
Data cleaning basically involves tackling the quality and tidiness issues that were note in the previous phase - Data assessing. With the use of formulas, functions and loops, most of the issues were cleaned. 

- During the cleaning the datasets, I combined the two into one master dataset (Covid-19.xlsx) and saved it in preparation for analysis and querying.

## EXPLORATORY DATA ANALYSIS 
As the Covid-19 dataset is very big in size and difficult to understand. As a Data Analyst I try to answer some of the question by writing some SQL queries in my workbench to summarize the data and get useful information from the Covid-19 data.

The queries are as follows;

- Select all data from the Covid Death Data Set.
- Specific data from the Covid-19 Data Set (Location, New_cases, Total_deaths etc).
- Comparing Total Cases vs the Population In Nigeria.
- Showing what Percentage Population got Covid in Nigeria.
- Checking Out Countries with Highest Infection Rate as compared Population.
- Displaying Countries with the Highest Death Count per Population.
- Displaying Continents with the Highest Death Count per Population.
- Overall cases across the world.
- Considering the Total Population and Vaccination etc.

## CONCLUSION
This Project is aimed at Exploring the Covid-19 data set across the World to get meaningful information and revelation insights about the data set using SQL.

## FEEDBACK 

If you have any feedback, please reach out to me at donhartly@gmail.com
