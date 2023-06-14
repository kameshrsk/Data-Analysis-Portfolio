# Project - T20 World Cup Data Analysis Portfolio [https://github.com/kameshrsk/Data-Analysis.git]

This repository contains my data analysis project on the recent T20 World Cup, where the goal was to select the best 11 players and form a team. The project involved gathering data, cleaning it, and performing analysis using Power BI.

## Problem Statement

The objective of this project was to analyze the performance of players in the T20 World Cup and select the best 11 players to form a team. The analysis considered various factors such as batting average, strike rate, economy rate, and wickets taken by bowlers to identify the most suitable players for different roles in the team.

## Data Gathering

To gather the required data, I utilized the Cricinfo website and employed web scraping tools like Octoparse and Parsehub. I collected data from multiple sources, resulting in four different CSV files. These files included the following:

1. Summary of every match
2. Scoreboard of each match
3. Batsmen profiles and performance
4. Bowlers profiles and performance

## Data Cleaning

Upon obtaining the data, I performed data cleaning to ensure its quality and consistency. The cleaning process involved several steps using Power Query in Power BI. Some of the tasks I undertook were:

- Removing special characters and unwanted elements from the data
- Transforming the data to the desired format
- Trimming and removing unnecessary whitespace
- Handling missing values by utilizing Excel sheets to complete the required information

## Data Analysis

The data analysis phase encompassed the creation of various reports and visualizations to evaluate player performance based on specific criteria and roles. I designed three distinct reports focusing on:

1. Openers' performance
2. Middle-order batsmen's performance
3. Bowlers' performance

Each report included different visualizations tailored to the specific role being analyzed.

### Openers' Performance Analysis

- Table visualization displaying detailed information and performance metrics of the players
- Scatter plot showcasing filtered players against their strike rate
- Consolidated performance cards exhibiting average strike rate, average runs, and average balls faced

### Middle-order Batsmen's Performance Analysis

- Similar visualizations as the openers' performance analysis with the focus shifted to the middle-order batsmen

### Bowlers' Performance Analysis

- Scatter plot illustrating bowlers' performance against their economy rate
- Performance cards presenting average economy, average wickets, and average runs conceded

Furthermore, I created a separate page dedicated to the final selection of the best 11 players. This page incorporates three slicers and a player details table for easy player selection.

To enhance the user experience, I also developed two tooltip pages. These tooltips provide additional information when hovering over the scatter plot charts in the openers' analysis, middle-order analysis, and bowlers' analysis pages. The tooltips display player images, names, countries, roles, and batting or bowling styles accordingly.

## Getting Started

To access and explore the project, please follow these steps:

1. Clone this repository to your local machine.
2. Open the Power BI file (`.pbix`) using Power BI Desktop.
3. Interact with the various pages and visualizations to explore the analysis and make player selections.


Feel free to reach out if you have any questions or suggestions!

Happy analyzing!
