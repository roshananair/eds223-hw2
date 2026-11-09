# eds223-hw2
Repository for EDS 233 Homework 2: Exploring Patterns of Environmental Justice

## Assessing Suitability for Mariculture on the West (Pacific) Coast of the United States
This repository contains Assignment 2 for EDS 223 Geospatial Analysis & Remote Sensing. First, this assignment looks at the legacy of redlining in current environmental justice, specifically looking at patterns of people with low income, PM 2.5, and low life expectancy across Home Owners' Loan Corporation (HOLC) grades (redlined neightbourhoods). Then, it looks at the legacy of redlining on pedestrian and bicycle accidents, by looking at proportions of accidents occuring across HOLC grades.

## Repository Contents
 - **data/** 
     - **data/ejscreen**
        - data/ejscreen/EJSCREEN_2023_BG_StatePct_with_AS_CNMI_GU_VI.gdb
             - GeoDatabase containing EJScreen data
        - data/ejscreen/EJSCREEN_2023_BG_Columns.xlsx
             - Descriptions of columns/variables in EJScreen data
        - data/ejscreen/ejscreen-tech-doc-version-2-2.pdf
             - Technical documentation for EJScreen
     - **data/mapping-inequality**
        - data/mapping-inequality/mapping-inequality-los-angeles.json
             - Map data for Home Owners' Loan Corporation (HOLC) grades
     - **data/SWITRS_LA**
        - data/SWITRS_LA/Crashes.csv
             - Data on crashes in Los Angeles County from the Statewide Integrated Traffice Records System (SWITRS) database
 - **homework_2.qmd** 
     - Contains code to map census block groups by HOLC grade, summarise percent of block groups in each HOLC grade, visualise people with low income, PM 2.5, and low life expectancy by HOLC grade, and show proportions of pedestrian and bicycle accidents by HOLC grade.

## Contributors 
[Roshan Andres Nair](https://github.com/roshananair)

## References
1. U.S. Environmental Protection Agency. [EJScreen: Environmental Justice Screening and Mapping Tool (Version 3.2022.3).](https://pedp-ejscreen.azurewebsites.net/) Mirrored and hosted by Public Environmental Data Partners.

2. Nelson, Robert K., LaDale Winling, et al. [Mapping Inequality: Redlining in New Deal America.](https://dsl.richmond.edu/panorama/redlining) Edited by Robert K. Nelson. American Panorama: An Atlas of United States History, 2023.

3. Safe Transportation Research and Education Center (SafeTREC). [Transportation Information Mapping System (TIMS): Statewide Integrated Traffic Records System (SWITRS).](https://tims.berkeley.edu/). University of California, Berkeley.
