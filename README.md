# T20-project

Recently the T20 world cup was held in Australia which was won by Team England. In this Project, We analyzed T20 world cup data to give 15 best possible players from the Tournament to make the best possible Team in the Tournament.

## Dataset

Raw Dataset:https://github.com/vkhot2023/t20-project/tree/main/t20_csv_files%20original

## Development Process
We are functioning following 4 steps to complete this project:

* Project statement
* Data Exploration
* Dashboard Development
* Data Analysis

## Project statement

Link:https://github.com/vkhot2023/t20-project/blob/main/project%20statement.docx

## Data Exploration 

Client provide row data Folder with 5 Excel Sheets:

dim_match_summary:45 records  team1,	  team2,	  winner,	  margin,	  ground,	  matchDate,	  match_id

dim_players:219 records name,	team,	image,	battingStyle,	bowlingStyle,	playingRole,	description

dim_players2:219 records  name,	team,	battingStyle,	bowlingStyle,	playingRole,	description

fact_batting_summary:699 records  match,	teamInnings,	battingPos,	batsmanName,	runs,	balls,	4s,	6s,	SR,	out/not_out,	match_id

fact_bowling_summary:500 records  match,	bowlingTeam,	bowlerName,	overs	maiden,	runs,	wickets	economy,	0s,	4s,	6s,	wides,	noBalls,	match_id

Data Process according to require condition. Data from Super12 Matches Considers for Model Development

## DashBoard Development

Data parsed in Microsoft PowerBI for Model development. The model develops in such a way that each data point has data consistency,and data relationship remains intact. We developed User-friendly Dynamic Dashboard using the Microsoft PowerBI tool to check various parameters.

Final 15 Players Dashboard Screenshot:

![n8](https://user-images.githubusercontent.com/115641570/228435660-e726039b-f8f8-47c4-94fc-47b80f549a27.PNG)

Opener Screenshot:

![n1](https://user-images.githubusercontent.com/115641570/228433651-0cb65a06-9cd0-4c70-a377-151a6bb097bf.PNG)

Middle Order Batsmen Screenshot:

![n2](https://user-images.githubusercontent.com/115641570/228438261-2f0372da-d975-4320-985c-7a9f76ab97a3.PNG)

WicketKeeper Screenshot:

![n3](https://user-images.githubusercontent.com/115641570/228434107-db53ae40-b30b-4ebe-9236-22e1a8fbbd24.PNG)

Finisher Screenshot:

![n4](https://user-images.githubusercontent.com/115641570/228434448-cf9f844f-63c0-4faa-83e9-4bce580316b3.PNG)

All Rounder Screenshot:

![n5](https://user-images.githubusercontent.com/115641570/228435402-f5a151da-5416-42d3-aa2f-da2ffcead408.PNG)

Spinner Screenshot:

![n6](https://user-images.githubusercontent.com/115641570/228434678-a8155bb9-8be1-4387-b859-3f8e08cfa67d.PNG)

Fast Bowler Screenshot:

![n7](https://user-images.githubusercontent.com/115641570/228434789-ac6da9c6-9f17-434e-85cd-f8908202b955.PNG)

For Detail Project:https://github.com/vkhot2023/t20-project/blob/main/t20project.pbix

# Data Analysis:

Final 15 Player Squad

https://github.com/vkhot2023/t20-project/blob/main/data%20analysis.docx

Above Document will provide detail analysis of each player and his selection process.

## Microsoft PowerBI Link:

https://github.com/vkhot2023/t20-project/blob/main/t20project.pbix

## Project completion

project successfully completed by VISHAL JAGANNATH KHOT
