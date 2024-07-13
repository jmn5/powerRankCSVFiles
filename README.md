## DSA Power Rankings Repository
Welcome to the DSA Power Rankings repository. This repository stores the power rankings for several soccer leagues, updated periodically. The rankings are stored in CSV files, and there is a DateTime document to track when the files were last updated.


### Repository Structure

The repository contains the following files:


### CSV Files: 

Each league has a corresponding CSV file containing the power rankings. The file name format is [league_name]_power_rankings.csv.


DateTime.docx: A Word document that records the date and time when the rankings were last updated.

### Leagues Covered
The following leagues are included in this repository:

Saudi Professional League

USL League Two

USL Championship

NWSL

Major League Soccer (MLS)

English Premier League (EPL)

Serie A

Women's Super League

La Liga

Women's Premier Soccer League (WPSL)

United Premier Soccer League (UPSL)

National Premier Soccer League (NPSL)

### Each CSV file contains the following columns:

Team: The name of the team.

Rank: The ranking of the team.

Wins: The total number of wins.

Losses: The total number of losses.

Ties: The total number of ties.

Points: The total points accumulated by the team (calculated as 3 * Wins + Ties).

### DateTime.docx

This document records the date and time when the rankings were last updated. It is useful for tracking the currency of the data.

### Updating Rankings
The rankings are updated by running a Python script that scrapes match results from various websites, processes the data, and generates the rankings. The script also updates the DateTime.docx file.
