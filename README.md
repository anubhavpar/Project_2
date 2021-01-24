# Project-2
GitHub repo for Project - 2

# Project-2 : Cut through the clutter - data-driven estimation of market value of Soccer players

#### Description
Soccer is a popular sport and a big business.Important decisions around player valuation are of major concern. Market values have traditionally been estimated by football experts and the process behind crowd judgments is not transparent and estimates are not replicable. As part of my project, I aim to develop a model which will try to replicate the crowd-based estimations of market value and check if the below equations holds good :

Market Valuation of a Player = Market Information + Player Attributes + Player Statistics/Ability

As part of the project, I will try to predict the 2017 - Market Valuations based on below features.

#### Features and Target Variables

* Player data -  Height, Age, Weight, Foot(Right/Left),Nation(Citizenship)
* Performance attributes - Position, Matches Played,Match Starts,Goals,Assists,Penalty Kicks,Cards(Yellow/Red)
* Market Information - Wikipedia page views, 2016 - Player Market valuation
* Limits to players in the English Premiership League
* I analyzded 141 players across 20 teams

#### Data Sources
* [transfermarkt](https://www.transfermarkt.us/) - Source for Market Valuations
* [fbref](https://fbref.com/en/)  - Source for Player Statistics and Player Attributes
* Wikipedia pageview Api - To get Wikipedia pageview details for respective players


#### Tools Used (e.g., Scrapy, Seaborn, etc.)
* Beautiful Soup 
* Selenium
* Pandas
* Pickle
* Wikipedia - pageviewapi
* Numpy
* Seaborn, Matplotlib
* Statsmodels 
* Sklearn - LinearRegression, Ridge, Lasso, CV, KFlold, StandardScaler,Polynomial Feature

#### File Contents :
* fbref.ipynb - Please refer to this file for the consolidated code for Project_2
* Valuation.ipynb - Supporting code(which I eventually moved to fbref.ipynb)
* Project_Anubhav.pdf - Presentation slides

#### Potential Clients

 * Football managers and Scouts 

#### Questions we might answer for clients using data

 * What are the key parameters which define market value of a player?
 * What parameters define player performance  ?
 * How do we factor in player popularity to the calculation?
 * How close were my predictions ?

 


