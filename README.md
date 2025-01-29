# Phase-2-Project

Author: __[Liam Hudson](https://www.linkedin.com/in/liamhud-son)__

## Overview
This __[project](notebooks/final.ipynb)__ investigates multiple movie datasets from IMDB and The Numbers utilizing both SQL and Python. The goal is to identify the primary factors that contribute to a film's success so that crucial business recommendations can be made. Given the large volume of data, cleaning, filtering, and visualization were key to devleoping a strong analysis. The main factors investigated were movie genre, director, and money figures (e.g. production budget, worldwide/domestic gross, etc.)

## Business Understanding
My business, Echelon Studios, sees how its competitors are producing successful films and wants to begin taking steps towards accomplishing that, as well. But, the problem is that Echelon Studios does not know the proper makeup of a movie's success. My goal is to analyze movie data and find those factors so that I can make appropriate recommendations.

## Data Understanding
Originally, there were over five datasets to work with. But, upon thorough investigation seen in __[this notebook](notebooks/exploratory.ipynb)__, I found a lot of repeated and unnecessary information across all the datasets. Thus, I only worked with the data that was relevant to my investigation, which was contained within the IMDB database and The Numbers dataset. The former contains information on a movie's director and genre, while the latter contains information on a movie's production budget and gross revenue (worldwide and domestic).

## Data Preparation
This project utilizes SQL and Python to eliminate unnecessary variables and merge datasets together, when appropriate. All records that contain a NULL value are eliminated because all data plays a role. 

## Recommendations

1. Produce either an `Adventure|Animation|Comedy` or `Drama` film.
2. To produce a highly popular and grossing film, hire Mike Mitchell to direct an `Adventure|Animation|Comedy` film.
3. For the most return on investment, hire Alex Kendrick to direct a `Drama` film.

## Conclusion + Final Notes
It is important to acknowledge that this project deals with data that has bias. For instance, a film that was produced in 2010 has had more time to generate revenue than a film produced in 2015 has. Also, the data is only as recent as 2018.

## For More Information
I have linked the project notebooks throughout this README file, as well as below:

__[Exploratory Notebook](notebooks/exploratory.ipynb)__

__[Final Notebook](notebooks/final.ipynb)__

Here is a slidedeck with a more organized overview of this project:

__[Slidedeck](https://github.com/lthudson42/Movie_Analysis/blob/6b4532b0668c700ba677565f99a0b4153c45d8ef/Echelon%20Studios%20Movie%20Analysis.pdf)__
