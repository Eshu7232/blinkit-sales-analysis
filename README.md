# Blinkit-Sales-Analysis

##blinkit sales-dashboard

#Problem statement

This dashboard helps to understand the blinkit sales.It is a quick commerce platform, aims to analyze its grocery sales performance across different outlets, item types, and customer ratings. it helps the blinkit know their customers are satisfied with their products,through customer ratings.it also lets them know the average sales,total sales,average ratings.


###steps followed

-step1:load data into power bi dekstop,dataset is a csv file.

-step2:open power query editor & in view tab under data preview section,check "column distribution","column quality",&"column profile"options.

-step3:i abserved some column errors&empty values were present in item weight.In business requirement item weight is not neceesary.thats why i am not cleaned that column.

step4:After that i went to report view,under the insert tab i select rounded tab.

step5:for the rounded tab i do some formattings.and visual filters(slicers) were added for 3 fields named "outlet location type","outlet size","item type".

step6:using new card i visualized kpi's requirement.
📊 Key Metrics Displayed
Total Sales: $1.20M
Average Sales: $141
Number of Items: 8523
Average Rating: 3.9

step7:after that i used charts for
Sales by Fat Content: Low Fat vs Regular
Top Item Types by Sales
Sales by Outlet Tier (Tier 1, 2, 3)
Outlet Size and Type Contribution
Trend Over Time (2012–2022).

step8:For kpi's metrics i was created new measures.that measures were created for totals sales,average sales,no.of items,average rating.
for creating measures i performed some dax calculations.

 ##Dataset Fields
Sales, avg sales, avg rating
Item Type, Item Fat Content, Item Weight, Item Visibility.Outlet Size, Outlet Type, Outlet Location Type no of items, Outlet Establishment Year.
## Tools Used
Microsoft Power BI
Data Modeling and DAX
Slicers for filtering (Outlet Size, Item Type, Location)
Various visualizations: bar charts, pie charts, donut charts, line charts.

##📈 Business Impact
This dashboard provides Blinkit stakeholders with a real-time, data-driven decision-support system for operational efficiency, product planning, and customer satisfaction improvement.
