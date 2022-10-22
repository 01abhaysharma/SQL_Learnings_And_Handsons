# HackerRank Problems part 1

*MS SQL Server*

## Problem 1:

Query all columns for all American cities in the CITY table with populations larger than 100000. The CountryCode for America is USA.
The CITY table is described as follows:

![image](https://user-images.githubusercontent.com/85710889/197353377-856f755d-a74c-4290-8d83-a43a106b7d2b.png)

Solution:

SELECT * FROM CITY WHERE COUNTRYCODE = 'USA' and POPULATION > 100000;

## Problem 2:

Query the NAME field for all American cities in the CITY table with populations larger than 120000. The CountryCode for America is USA.
The CITY table is described as follows:
 
![image](https://user-images.githubusercontent.com/85710889/197353507-61c5c3c7-c0a7-42bc-bd71-5408c4f449bf.png)

Soultion:

SELECT NAME FROM CITY WHERE COUNTRYCODE = 'USA' AND POPULATION > 120000;

## Problem 3:

Query all columns (attributes) for every row in the CITY table.
The CITY table is described as follows:
 
![image](https://user-images.githubusercontent.com/85710889/197353548-7729b6e8-a406-40f7-92d3-c31204afc227.png)

Solution:

SELECT * FROM CITY;

## Problem 4:

Query all columns for a city in CITY with the ID 1661.
The CITY table is described as follows:

![image](https://user-images.githubusercontent.com/85710889/197353604-19de44ca-c091-4cd6-bb02-2dfaf130126a.png)

Solution:

SELECT * FROM CITY WHERE ID = 1661;

## Problem 5:

Query all attributes of every Japanese city in the CITY table. The COUNTRYCODE for Japan is JPN.
The CITY table is described as follows:

![image](https://user-images.githubusercontent.com/85710889/197353656-6e44464c-a392-426a-9b6d-ab971b9db21b.png)

Solution:

SELECT * FROM CITY WHERE COUNTRYCODE = 'JPN';

## Problem 6:

Query the names of all the Japanese cities in the CITY table. The COUNTRYCODE for Japan is JPN.
The CITY table is described as follows:

![image](https://user-images.githubusercontent.com/85710889/197353713-57495afa-8681-4194-baa2-5700d4bcd273.png)

Solution:

SELECT NAME FROM CITY WHERE COUNTRYCODE = 'JPN';



