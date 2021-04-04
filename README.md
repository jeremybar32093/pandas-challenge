# pandas-challenge
### This repository contains a jupyter notebook script (/HeroesOfPymoli/HeroesOfPymoli.ipynb) performing an analysis based off of a video game purhase dataset.

The source data is of the following format:
```csv
0,Lisim78,20,Male,108,"Extraction, Quickblade Of Trembling Hands",3.53
1,Lisovynya38,40,Male,143,Frenzied Scimitar,1.56
2,Ithergue48,24,Male,92,Final Critic,4.88
3,Chamassasya86,24,Male,100,Blindscythe,3.27
4,Iskosia90,23,Male,131,Fury,1.44
```

Based off of this source dataset, the following analyses are performed using **pandas dataframes**:
### Player Count

* Total Number of Players

### Purchasing Analysis (Total)

* Number of Unique Items
* Average Purchase Price
* Total Number of Purchases
* Total Revenue

### Gender Demographics

* Percentage and Count of Male Players
* Percentage and Count of Female Players
* Percentage and Count of Other / Non-Disclosed

### Purchasing Analysis (Gender)

* The below each broken by gender
  * Purchase Count
  * Average Purchase Price
  * Total Purchase Value
  * Average Purchase Total per Person by Gender

### Age Demographics

* The below each broken into bins of 4 years (i.e. &lt;10, 10-14, 15-19, etc.)
  * Purchase Count
  * Average Purchase Price
  * Total Purchase Value
  * Average Purchase Total per Person by Age Group

### Top Spenders

* Identify the the top 5 spenders in the game by total purchase value, then list (in a table):
  * SN
  * Purchase Count
  * Average Purchase Price
  * Total Purchase Value

### Most Popular Items

* Identify the 5 most popular items by purchase count, then list (in a table):
  * Item ID
  * Item Name
  * Purchase Count
  * Item Price
  * Total Purchase Value

### Most Profitable Items

* Identify the 5 most profitable items by total purchase value, then list (in a table):
  * Item ID
  * Item Name
  * Purchase Count
  * Item Price
  * Total Purchase Value

Lastly, some key observations are noted at the end of the jupyter notebook file.
