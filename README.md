# T20-project

Recently t20 world cup held in Australia which won by team England. In this Project, We analysing data to give 15 best possible players from tournament to make best possible Team in Tournament

# Dataset

Link:https://github.com/vkhot2023/t20-project/tree/main/t20_csv_files%20original

# Development Process
In this project, we are carrying following steps:

1 Project Statement

2 Data Exploration and Processing

3 DashBoard and Model Generation

4 Data Analysis and Insights

## Project statement

Link:https://github.com/vkhot2023/t20-project/blob/main/project%20statement.docx

## Data Exploration and Processing

Client provide row data Folder with 5 Excel Sheets:
dim_match_summary:45 records  team1,	  team2,	  winner,	  margin,	  ground,	  matchDate,	  match_id

dim_players:219 records name,	team,	image,	battingStyle,	bowlingStyle,	playingRole,	description

dim_players2:219 records  name,	team,	battingStyle,	bowlingStyle,	playingRole,	description

fact_batting_summary:699 records  match,	teamInnings,	battingPos,	batsmanName,	runs,	balls,	4s,	6s,	SR,	out/not_out,	match_id

Data Process according to require condition. Data from Super12 Matches Considers for Model Development

fact_bowling_summary:500 records  match,	bowlingTeam,	bowlerName,	overs	maiden,	runs,	wickets	economy,	0s,	4s,	6s,	wides,	noBalls,	match_id

## DashBoard and Model Generation

Data parsed in Microsoft PowerBI for Model development. Model developes in such way that each data point has data consistency and relationship with respect to selected data point to provide User Required data insights. we developed User friendly Dynamic Dashboard using Microsoft PowerBI tool to check various parameters.

Final 15 Players Dashboard Screenshot:

<img src="https://user-images.githubusercontent.com/115641570/224487057-22c7f525-7eae-429e-9b37-c230d815fbfe.PNG" height="400" width="800" />

Opener Screenshot:

<img src="https://user-images.githubusercontent.com/115641570/224487246-ffec4210-fd7c-4ba0-ad68-82f592fa6397.PNG" height="400" width="800" />

Middle Order Batsmen Screenshot:

<img src="https://user-images.githubusercontent.com/115641570/224487379-eb9c726d-6bb6-40f8-92c6-8249f76c05a1.PNG" height="400" width="800" />

WicketKeeper Screenshot:

<img src="https://user-images.githubusercontent.com/115641570/224487449-2c5880f5-0668-4bad-910f-9233f0160147.PNG" height="400" width="800" />

Finisher Screenshot:

<img src="https://user-images.githubusercontent.com/115641570/224487487-9aa8eeee-949c-4793-b773-6987ffc82f92.PNG" height="400" width="800" />

All Rounder Screenshot:

<img src="https://user-images.githubusercontent.com/115641570/224487579-6bab3416-e454-466a-8845-63ceaa519678.PNG" height="400" width="800" />

Spinner Screenshot:

<img src="https://user-images.githubusercontent.com/115641570/224487839-d51e1a1a-d82b-4d2c-aa24-4b76d3cc1133.PNG" height="400" width="800" />

Fast Bowler Screenshot:

<img src="https://user-images.githubusercontent.com/115641570/224487916-e0492782-366a-49e7-a276-ebc38b855097.PNG" height="400" width="800" />

For Detail Project:https://github.com/vkhot2023/t20-project/blob/main/t20project.pbix

# Data Analysis:

Final 15 Player Squad

https://github.com/vkhot2023/t20-project/blob/main/data%20analysis.docx

## Microsoft PowerBI Link:

https://github.com/vkhot2023/t20-project/blob/main/t20project.pbix

## Project completion

project successfully completed by VISHAL JAGANNATH KHOT
