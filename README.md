A date dimension or table can be extremely important when working on a Power BI project, or BI projects in general for that mater. Here’s some of the quick benefits and reasons why you need a date table:

Helpful when filtering data
Filter by year, quarter, month, etc…
Helpful for drilling into a hierarchy of dates
Expand 2015 to see all the months within that year
Drill in to January to see all the days within that month
It’s required to do Time Intelligence functions in Power Pivot with DAX
Calculating year to date, prior period, etc…
It allows you to track important dates like holidays in a central spot.
Theses can be applied to filters
Allows you to track multiple types of dates
Calendar, fiscal, manufacturing, etc…
Just about any project will likely require one or many of these features. So if you’re working on a Power BI project what are your options?

Import a date table that exist in your source already and use it
Import a date table from the Azure Marketplace (I’ve used DateStream in the past successfully)
Use Power Query and the M query language to create your own date table from scratch
For this post I’d like to share with you how to do option 3 using a script that I’ve created to generate a date dimension. Here’s the steps to replicate this table on your own.

Creating the Date Dimension
Launch Excel
Go to Power Query tab. If you haven’t downloaded Power Query already you can do so here.
Select From Other Sources > Blank Query. This will launch the Power Query Editor .
Select Advanced Editor in either the Home or View tab of the editor.
Remove any code that the editor is currently story and replace it with the following:
