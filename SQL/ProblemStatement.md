# ๐๐Problem Statement: SQL
![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)

As a data analysis intern, you have to analyze sports data for a client. You are given two datasets related to IPL (Indian Premier League) cricket matches. One dataset contains ball-by-ball data and the other contains match-wise data. You have to import the datasets into an SQL database and perform the tasks given in this assignment to find important insights from this dataset.

## ๐ About the Data:
**IPL_Ball:**
The first CSV file is for ball-by-ball data and it has information of all the 193468 balls bowled between the years 2008 and 2020. It has 17 columns and below is the details of those 17 columns:

|Column title    |Description                         |
|:---------------|:-----------------------------------|
|id              |Unique Match ID as per ESPNcricinfo |
|inning          |Inning number                       |
|over            |Over Number in an inning            |
|ball            |Ball Number in an over              |
|batsman         |Batsman on strike                   |
|non_striker     |Batsman at non-striker end          |
|bowler          |Bowler                              |
|batsman_runs    |Runs off Bat                        |
|extra_runs      |Extra runs                          |
|total_runs      |Total runs scored                   |
|is_wicket       |Is the delivery a wicket?           |
|dismissal_kind  |Type of dismissal                   |  
|player_dismissed|Player who got dismissed            |
|fielder         |Fielder involved in the dismissal   |
|extras_type     |Type of extras                      |
|batting_team    |Team to whih batsman belongs        |
|bowling_team    |Tem to which bowler belongs         |

**IPL_Matches:**
The second file contains match-wise data and has data of 816 IPL matches. This table has 17 columns and below is a short description of the columns in this table:

|Column title    |Description                                 |
|:---------------|:-------------------------------------------|
|id              |Unique Match ID as per ESPNcricinfo         |
|city            |City in which stadium is located            |
|date            |Date on which match is held                 |
|player_of_match |Player awarded with best performance        |
|venue           |Stadium name                                |
|neutral_venue   |Is the venue neutral(not a homeground)      |
|team1           |Team 1                                      |
|team2           |Team 2                                      |
|toss_winner     |Decision of the toss winner                 |
|winner          |Match winning team                          |
|result          |Result base on victory by runs or by wickets|
|reault_margin   |Margin of wickets or runs                   |
|eliminator      |Was a superover bowled or not               |
|method          |was a DL(Duckworth Lewis) method applied    |
|umpire1         |First umpire                                |
|umpire2         |Second umpire                               |

## โ Tasks to do:
***Write queries in SQL for the following tasks:***

|Task|โณ๏ธ|Description|
|:--:|:-:|:-|
|1|๐ณ|Create a table named โmatchesโ with appropriate data types for columns|
|2|๐ณ|Create a table named โdeliveriesโ with appropriate data types for columns|
|3|๐ณ|Import data from CSV file โIPL_matches.csvโ attached in resources to โmatchesโ|
|4|๐ณ|Import data from CSV file โIPL_Ball.csvโ attached in resources to โdeliveriesโ.|
|5|๐ณ|Select the top 20 rows of the deliveries table.|
|6|๐ณ|Select the top 20 rows of the matches table.|
|7|๐ณ|Fetch data of all the matches played on 2nd May 2013.|
|8|๐ณ|Fetch data of all the matches where the margin of victory is more than 100 runs.|
|9|๐ณ|Fetch data of all the matches where the final scores of both teams tied and|
|||order it in descending order of the date.|
|10|๐ณ|Get the count of cities that have hosted an IPL match.|

If you want to analyze data further you can write your own queries.

## ๐ Datasets:

***IPL_Ball Dataset:***
https://drive.google.com/file/d/1It3JnQPpNHCHoZyB6xLyTCP6prrzE3p-/view

***IPL_Matches Dataset:***
https://drive.google.com/file/d/18GFAORe6kWU6UQxNXSgoOofR9h8dZ7wU/view
