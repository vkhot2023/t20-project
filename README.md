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

Above Document will provide detail analysis of each player and his selection process.

## Microsoft PowerBI Link:

https://github.com/vkhot2023/t20-project/blob/main/t20project.pbix

## Project completion

project successfully completed by VISHAL JAGANNATH KHOT
