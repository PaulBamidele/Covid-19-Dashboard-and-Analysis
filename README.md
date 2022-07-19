  **AIRPLANE CRASHES AND FATALITIES FROM 1908 TO 2009**
  
The dataset contains data of airplane accidents involving civil, commercial, and military transport worldwide from 1908-09-17 to 2009-06-08. It provides information about the history of airplane crashes around the world, the causes, and the death rates.

**PROBLEM STATEMENT**

Airplane crash leads to loss of lives and most of the survivors do live with the negative effects e.g trauma, diabilities etc. it had on them for the rest of their lives. This project hope to enable the readers to know what to do in order prevent airplane crash in the future and give them insights on previous occurrences including the rate of fatality and survival etc.

**PROBLEM OBJECTIVES**

The goal of this project is to provide insights on and provide answers to the following questions:

* Which Country has the highest fatality rate?

* What is the rate of Fatality and Survival?

* What is the type of airplane with the highest occurrence of fatalities and survivals?

* When did the most fatal airplane crash happen? WHat is the number of fatalities and where did it take place?

* Which year has the highest number of Survivors and which one has the highest number of Fatalities per year?

* What is the record of the number of survivors and fatalities per month?

* Compare the sum of passengers aboard, fatalities and survivors by operators including the survival and fatality rates.

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


