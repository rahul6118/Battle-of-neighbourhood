# notebooks
The Battle of Neighbourhoods
Introduction
New Delhi is the capital city of India. It is a part of the city of Delhi’s 11 districts. The city itself has a population of 257,803. However, the much larger metro area has a population that exceeds 26 million.

New Delhi are used interchangeably to refer to the National Capital Territory of Delhi (NCT), these are two distinct entities, with New Delhi forming a small part of Delhi. The National Capital Region is a much larger entity comprising the entire NCT along with adjoining districts in neighboring states.

The official language of New Delhi and the one that is most widely spoken is Hindi. However, English is also spoken as a formal language within businesses and government agencies. Over last decades it is continuously grow because of the city’s important role in government and commercial business.

With it’s diverse culture , comes diverse food items. There are many restaurants in New Delhi City, each belonging to different categories like Chinese , Italian , French etc. So as part of this project , we will list and visualise all major parts of New Delhi City .

Questions that can be asked using the above mentioned datasets
What is best location in New Delhi City for Chinese Cuisine ? Which areas have large number of Chinese Resturant Market ? Which all areas have less number of resturant ? Which is the best place to stay if I prefer Chinese Cuisine ? What places are have best restaurant in New Delhi?

Data
For this project we need the following data :

New Delhi Resturants data that contains list Locality, Resturant name,Rating along with their latitude and longitude. Data source : Zomato kaggel dataset Description : This data set contains the required information. And we will use this data set to explore various locality of new delhi city. Nearby places in each locality of new delhi city. Data source : Fousquare API Description : By using this api we will get all the venues in each neighborhood.

Approach
Collect the new delhi city data from Zomato kaggel dataset Using FourSquare API we will find all venues for each neighborhood. Filter out all venues that are nearby by locality. Using aggregative rating for each resturant to find the best places. Visualize the Ranking of neighborhoods using folium library(python)

