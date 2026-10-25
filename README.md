
# My Project Repository

This repository contains the code and resources for my project.
Overview:
This project aims to provide a series of informative graphs, heatmaps and tools for Monash University staff to use in their running of their engineering facilities by predicting headcounts in different rooms within the facility at different times. By harnessing the outputs of this project, managers can control staffing and utility levels to best meet the requirements of the future expected heacounts. The makerspace occupancy data provided by MMA3001 is used as input data. The program utilises a series of numerical analysis and machine learning methods taught in MMA3001 to efficiently process the data into the outputs.

The provided outputs of the program are:
Line graphs showing the average occupancy at each time of day for all rooms combined as well as each room individually.
Heat maps breaking down the average occupancy into the time of day and day of week for all rooms combined as well as each room individually. Values which are predicted by machine learning as opposed to being backed by physical data are shown in a lighter colour.
A lookup tool to find the total headcount over a given time period.
Table with mean and standard deviation for each room.
Validation and training errors for the utilised numerical methods.


Instructions:
The input datafiles are "Pre Daylight Savings 1", "Pre Daylight Savings 2" and "Post Daylight Savings", they had to be broken up to fit onto GitHub.
All input datafiles can be found in this repository, ready for upload when running the code.
Run all sections of the code to generate outputs.
To utilise the occupancy lookup tool, select the room, day of the week, start time and end time and then click "Calculate Occupancy"
