# Citibike-Analysis
Analysis of [ride data](https://www.citibikenyc.com/system-data "Data source") from New York City's bike sharing company Citibike for the month of December 2019.
 ##### [See the visualization here!](https://public.tableau.com/profile/barry.tikalsky#!/vizhome/Citibikeanalysis_15832739780490/CitibikeDashboard "Tableau Profile")
This visualization uses Tableau to interactively display data on bicycle ride destinations and times. The data was first loaded into Python Pandas to create the fields necessary for creating a filterable [spider map](https://help.tableau.com/current/pro/desktop/en-us/maps_howto_origin_destination.htm "More info on Spider Maps in Tableau"). 
Selecting a Station from the origins will show all bike trips from that origin for the dataset. Selecting days or hours will filter trips by start time.

In the below screenshot all trips starting at Pershing Square North are displayed. These trips are then filtered by trips starting on Tuesday during the 7 O'clock hour. Mousing over a path displays the origin and destination of that trip and its duration.
![Screenshot of the dashboard](Screenshot.png)
