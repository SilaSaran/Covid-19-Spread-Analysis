# Covid-19-Spread-Analysis
Covid-19 Global Impact Dashboard: Comprehensive Analysis Using Power BI

Introduction
This project aims to create a comprehensive dashboard in Power BI to analyze the global impact of Covid-19. The dashboard will include various visualizations to provide insights into confirmed cases, deaths, recoveries, and other key metrics.

Step-by-Step Guide
Step 1: Open Power BI Report.
        Open Power BI Desktop.
        Import Dataset
      	Go to Home -> Get data.
        Select the dataset you want to import.
        Remove all inconsistancies.
        
Step 2: Create Calculated Measures.
        Right-click on the dataset in the Fields section.
        Select New measures.
        Here I created the measures named as 'Acive cases','Average New cases','Average New Death cases','Average Recovered cases','Mortality Rate' and 'Recovered Rate'.

step 3:Start visualization in Model View.
       Customised the canvas as per the theme.
       Created First page with a title Covid 19: Spread Regional Insights.
       Added an Image for the Logo.
       
Step 4:Create Mutiple Card for Various Metrics:
    	Go to the Visualization pane.
      Drag and drop the Card visual.
      Add fields into the Card visual:
      Put 'Mortality Rate','Recovery Rate', 'Average confirmed cases', 'Average recovered cases ' and 'Average deaths' in Fields.

Step 5:	Add Gauges for Total confirmed Cases, Active Cases, Deaths, and Recovered Cases:
        Go to the Visualization pane.
        Drag and drop the Gauge visual.
        Add fields into the Gauge visual:

Step 6:	Add Slicers for Month and Country/Region:
       Go to the Visualization pane.
       Drag and drop the Slicer visual.
       Add fields into the Slicer visual:
       
Step 7:	Add a Map for Covid-19 Latest Confirmed Cases by 'Country/Region':
        Go to the Visualization pane.
        Drag and drop the Map visual.
        Add fields into the Map visual:
        
Step 8: Add a Clustered Bar Chart for Last week Confirmed Cases by Country/Region:
        Go to the Visualization pane.
        Drag and drop the Clustered bar chart visual.
        Add fields into the Clustered bar chart visual:
       
Step 9:	Add a Line and Clustered Column Chart for Cumulative Confirmed, Deaths, and Recovered by Date:
        Go to the Visualization pane.
        Drag and drop the Line and Clustered column chart visual.
        Add fields into the Line and Clustered column chart visual:
        Put 'Date' in the X axis field.
        Put 'Deaths' in the Y axis values field.
	Put 'Confirmed' and 'Recovered' in the Line values field.
9.	Add a Table for Various Metrics:
o	Go to the Visualization pane.
o	Drag and drop the Table visual.
o	Add fields into the Table visual:
	Put 'Country/Region', 'Confirmed Daily', 'Recovered Daily', 'Deaths Daily', 'Average Confirm daily', 'Average Recovered daily', 'Average Deaths daily', 'Recovery Rate', and 'Mortality Rate' in Values field.
o	Apply conditional formatting on the table:
	Go to Format -> Conditional formatting -> Select column -> Turn on Data bar.
Conclusion
By following these steps, you can create a comprehensive Covid-19 Global Analysis Dashboard in Power BI. This dashboard will help you visualize and analyze the impact of Covid-19 across different regions and time periods.

