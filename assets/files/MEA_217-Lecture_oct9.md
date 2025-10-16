---
layout: default
title: Lecture Oct 9
nav_exclude: true
---


October 9
---
## Activity 1

At this point we have been introduced Pandas and basic operations with it.

To motivate further dicsussion, I would like you to first:

- Review the code from last class and run all the cells
  
- Ask any questions that may arise


## Activity 2 - Obtaining and Visualizing Ocean Buoy Data

### Step 1: Data

- Navigate to [https://www.ndbc.noaa.gov/](https://www.ndbc.noaa.gov/)
- Familiarize yourself with the site and the data it provides
- Zoom to the North Carolina Coast
- Locate station: Station 41037 - Wrightsville Beach Offshore, NC (ILM3)
- If you click on the site, you will see a pop up on the page bottom. Follow the link "view history"
- Get data from the year 2023 (use method 2 to view and download the text file 41037o2023.txt)
- Examine the data - what are the columns? What are the units? Are there missing data? If so, what is the
  indicator (or data value for missing data)?
  
### Step 2: Code
- Write code to read the data as a Pandas data frame for the year 2023
- Then do the following
  - calculate the average, minumum and maximum water temperature reported by this station
  - calculate the average, minumum and maximum salinity reported by this station
  - How does the temperature at this site vary over the course of a year? Visualize it
  - How does the salinity at this site vary over the course of a year? Visualize it

## Step 3: More operations using Pandas
  - Follow along with me in class as we add more capability to your code

### Step 4: Upload your code on moodle under today's activity

