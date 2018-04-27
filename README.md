# Matthew-Javier-ps239t-final-project (under construction!)

## Description
This project focuses on creating a risk terrain model for crime in New York City. In this project, I will analyze petit larceny in April of 2017 and investigate certain geographical risk factors. These factors will be limited to infrastructural assets that I find to be strongly associated with New York's citylife: subways, bus stops, and munimeters. Because the distribution of these assets are concentrated in the most population dense precincts, I will throw in public libraries as sort of an ad hoc control variable since these are located relatively equality across the precincts. This long term project will eventually include other considerable risk factors. 
Onto the process itself. The datasets are sourced from NYC's Open Data R is used to clean the raw crime data, cutting out unimportant columns and isolating the data down to April 2017's petit larceny incidents. Next begin to 

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
#### Infrastructure Data
1. nypd_precincts_and_2010_census_pop.csv: NYPD precincts with 2010 census population. Note, precinct 61 was a broken polygon (even from Open Data, it's broken, I literally drew the precinct by hand to solve this. Available here: https://dunnguyen.carto.com/tables/nypd_precincts_and_2010_census_pop/public
1. DOITT_SUBWAY_ENTRANCE_01_13SEPT2010.csv: Subway entrance locations, available here: https://data.cityofnewyork.us/Transportation/Subway-Entrances/drex-xx56. 
3. Bus_Stop_Shelter.csv: The PolityVI dataset, available here: https://data.cityofnewyork.us/Transportation/Bus-Stop-Shelters/qafz-7myz
9. LIBRARY.csv: The PolityVI dataset, available here: http://www.systemicpeace.org/inscrdata.html
10. MUNIMETER.csv: The PolityVI dataset, available here: http://www.systemicpeace.org/inscrdata.html
11. NYC_Free_Public_WiFi_03292017.csv: The PolityVI dataset, available here: http://www.systemicpeace.org/inscrdata.html

*Note that the filenames from NYC Open Data are outdated. They continuously update, but fail to rename the file.
#### Crime data
1. NYPD_Complaint_Data_Current_YTD.csv: All reported crimes that occurred in New York City limits, available here: https://data.cityofnewyork.us/Public-Safety/NYPD-Complaint-Data-Current-YTD/5uac-w243
    - NYPD_Incident_Level_Data_Column_Descriptions.csv for column descriptions

### Code

1. Matt-Javier-CleaningData.rmd: Loads and cleans data from NYC Open Data, also merges data produced from QGIS
2. Matt-Javier-Analysis.rmd: Loads, cleans, and merges the raw Polity and NYT datasets into the Analysis Dataset.
2. 03_analysis.R: Conducts descriptive analysis of the data, producing the tables and visualizations found in the Results directory.

### Results

1. coverage-over-time.jpeg: Graphs the number of articles about each region over time.
2. regression-table.txt: Summarizes the results of OLS regression, modelling *nyt* on a number of covariates.

## More Information

Include any other details you think your user might need to reproduce your results. You may also include other information such as your contact information, credits, etc.
