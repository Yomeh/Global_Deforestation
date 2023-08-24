# INTRODUCTION
![WhatsApp Image 2023-08-23 at 17 12 49](https://github.com/Yomeh/Global_Deforestation/assets/140501792/7885b613-9236-4037-9fc4-0d150849bcd8)
Global deforestation refers to the widespread and ongoing process of clearing or removing forests and trees on a large scale across the world. This is typically done to make way for agriculture, urban development, infrastructure, logging, mining, and other human activities. Deforestation has significant environmental, social, and economic implications, as forests play a crucial role in maintaining biodiversity, regulating the climate, supporting indigenous communities, and providing ecosystem services. Deforestation occurs primarily in areas with large forest areas such as the Amazon Basin of South America, the Congo Basin in Central Africa and Southeast Asia.

# PROBLEM STATEMENT
The objective of the analysis is to get insight into the similar features and characteristics of countries involved in deforestation such as their total land area, forest area, country's income group, and their region. These features and patterns are helpful in helping us determine the country that might be most involved in deforestation and provide insight into the factors that might influence the rate of deforestation in such regions.

# UNDERSTANDING THE DATASET
The dataset provided shows the land area and forest area of each country from 1990 up till 2016, it is made up of 3 tables which are; the forest area, the regions, and the land area. The forest area table consists of 4 columns (country code, country name, year, and the forest area in square kilometers) and 5886 rows of data, The regions table is made up of 4 columns (country name, country code, region and income group) and 219 rows of data, and finally, the land area is made up of 4 columns (country code, country name, year and total land area in square miles) and 5886 rows of data.
- Country code: This column shows the shortcode for each country.
- Country name: This column shows the name of each country.
- Region: This shows the region in which each country is located.
- Year; This shows the land area and forest area for each country between 1990 and 2016.
- Forest area: This shows the forest area for each country in square kilometers.
- Total area: This shows the total area for each country in square miles

# QUESTIONS AND ANALYSIS

**TOTAL NUMBER OF COUNTRIES INVOLVED IN DEFORESTATION**
![Screenshot (58)](https://github.com/Yomeh/Global_Deforestation/assets/140501792/761a45b2-7f2a-43d7-b631-b39454804e97)
Across the globe, we have a total of *218* countries involved in deforestation. The dataset contained multiple instances of each country, so I used the **DISTINCT** function to count only one occurrence of each country from the land area table.

**INCOME GROUP OF COUNTRIES WITH TOTAL AREA RANGING FROM 75,000 TO 150,000**
