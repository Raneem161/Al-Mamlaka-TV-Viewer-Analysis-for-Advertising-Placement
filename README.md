# Al-Mamlaka-TV-Viewer-Analysis-for-Advertising-Placement

## Overview
This project conducts a thorough analysis to determine optimal times for advertising on Al-Mamlaka, a public television broadcaster in Jordan. By examining user data across weekdays and program schedules, the project sought to identify periods of high and low viewership. The analysis used CSV files and Jupyter Notebook, focusing on understanding audience interaction patterns throughout the day and week. Key findings indicate that news programs often align with peak user numbers, particularly around noon, while early morning hours show the lowest viewership. The project concludes with recommendations to place advertisements during high-traffic news broadcasts and avoid early morning slots, acknowledging challenges faced with data organization and suggesting further analysis with more extensive data in the future.

## Data Details
The data was provided by Al-Mamlaka, a public broadcaster based in Amman, Jordan, established by a bylaw in 2015. The project utilized several datasets provided by Al-Mamlaka:
- Daily Datasets: Datasets for each weekday (Sunday, Monday, Tuesday, Wednesday, and Thursday) were provided.
- Online Users Dataset: Access was given to a separate dataset detailing the number of people online at any given time between 12 am and 12 pm on May 22, 2022, and May 26, 2022. A combined average of users across both programs was determined by splicing these two datasets together.
- Program Data: Data of programs was delivered as a grid or schedule with time and day, but without any output data.
The primary dataset used for the analysis have been consolidated into a CSV file. This file contains 54 rows and 8 columns. The columns are labeled: 'ID', 'TIME', 'SUNDAY_USERS', 'MONDAY_USERS', 'TUESDAY_USERS', 'WEDNSDAY_USERS', 'THURSDAY_USERS', and 'PROGRAM'.

## Documentation
For more details regarding the data source, and analysis of the results, you can access the project's full documentation via this link: https://drive.google.com/file/d/1ro63t2TwbD33CkcJTIZ3RYZd7xpfclVi/view?usp=sharing

## Code
You can find the project code in the Notebook.ipynb file.
