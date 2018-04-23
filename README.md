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
## Infrastructure Data
1. DOITT_SUBWAY_ENTRANCE_01_13SEPT2010.csv: Subway entrance locations, available here: https://data.cityofnewyork.us/Transportation/Subway-Entrances/drex-xx56. 
3. Bus_Stop_Shelter.csv: The PolityVI dataset, available here: https://data.cityofnewyork.us/Transportation/Bus-Stop-Shelters/qafz-7myz
4. DOITT_AFTER_SCHOOL_PROGRAM_01_29JUL2009.csv: The PolityVI dataset, available here: https://data.cityofnewyork.us/Social-Services/After-School-Programs/6ej9-7qyi
5. COLLEGE_UNIVERSITY.csv: The PolityVI dataset, available here: http://www.systemicpeace.org/inscrdata.html
6. Public_Schools_Points_2011-2012A.shp: The PolityVI dataset, available here: http://www.systemicpeace.org/inscrdata.html
7. homebase_locations_for_homelessness.csv: The PolityVI dataset, available here: http://www.systemicpeace.org/inscrdata.html
8. homeless_drop-_in_centers.csv: The PolityVI dataset, available here: http://www.systemicpeace.org/inscrdata.html
9. LIBRARY.csv: The PolityVI dataset, available here: http://www.systemicpeace.org/inscrdata.html
10. MUNIMETER.csv: The PolityVI dataset, available here: http://www.systemicpeace.org/inscrdata.html
11. NYC_Free_Public_WiFi_03292017.csv: The PolityVI dataset, available here: http://www.systemicpeace.org/inscrdata.html

*Note that the filenames from NYC Open Data are outdated. They continuously update, but fail to rename the file.
## Crime data
1. NYPD_Complaint_Data_Current_YTD.csv: All reported crimes that occurred in New York City limits, available here: https://data.cityofnewyork.us/Public-Safety/NYPD-Complaint-Data-Current-YTD/5uac-w243
    - NYPD_Incident_Level_Data_Column_Descriptions.csv for column descriptions

### Code

1. Matt-Javier-PS239T-Final-Project.rmd: Loads and cleans data from NYC Open Data, also merges data produced from QGIS
2. 02_merge-data.R: Loads, cleans, and merges the raw Polity and NYT datasets into the Analysis Dataset.
2. 03_analysis.R: Conducts descriptive analysis of the data, producing the tables and visualizations found in the Results directory.

### Results

1. coverage-over-time.jpeg: Graphs the number of articles about each region over time.
2. regression-table.txt: Summarizes the results of OLS regression, modelling *nyt* on a number of covariates.

## More Information

Include any other details you think your user might need to reproduce your results. You may also include other information such as your contact information, credits, etc.
