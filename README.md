* Tableau:
Tableau is one of the fastest evolving business intelligence and data visualization tool. 
It is easy to deploy data from different data sources like Sql server, Hadoop/Hive, Teradata and from Flat files.
In Tableau, we have different types of chart like Histogram, Side by side, Scatterplot, and Bubble chart etc. 
Dimensions and measures are two different categories used to represent aggregate and non-aggregate functions. 
We can work with multiple data sources using data blending concept. Sometimes Sql queries are used to retrieve the data from data set. In this project, I have used Tableau Desktop 10.3 version and Tableau server to publish the workbook. I have compared two measures for dual axis.

* Data Set
In this project, we have taken excel set (Sheet1 sample coding) as data. 
I have used extract connection as it would be flexible to publish to tableau server and Tableau public. In the data set we have five columns and they are Date, Name of table, Name of person, Position, Unit and number of records. Once the data set is connected to Tableau desktop 10.3, dimensions and measures are separated automatically. 

* Project:
Percentage of employees based on seating is represented in the visualization.
I had created three calculation fields like to get the data in correct viz. 
Durations in preferred place gives the time spent on the table as sum of best place is divided by sum of number of records.
Preferred place measure gives the best place for employee based on the position. 
Best place calculation field gives maximum amount of time employee preferred to seat in table. 
I have dragged duration preferred place to columns where Rank-unique is assigns on table calculations and Name of table to rows to compare. We have assigned dual axis by creating two fields in shelf itself as AGG (avg (0)). 
Quick filter is used to filter the measure names. In marks field, we have two fields in one field we have name of person in details, durations in preferred field is in tool pic and measure name is in color and details. 
In format, we have assigned the percentage to duration of preferred place to views the percentage of employees seating in table.
In viz we have represented the percentage of time in duration in preferred place, name of person, name of table where the employees are seating.  I have included the command buttons and selections by category on. 
In viz, we have big square embedded with circle where it represents the durations of time spent according to size. 
Ones the worksheet is done we need to use these workbook to tableau dashboard. Where we can format and gives color to shading and rules. Therefore, it would be clearly understandable when we see the data in viz form. 
Employees seating position in meeting dashboard is very flexible and very good at performance where it optimizes the queries fast. 

* Tableau File extensions:
. Twb-Tableau workbook holds one or more worksheets, tableau dashboard and tableau stories
. Tbm-Tableau book mark contains single worksheets and it is easy way to share your work quickly.
. Twbx- Tableau packaged workbook, where it is a zip file contains all supporting local files in data source. It is best way of sharing data who don’t have access to data.
. Tde- Tableau data extract, it is used to share data.
. Tds- Tableau data source, contains information which is used to connect to data sources.
These file extensions are use full for sharing and publishing the tableau dashboard, worksheets to the tableau repository.

### DASHBOARD
![alt text](https://github.com/Hima8696/Tableau-Dashboard/blob/master/Screenshots/Capture11.PNG) 
#### CALCULATIONS
![alt text](https://github.com/Hima8696/Tableau-Dashboard/blob/master/Screenshots/Cal1.PNG)
![alt text](https://github.com/Hima8696/Tableau-Dashboard/blob/master/Screenshots/Cal2.PNG)
![alt text](https://github.com/Hima8696/Tableau-Dashboard/blob/master/Screenshots/Cal3.PNG)


Tableau Public Link: https://public.tableau.com/profile/ hima 
