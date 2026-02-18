Operational Guide for Reproducibility – F1 Drivers Championship Analysis from Reddit

By Giovanni Noè and Elena Maggiore
University of Milan Bicocca – Social Media Analytics Course

PROJECT OVERVIEW

This project analyses discussions on Reddit related to Formula 1 with the goal of reconstructing fan communities and studying their sentiment over time about the drivers championship and the world champion (Lando Norris).
The analysis combines Social Network Analysis (SNA), community detection, and sentiment analysis to investigate how different fan bases interact and express opinions during the Formula 1 season, with a specific focus on the World Championship battle.

FOLDER STRUCTURE

The project folder is organized as follows:

Data
Contains the Reddit data gathered for the analysis, including comments, posts and related metadata.

SMA_Project_Maggiore_Noè
Contains the single notebook used for data processing, network construction, social network analysis, community detection, and sentiment analysis.

SMA_Presentation_Maggiore_Noè
Contains the presentation slides summarizing the methodology and main results of the project.

SMA_Report_Maggiore_Noè
Contains the final written report describing the project in detail.

REPRODUCIBILITY NOTES

The notebook is designed to be executed sequentially from top to bottom, since data is saved in another folder and the data gathering could provide different results at each run (due to time passing), the Data Acquisition section should not be executed, comments and posts data frames will be loaded in the subsequent section.
Some parts of the analysis, especially sentiment analysis with transformer-based models, may benefit from GPU acceleration.
All results presented in the report and slides can be reproduced using the provided data and notebook.
