# Project | Data Cleaning of Shark Attacks

This project is a challenge to evaluate our data cleaning skills. An open dataset was obtained from the web (url in 'Resources'), originally created as an amalgamation of other oficial incidents datasets. This means the dataset has little to no fundamental criteria to its input, and that means dirt.


## Introduction

The challenge was proposed with only three necessary bullet-points:

- The deliverables must be handed-down befor 3:30  p.m December 12 of 2019.
- The deliverables are a .csv containing the cleaned dataset, a jupyter notebook and a presentation.
- Do our best. Also, justify why and how on each step.


## The steps

- Organize the steps, with expected necessary time to conclusion.
- Overlook of the data and write suppositions and expectations.
- Read content about data cleaning with the acquired toolbox.
- Thorough evaluation of the dataset, to identify the main issues and greatest opportunities.
- Remove, with justifications, the most empty rows and columns, to obtain a leaner dataset.
- Remove, with justifications, rows and columns containing redundant information, also to make it lean.
- Identify key information and ease of work on the dataset.
- Target those key columns to improve workability.


## Stones along the way

- I first thought that cleaning columns would be my priority. I was not expecting so many empty rows.


## Found oportunities

- 'Case n. 1', 'Case n. 2', 'Case number' and 'Date' had high correlation.
- 'href formula' and 'href' had high correlation. 
- Also, 'pdf' doesn't look like is adding anything new, except the last name.

## Things I'd like to take my time to learn

- I like to extract a clean column of years, and ideally day and month, but that would take time to learn.
- Binning the 'Time' into periods of the day
- Using the 'pdf' as a source for the missing names, and then drop it
- Answer if the 'original order' a column of uniques, and set it as index
- Map 'Sex','Time' and 'Age' into the inherent simplicity of its data


## Deliverables

- sharkattacks_clean_ish.csv
- A neatly organized and commented jupyter notebook. With this README file.
- A presentation.


## Resources

[Dataset - Shark Attacks](https://www.kaggle.com/teajay/global-shark-attacks/version/1)