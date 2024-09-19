# Compilation of Documents (PROGRAMMING ASSIGNMENTS)

## Practice Problems:

ECE BOARD EXAM PROBLEM: Using data wrangling and data visualization technique with storytelling, analyze the data and present different (i) data frames; and (ii) visuals using the dataset given.

1. Create the following data frames based on the format provided:

      Example: Vis = [“Name”, “Gender”, “Track”, “Math<70”]; hometown is constant as Visayas

      a. Filename: Instru = [“Name”, “GEAS”, “Electronics >70”]; where track is constant as Instrumentation and hometown Luzon

      b. Filename: Mindy = [ “Name”, “Track”, “Electronics”, “Average >=55”]; where hometown is constant as Mindanao and gender Female

2. Create a visualization that shows how the different features contributes to average grade. Does
chosen track in college, gender, or hometown contributes to a higher average score?


## Overview of the P.A.:

Source of the code: board2.csv (Downloadable in Main Branch)

Description: This project involves analyzing and visualizing student grades from an example Electrical and Communications Engineering (ECE) Board Exam dataset. The dataset contains information on students' scores in various subjects, their gender, track, and hometown. The primary tasks is to include data wrangling and visualization to understand how different data (track, gender, hometown) contribute to students' average grades.


## P.A. Analysis, Explanation, and Process

- Download the Dataset - Make sure to save the provided file "board2.csv" in your working directory or default user folder together with the Jupyter Notebook

- Set Up the Jupyter Notebook - Open a Jupyter Notebook. Create a new notebook and rename it

- Load the Dataset - Start the program by importing the pandas library. Import the CSV file into the Data and name it, for example, board

- Creating the Average Score Column - Calculate for the average score of the subject columns and use it for further analysis.

- Filtering the Data - Take relevant data based on given criteria. Create graphs and new frame for the filtered data.

- Run the Cells - Execute each cell sequentially, and review the outputs to confirm that the operations performed well


## Expected Outputs

For P.A.4 Problem no.1

- "Instru" - Data Frame and set of files with students' names, GEAS, and Electronics scores filtered by the given conditions.

- "Mindy" - Data Frame and set of files with students' names, track, Electronics scores, and average grades, filtered by the given conditions.

...............................................................................................................................

For P.A.4 Problem no.2

- Visualizations - Bar charts for average grades by track, gender, and hometown. To check which of the data sets ontributes to a higher average score.


## Version and Edit History 

- Version 1 - Initial implementation of data wrangling, filtering, and basic visualizations.

- Version 2.1 - Extended the previous code by adding a new column that calculates the average score from multiple subject

- Version 2.2 - Added Label and comments to further better readability for viewers

- Version 3 - Significant changes, tried to adjust the bar graph to other type of possible graph like pie chart or area graph, but was noted to be unsuccessful. Reverted to original "bar graph"

- Version 4 - Working output, corrected most of the possible mistakes, Final Ouput
  

# Author's Profile
Name: Charles Ellis S. Reyes

Section: 2ECE-D

P.A. by: Prof. Engr. Ma. Madecheen S. Pangaliman, M.Sc.

Date of Completion: September 19, 2024
