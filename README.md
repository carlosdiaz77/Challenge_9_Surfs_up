# Surfs UP analysis

## 1. Overview of the analysis

This is the challenge activity for the module 9 of the Data Analytics and Visualization Boot Camp of the university of Texas at Austin.
The main idea is to apply the learned skills of SQLite and SQLAlchemy

<img src = "resources/intro.png" width= "650" >

The project  was based on data of about  19,550 records in 9 weather stations in the Hawai area.
The main objective of the analysis was to determine the weather trends in two specific months, June and December.
Below we can see a sample of the data in SQLite
 
<img src = "resources/SQLite.png" width= "650" > 
 


## 2. Results:

### Deliverable 1: Determine the Summary Statistics for June


<img src = "resources/june2.png" width= "650" >


Using Python, Pandas functions and methods, and SQLAlchemy, I filtered the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of June. I then converted those temperatures to a list, created a DataFrame from the list, and generated the summary statistics. See image above.


 
### Deliverable 2 : Determine the Summary Statistics for December


<img src =  "resources/dec2.png" width= "650" >

Using Python, Pandas functions and methods, and SQLAlchemy, I filtered the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of December. I then converted those temperatures to a list, created a DataFrame from the list, and generated the summary statistics. See image above.


## 3. Summary: 

### Summary:  The three key differences in weather between June and December:
	

I made two boxplots using the average tempetture of each day and we can see the image below.

<img src =  "resources/summary.png" width= "650" >



<img src =  "Resources/summary.png" width= "650" >
	
