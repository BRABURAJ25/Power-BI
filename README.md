# Power-BI
In this project, I worked on a real-time business case where a company's sales performance was declining. I obtained the raw sales dataset and performed the following steps:

Clean → Transform → Model → Visualize → Insight.

1)Data Cleaning & Transformation
2)Data Modeling
3)Power BI Visualization
4)Insights Generated
5)Published Online 


How it started?

Downloaded the raw data set from https://codebasics.io/resources/sales-insights-data-analysis-project, and loaded this data into My SQL Work Bench.

Just runnnig some select queries and other sql commands to check the consistency of data(contains 150000 rows). 

Problem Araised

I've to connect My SQL and Power BI. To load the data from My sql to Power BI. But usual method falied. Error with My Sql Connector, tried with all trouble shooting methods

💡Tried other options to load the data to Power BI. Then I found ODBC = Open Database Connectivity
It’s a standard API (Application Programming Interface) that allows Power BI to connect to databases like MySQL regardless of the database vendor.

Data Sucessfully loaded!

Next Step-> Data Cleaning🛠️ in Power Query.

I don't want the regions apart from India, removed.

Deleted some unwanted blank values.

Some currency type are in USD, converted into INR(manually), it prefer to fetch real time value.

Data Cleaned and ready for analysis.


🔗Data Modeling.

At initial stage I found there is a common table Transaction linked with all other table expect date, and market. 

But I proceed further. There is a mistake. we have to check whether all the tables are related with common column. 

If not just find the column from market that matched with Transaction column i.e Market_Column drag that column from M -> T it will mapped in One to Many Relation ship. 


📊Started Working with Generating Reports (Visualization Started)

Draging the required column to the medium and altering accordingly. 

Creating Measures like a formula and injecting that into charts wherever it required.

#Interactions are the best feature of Power BI where it changes when ever you changes the data.

Based on the Key Performance Indicator we created some dash board that represents sales performance region wise, year wise, Top 5 Products and Top 5 Customer.

Brain Stroming Sessions with Sales People

Based on the requirement our dashboard changes.

like they required the Performance insights, when sales is decling the expected the alert should be shown in the dash board. Added that feature.

This is the good to go begineer friendly guided Power Bi Project from Code Basics.  

Thanks for Reading.  


