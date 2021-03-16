
# Cut through the clutter - data-driven estimation of market value of Soccer players
GitHub repo for Project - 2


#### Description
Soccer is a popular sport and a big business.Important decisions around player valuation are of major concern. Market values have traditionally been estimated by football experts and the process behind crowd judgments is not transparent and estimates are not replicable. As part of my project, I aim to develop a model which will try to replicate the crowd-based estimations of market value and check if the below equations holds good :

**Market Valuation of a Player = Market Information + Player Attributes + Player Statistics/Ability**

As part of the project, I will try to predict the 2017 - Market Valuations based on below features.

#### Features and Target Variables

* Player data -  Height, Age, Weight, Foot(Right/Left),Nation(Citizenship)
* Performance attributes - Position, Matches Played,Match Starts,Goals,Assists,Penalty Kicks,Cards(Yellow/Red)
* Market Information - Wikipedia page views, 2016 - Player Market valuation
* Limits to players in the English Premiership League
* I analyzded 141 players across 20 teams

#### Data Sources - WebScraped using Beautiful Soup
* [transfermarkt](https://www.transfermarkt.us/) - Source for Market Valuations
* [fbref](https://fbref.com/en/)  - Source for Player Statistics and Player Attributes
* Wikipedia pageview Api - To get Wikipedia pageview details for respective players

### EDA 


![](https://github.com/anubhavpar/Project_2/blob/main/Wiki_Views.png)

2016 Market Valuation compared to Wikiepdia views

![](https://github.com/anubhavpar/Project_2/blob/main/Images/Pos.png)

2016 Market Valuations with respect to Player Positions


### Model - Linear Regression

![](https://github.com/anubhavpar/Project_2/blob/main/Images/AVP.png)

Linear Regressions Model Predictions(for 10 Players)


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
* Project_Anubhav.pdf - Presentation slides

#### Potential Clients

 * Football managers and Scouts 


 


