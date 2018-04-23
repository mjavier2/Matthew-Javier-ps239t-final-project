# Matthew-Javier-ps239t-final-project
This is a template you can use for your final project. Fill in each section with information on your own project.

## Short Description

Give a short, 1-2 paragraph description of your project. Focus on the code, not the theoretical / substantive / academic side of things. 

## Dependencies

List what software your code depends on, as well as version numbers, like so:.

1. R, version 3.4.4
2. RStudio, version 1.1442
2. QGIS, version 3.0.1

(In your code itself, includes commands that install required packages.)

## Files

List all other files contained in the repo, along with a brief description of each one, like so:

### Data

1. NYPD_Complaint_Data_Current_YTD.csv: The PolityVI dataset, available here: https://data.cityofnewyork.us/Public-Safety/NYPD-Complaint-Data-Current-YTD/5uac-w243
    - NYPD_Incident_Level_Data_Column_Descriptions.csv for column descriptions
2. DOITT_SUBWAY_ENTRANCE_01_13SEPT2017.csv: Subway entrance locations, available here: https://data.cityofnewyork.us/Transportation/Subway-Entrances/drex-xx56. Note that when downloaded it will say "SEPT2010." The csv file was updated since Sept of 2017, they have just simply failed to rename the file for the past 6 years
3. polity.csv: The PolityVI dataset, available here: https://data.cityofnewyork.us/Transportation/Bus-Stop-Shelters/qafz-7myz
4. polity.csv: The PolityVI dataset, available here: https://data.cityofnewyork.us/Social-Services/After-School-Programs/6ej9-7qyi
5. polity.csv: The PolityVI dataset, available here: http://www.systemicpeace.org/inscrdata.html


### Code

1. 01_collect-nyt.py: Collects data from New York Times API and exports data to the file nyt.csv
2. 02_merge-data.R: Loads, cleans, and merges the raw Polity and NYT datasets into the Analysis Dataset.
2. 03_analysis.R: Conducts descriptive analysis of the data, producing the tables and visualizations found in the Results directory.

### Results

1. coverage-over-time.jpeg: Graphs the number of articles about each region over time.
2. regression-table.txt: Summarizes the results of OLS regression, modelling *nyt* on a number of covariates.

## More Information

Include any other details you think your user might need to reproduce your results. You may also include other information such as your contact information, credits, etc.
