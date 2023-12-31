# Final_Project_Sanbercode

# Background

About the Organization :
HELP International is an international humanitarian NGO committed to fighting poverty and providing basic facilities and assistance to people in underdeveloped countries during disasters and natural calamities.

Issues :
HELP International has managed to raise about $10 million. Now, the CEO of the NGO needs to decide how to use this money strategically and effectively. So, the CEO has to make a decision to choose the country that needs the most help.


Columns
--
1. Negara : Name of the Country
2. Kematian_anak: Child mortality under age 5 per 1000 births
3. Ekspor : Export of goods and services per capita
4. Kesehatan: Total per capita expenditure
5. Impor: Import of goods and services per capita
6. Pendapatan: Net income per individual
7. Inflasi: Measures the annual growth rate of Total GDP
8. Harapan_hidup: The average number of years a newborn child would live if current mortality patterns remained the same
9. Jumlah_fertiliti: The number of children that would be born to each woman if the current age fertility rate remained the same
10. GDPperkapita: GDP per capita Calculated as Total GDP divided by total population. 


# What is in the Project
 1. Exploratory Data Analysis
 2. Data Visualization
 3. Feature Engineering(Clustering)

# Analysis Result
Analysis Bivariate Description
----
There is a strong correlation between 'GDPperkapita' - 'Pendapatan', and 'Kematian_anak - Harapan_hidup'


![Bivariate(GDPperkapita - Pendapatan)](https://github.com/adimasmrid/Sanbercode/assets/125172558/182ca9f1-2886-4f5b-bafe-fdc04361220e)
![Bivariate (Kematian_anak - Harapan_hidup](https://github.com/adimasmrid/Sanbercode/assets/125172558/aea91d6d-eef5-46b6-8b09-db7503d39ebf)

Description
---
The graph above shows the correlation between two interrelated variables, GDPperkapita - Pendapatan, and Kematian_anak - Harapan_hidup.
1. GDPperkapita - Pendapatan = It can be seen that there are several countries that have high 'Pendapatan' and high 'GDPperkapita'.
2. Kematian_anak - Harapan_hidup = It can be seen that there are several countries that have low 'Kematian_anak' and high 'Harapan_hidup.

Analysis Crossing Bivariate Description
---
I have also analyzed two variables that represent social and health conditions, for the following reasons:
1. GDPperkapita = An indicator of a country's prosperity and level of development. The greater the per capita income, the more likely it is that the country has a high level of development and average income of the population. 
2. Kematian_anak = The child mortality rate reflects environmental health conditions that directly affect the level of child health. A high child mortality rate indicates a state of malnutrition, poor personal hygiene.
   
![Crossing Bivariate (Kematian_anak - GDPperkapita)](https://github.com/adimasmrid/Sanbercode/assets/125172558/38991a98-174f-44f7-aa66-7b29c47b0c97)


Description
---
The graph shows that there are several countries that have high child mortality rates and low GDP per capita. This shows that prosperity and development levels are still relatively low, which is one of the factors that cause a poor hygiene and health environment, resulting in high child mortality rates.


# Machine Learning Model Result (Clustering
There are 3 clusters that categorize groups of countries ranging from poor countries, developing countries, and developed countries.

![GDPperkapita,   Pendapatan](https://github.com/adimasmrid/Sanbercode/assets/125172558/34fb55b3-453b-4ca2-937f-3c9570a2443c)  ![Harapan_hidup,   Kematian_anak](https://github.com/adimasmrid/Sanbercode/assets/125172558/171c7585-8ef0-410d-aa51-01204edfd14e)



There are several clusters that classify countries based on GDP per capita, income, life expectancy, and child mortality. 

0. Cluster 0 = It indicates a low value owned by some countries, it shows that some of these countries are underdeveloped countries in terms of underdevelopment of economic conditions, and health.

1. Cluster 1 = It indicates a medium value owned by some countries, it shows that some of these countries include developing countries in terms of economic conditions, and health

2. Cluster 2 = It indicates a medium value owned by several countries, it shows that this country is a developed country in terms of economic conditions, and health.


# Conclusion
Since Help International is an international humanitarian NGO committed to fighting poverty and providing basic facilities and assistance to people in underdeveloped countries during disasters and natural calamities, the main focus countries are in cluster 0, as follows 


![Final_data](https://github.com/adimasmrid/Sanbercode/assets/125172558/7e3c3649-89ed-42c6-bb99-329e573bf70d)


Based on the heat map that has been presented, there is a ranking of countries of concern for
areas that need assistance, as follows:
1. Central African Repbulic
2. Congo, Dem. Rep.
3. Niger
4. Sierra Leone
5. Haiti
6. Guinea - Bissau
