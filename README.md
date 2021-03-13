# Data Science Blog Post

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#filedescriptions)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>
This code runs with Python version 3.* and libraries and their respective versions mentioned in *requirements.txt*. Following command can be executed for their installation: </br>
` pip install -r requirements.txt `


## Project Motivation<a name="motivation"></a>
This is an Udacity Nanodegree project. The dataset I chose had statitics of players in top 5 soccer leagues across Europe from year 2014-2015 to 2019-20. Apart from attributes like goals, assists, yellow and red cards,etc, there were some other interesting statistics such as expected goals, expected assists, key passes,etc. 


With the data at hand, I tried to answer following questions:

- Which league has the most attacking defenders across Europe's top 5 league in the last 6 seasons? 
- Which teams outperform their expected goals measure while which ones underperform (and in which season)? How is it related to performance in respective league in that year? Further, which teams constantly outperform their expected goals measure?
- One man army: In a particular season and league, which teams were most dependent on a single player for scoring goals?


## File Descriptions <a name="filedescriptions"></a>
*data* folder consists of csv files containing statisitics of each player in Europe's top 5 soccer league teams from year 2014-15 to 2019-20.

## Results<a name="results"></a>

## Licensing, Authors, Acknowledgements<a name="licensing"></a>
The data was obtained from [Kaggle](https://www.kaggle.com/jashsheth5/indepth-soccer-statistics-xg-xa-and-more). The Gini coefficient analysis is based on ideas presented in [this](https://statsbomb.com/2018/08/introducing-xgchain-and-xgbuildup/) article. Further, I would also like to acknowledge Udacity Data Scientist Nanodegree instructors for providing an opportunity of creating a blog for a data science problem. 