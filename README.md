# Best-Selling Video Games of All Time

**Author:** Georgia Cameron and Noel Pop\
**Date:** November 21, 2025

## Project Goal
The goal was to identify the top platforms used by the most sold video games of 
all time and how many of the best-selling video games of all time belong to 
well-known publishers.

## About the Dataset
This project uses the “Best-Selling Video Games of All Time” data set 
by Tayyar Hussain, available on Kaggle. The dataset is composed of records 
of high-selling video games. The dataset is composed of records of high-selling 
video games. It includes numerous data points for each game. Each game is 
ranked on the list of best-selling video games of all time. The titles of 
each video game are included and the estimated number of copies of each game 
is reported in millions. There is a data column for the name of the series to 
which the video game belongs, if applicable. Each video game has the name of 
the developer, the company or individual responsible for creating and 
programming the video game and the name of the publisher, the company or 
individual responsible for marketing or distributing the video game. 
Additionally, the date on which the video game was first released to the 
public and the platform on which the video game is available are included.

## Project Set-up
The data was imported into R and cleaned by standardizing variable names, 
removing empty rows and columns, and omitting entries with missing values 
in key fields including platform, publisher, and sales. 
A box plot was created to visualize the different platforms that the most 
sold video games of all time uses. A bar plot was created to visualize 
how many of the best selling video games of all time belong to each publisher.

## Running the Code
The required packages to run the code are tinytex, tidyr, janitor, readxl, 
lubridate, ggplot2, dplyr, paletteer, and patchwork. 