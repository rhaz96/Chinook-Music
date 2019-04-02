# Chinook Music Store Exploration

![image](https://user-images.githubusercontent.com/43581750/55284864-0865fe80-534d-11e9-8c14-3fb4461a37d3.png)

## Introduction

Chinook is a (contrived) music store (but based on real data) that is similar to iTunes.  We have a database provided that
contains information on customer purchases, songs, and albums.  You can read more about Chinook at 
[this](https://github.com/lerocha/chinook-database) repository, which is also where the data originates.   

The objective is to answer business questions pertaining to Chinook's investment strategy and music offerings.

## Getting Started

This is a SQL database, but as mentioned in the [CIA Factbook](https://github.com/rhaz96/CIA-Factbook.git) analysis, R can be 
used to connect to databases to experience the functionality of the ```tidyverse```.  Additional necessary packages
include:

* ```kableExtra```
* ```DBI```
* ```RSQLite```
* ```magrittr```

The database schema is displayed below.

![image](https://user-images.githubusercontent.com/43581750/55284937-73640500-534e-11e9-888b-38d9afb52cf1.png)
