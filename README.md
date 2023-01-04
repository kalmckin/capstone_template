# DA7-Kala-McKinney-Capstone

Repository for Capstone Project for Nashville Software School Data Analytics Bootcamp.

Executive Summary

As someone who recently went through the agonizing process of trying to buy a home in Nashville, I intend to deep dive into the home-buying trends in the post-Covid world. I am interested in understanding if the difficulty many local buyers are experiencing is stemming from corporations buying homes for rentals, Airbnb purchasing homes to target Nashville’s growing tourism and bachelorette/woo-girl popularity, out-of-state buyers capitalizing on our lower prices/taxes, or something else. 
Additionally, I will try to aggregate this data into a usable format that could potentially help a future homebuyer identify neighborhoods that haven’t been hit as hard and can focus their attention on. 


Motivation

My husband and I began our home-buying journey in early 2021. He was born and raised in Nashville and I’ve lived here for the last 13 years. We had lived in several rentals in East Nashville and were intent on settling our home there as well. The Nashville housing market, however, had other plans. We spent over a year looking for a home to buy and the longer we went, the more expensive things got. Countless drive-buys, 65 official showings, 25 failed offers, and over 6,000 miles driven across Middle TN searching. I understood that COVID and mass buy-outs from companies like Zillow were affecting the market, but wondered why Nashville seemed so hard hit and if other people were experiencing the same struggle we were and what other factors could have contributed. 

Data Question

I think I will find more questions as I explore the data but my initial thoughts are: 
•	How many homes were available per each month in 2021-2022?
•	Does the # of Airbnbs within each neighborhood affect the inventory for residential buyers?
•	Are there more commercially owned homes than resident-owned homes?
•	Were those home purchases immediately turned into rentals?
•	Are those homes being purchased and resold within the same year? i.e. flippers
•	Are the people buying houses in Davidson county from Tennessee or elsewhere?
•	Are there trends that show better months or areas in which to focus your home-buying attention?
•	Are those trends staying consistent into 2022?
•	Are there areas of Nashville with a higher population of Airbnbs that could potentially reduce your home-owner experience or affect your future sale value?

Minimum Viable Product (MVP)

A minimum viable product for this will be a presentation with the intended audience of future native-Nashvillian homebuyers who can use it to make an educated decision about the home they’re purchasing. 

Schedule

1.	Get the Data (11/19/22)
2.	Clean & Explore the Data (12/3/2022)
3.	Create Presentation of your Analysis (12/17/2022)
4.	Internal demos (12/20/2022)
5.	Demo Day!! (1/5/2022)

Data Sources

•	Multiple excel files from https://www.padctn.org/services/recent-sales/#zone_map
•	Multiple excel files from http://insideairbnb.com/get-the-data/
•	Web Scraping https://www.greaternashvillerealtors.org/market-data-monthly/2022/
•	Multiple Excel files from https://data.census.gov/cedsci/table?q=Owner%2FRenter%20%28Householder%29%20Characteristics&g=0500000US47037&tid=ACSDT1Y2021.B07013

Known Issues and Challenges

Explain any anticipated challenges with your project, and your plan for managing them. Be sure to include:

•	The data for the home sales in Davidson county for 2021-2022 are stored across 198 different .xlsx files on the Davidson county assessors website
•	The files are not data intensive, there are just a lot of them. I plan to utilize PowerQuery in Excel to combine all files into one sheet in order to upload. 
•	Excel files on the assessors websites do not include zip code so I need to find a different geojson file in order to create the visuals and maps
•	I am not fully familiar with webscraping and will need to dedicate extra time to scraping the inventory website
•	The Census site is elaborate and confusing. There are no marketable keys in order to join the data so I will have to manually create one in the files.
•	Additionally, there are formatting issues in the headers and values that will have to be removed/cleaned
•	The Airbnb data is keyed by Districts and I am not fully sure what those equate to in the Davidson County designation. I will have to further research what goes where. 

