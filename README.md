  **COVID 19 Analysis and Visualisation from 2020 - 2022**
  
The dataset on COVID 19 was provide by Oyinbooke Olanrewaju during the #NG30daysoflearning programme that was organised by Microsoft. The dataset contains data about the various countries we have in the world, confirmed cases of COVID-19 in the countries, recovered cases, death cases, the latitutde and longitude of these countries.  

**PROBLEM STATEMENT**

Coronavirus disease 2019 (COVID-19) is a contagious disease caused by a virus, the severe acute respiratory syndrome coronavirus 2 (SARS-CoV-2). The first known case was identified in Wuhan, China, in December 2019.The disease quickly spread worldwide, resulting in the COVID-19 pandemic. This Pandemic led to a global lockdown all over the world and it affected lot of lives, careers and businesses. Due to the level at which the disease is contagious, many people were affected and some of them lost their lives while some recovered. 

**PROBLEM OBJECTIVES**

The goal of this project is to provide insights on and provide answers to the following questions:

* The Top 5 countries with the highest confirmed cases of COVID-19 and also with the lowest confirmed cases of COVID-19

* Countries with the highest death cases as a result of COVID 19

* What year was the highest case of COVID-19 confirmed?

* What year was the highest death case as a result of COVID 19 recorded?

* What is the total confirmed cases of COVID-19 recorded from 2020 -2021?

* What is the total death rate from 2020 to 2022?

* What is the total death cases and recovered cases of COVID 19 recorded within those years.

* What month(s) has the highest confirmed cases and death cases of COVID-19 when filtered by year?

**DATA SOURCING**

This data was provided by Mr. Oyinbooke Olanrewaju @theoyinbooke after the completion of the 30 days of learning programme. The link to the data is provided below;

https://raw.githubusercontent.com/theoyinbooke/30Days-of-Learning-Data-Analysis-Using-Power-BI-for-Students/main/Airline%20Project/Airplane_Crashes_and_Fatalities_Since_1908.csv

The data is imported as a CSV file to Excel from web by clicking on **Get Data** under data tab, click on other sources and then from WEB.

**DATA TRANSFORAMTION**

After the data was imported into Excel from web, it was then transformed using Power query. Exploration and Observation of the dataset was done in order to know the state of the dataset and since it was found to be dirty, I started with cleaning the data by ensuring it is correct, completely free of errors, outliers and special characters.I also checked for duplicates and changed each variable to their appropriate data type.

Using text after delimiter function in Power Query(Excel), I extracted the countries from Location and I noticed that they mostly included states instead of countries especially for USA, also spelling mistakes, repetitive words. For the states in USA I replaced them with USA for the sake of uniformity and easy visualisation and storytelling and it was done by right-clicking on the column that consists of the states and select replace values, each states are replaced with USA.

In each of the columns; for Variables whose data type is Text, blank rows or null rows are replace with Unknown while for variables whose data type is number, blank rows or null are replaced with 0

_**POWER BI**
Imported the dataset into PowerBI, using Power query made some modifications:

Realized that some special characters were still present, used “replace values” to remove them.
Added a Year ,Time, month column
1. Used the ‘Switch’ function in DAX to categorize the months to their respective seasons

Winter — December, January and February.
Spring — March, April and May.
Summer — June, July and August.
Autumn — September, October and November.
2. Created measures for the required parameters i needed: such as Total fatalities, total passengers aboard, the deaths caused by weather for the peak years, fatality rate etc. (.pbix file available upon request)

Visualization

The dataset is based on fatality, hence decided to go with the color red for the hex colors: #FF000, #FF5252, #FFBABA #FF7B7B.

I also wanted the map visual to be unique, did some research and I found this video on YouTube, check it out here . YouTube is a university on its own ☺️.

My Dashboard


Follow me on my Socials:

LinkedIn

Twitter :@Fehintiti

My Portfolio

Feel free to drop a comment if you have any question.

Thanks for reading and kindly click on the clap icon below!








































Findings and Recommendation


