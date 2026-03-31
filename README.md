# Project 3

## Transportation Data Visualization and Simulation
This Python Programming Assignment 3 is completed by Abdi Aden for CIVE 202 and is intended to be shared with the instructor.

## Purpose
This project involves the analysis of real-world data related to transportation. The project involves the following:

NHTS (National Household Travel Survey) - travel patterns

NGSIM (Next Generation Simulation) - vehicle-following behavior

The purpose of the project is:

To create clear data visualizations related to transportation trends
To analyze vehicle speed, acceleration, and spacing behavior
To implement the Intelligent Driver Model (IDM) to simulate traffic behavior
To compare real-world data with the results from the simulation

The project also shows the potential for Python to be used as an engineering tool instead of traditional tools such as Excel.

## Repository Contents
This repository includes all the required materials for Project #3. The materials are as follows:

README.md 

– A summary of the project and a guide on how to run the code

Scope of Work (SOW) 

– A detailed outline of the project activities and requirements

Annotated Code Document (ACD) 

– An explanation of the Python code written

Technical Report 

– A comprehensive report comprising an introduction, methods, results, and discussion

Gantt Chart 

– A project plan showing the project timeline and scheduling

Engineering Timesheet 

– A log of the hours spent working and the activities completed
Python Code (.ipynb) 

– A Jupyter Notebook that is used to produce the analysis and results

Datasets (NHTS.csv and NGSIM.csv) – Data required for the project

## How to Run the Code
Make sure you have Python installed with the following libraries:

pip install pandas numpy matplotlib seaborn

Open the file:

Project3_CIVE-202_Abdi-Aden_Code.ipynb

in Jupyter Notebook or VS Code

Run each section top to bottom:

1. Import Libraries
Loads pandas, numpy, matplotlib, seaborn
2. Load Datasets
Reads:
NHTS.csv
NGSIM.csv
3. Data Cleaning
Selects variables:
travel_day, vehicle_age, vehicle_type
speed, acceleration, position variables
Removes missing values using .dropna()
4. Data Visualization

The code generates:

Bar Chart - Trips by day
Histogram - Vehicle age distribution
Boxplot - Vehicle age by type
Time-Series Plots:
Speed vs Time
Acceleration vs Time
Spacing vs Time

The model:

Uses leader vehicle data
Simulates follower behavior
Calculates:
Speed
Position
Acceleration

Then compares:

Actual vs Simulated Speed
Actual vs Simulated Position
Actual vs Simulated Acceleration
Actual vs Simulated Spacing

After running the code the program will:

Display all graphs
Show comparisons between real and simulated data
Provide visual insight into transportation behavior

## Results
Travel demand is not uniform over days
Most vehicles are within a moderate age group
Different vehicles have different age groups
Follower vehicles respond to leader vehicles with some lag
Acceleration is not constant - constant adjustments by drivers
Spacing is not constant, which affects safety
IDM simulation does not show all the variability seen in the real world

## Engineering Relevance
This project is important for:

Traffic flow modeling
Roadway safety analysis
Autonomous vehicle development
Transportation planning and policy
Intelligent transportation systems

## Project Timeline
The project followed a structured schedule including:

Data review
Cleaning and processing
Visualization creation
Simulation modeling
Report writing

(Look at Gantt Chart for full breakdown)

## Work Summary
Total Hours Worked: 32.8 hours
Tasks included:

Data cleaning
Visualization
Simulation development
Report writing
Final revisions

## Final Deliverables
Python Code (.ipynb)

Annotated Code Document

Scope of Work

Gantt Chart

Engineering Timesheet

Technical Report

GitHub Repository

## References
Federal Highway Administration (FHWA)
National Household Travel Survey (NHTS)
Next Generation Simulation (NGSIM) Dataset
CIVE 202 Course Materials

