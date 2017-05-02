# Create Visualizations I
**Objective:** in this section we will explore the report. The aim is to learn how we can fulfill an empty report with enriched graphs.

Now that our data is imported and we know the basic features of the dashboard, we can start making our first visualizations. Let's create a new report: go to the left-hand bar menu and click on the dashboard *Canada sales data.xlsx*, inside the *DASHBOARDS* tab. In spite clicking in the dashboards tab, what we are doing is creating a new report, because the *REPORTS* section is empty.

![](/Module%201%20-%20Visualizations%20I/Images/1.PNG)

> NOTE: notice that two new columns have appeared in our table, *Month* and *Year*. This is very useful for making our visualizations. All of this information was in the *Date* field and Power BI creates them automatically for you. Power BI Desktop doesn't do that for you, because you have many different options of managing and transforming your data.



If you click on the *Save* button and enter a name, a new report will appear on the left-side menu.
These are the main sections when we create a report:
* Visualizations: where you can choose the most convenient visualization, such as bar char, scatter plot, tables, maps... We will cover almost all of them in this lab. You can also import a *custom visual*, clicking in the three dots on the right of the last *Visualization*, which are visualizations created by third party.
* Fields and Format tabs: they are right down the *Visualizations*. On the *Fields* tab you can put the values that you want in the axis of the graphs. and the *Format* tab is used to customize the visualization changing the colours, adding titles, changing the font size, etc...
* Fields: here you will find the database, divided in tables and in the tables you have the name of each column.
As you can see, you have a visualizations menu, , and you have the *Fields* menu. Here you'll have all of your tables with it's respectives columns. So let's create out first report!

![](/Module%201%20-%20Visualizations%20I/Images/2.PNG)

> NOTE: there are icons next to some fileds. There are three type of icons, the summatory, which means that it is a numeric field, a world icon, which means that there is data about countries on it and we could use it for making interactive maps and a calculator icon (not in this dataset). This icon appears when we make measurements in Power BI Desktop.



## Tables, Bar Chart and Pie Chart
Let's create the simplest chart, a table. Go to the Visualizations menu on the right-side and select the table. A new box will appear on the blank page.

![](/Module%201%20-%20Visualizations%20I/Images/3.PNG)

So now we can fill the table with some data. Remember that we have all of the columns of our database in the *Fields* section. So you just have to click in the little empty box on the field that you want in the table, for example, Revenue, and then Manufacturer. Now we can find in the table all the revenue of each manufacturer. You may probably can't see the numbers because of the font size. Go to the *Format tab (the brush icon) - General - Text Size. Notice that automatically Power BI makes the total revenue for you, in a new row. You can disable this option if you want.

![](/Module%201%20-%20Visualizations%20I/Images/4.PNG)

Let's see how easy is to create a graph. Click on the table that we have just created, and then in the visualizations, select the second one, the stacked column chart. Now we have the revenue in Canada, represented by Manufacturer.

![](/Module%201%20-%20Visualizations%20I/Images/5.PNG)

What do we have to do if we want to make another visualization with the same data, for example a pie chart? You just click in the chart that you have just created and then select the pie chart in the *Visualizations* menu. This is an easy way to compare the revenue of all manufacturers.

![](/Module%201%20-%20Visualizations%20I/Images/6.PNG)

Easy right? We can customize it a little bit from the Format menu, for example, turning on the *Legend*.

Let's do a bar chart Drag and drop *Units* and *Months* in the same box in the canvas, and a new *Clustered Column Chart* will appear. Your report should look like this:

![](/Module%201%20-%20Visualizations%20I/Images/6.1.PNG)

Let's see more visualizations.

## Bar Chart With Line
In order to visualize better the charts, create a new page here, in the *plus* button:

![](/Module%201%20-%20Visualizations%20I/Images/6.2.PNG)

Now we have a new challenge. We'll try to make a 4 dimension chart in a 2 dimension one. Let's see how we can do that. Select the Line and Staked column chart and fill the fields with the followings:

![](/Module%201%20-%20Visualizations%20I/Images/7.PNG)

What have we done here? For each year (X axis), we can see all of the revenue spent in that year (Y axis), which is represented by the whole bar. At the same time, we can compare it with the units sold in that year, represented with the line. And finally, we have a seggregation of the reveneue of each year, separated by the *Segment* field, in different colours. We can see which colour represents a segment in the legend above.

## Slicer
Here we introduce the Slicer option. This is used to filter our data, so that we can focus on individual fields. In this case, we will focus on each *Province*. How can we do this? First of all, create a new page on the report, then go to the visualizations pane and choose the slicer icon. Then click on the *Province* field.

![](/Module%201%20-%20Visualizations%20I/Images/8.PNG)

Now if we click in any of the provinces, all the charts will automaticlly update with the information of that particular province. You can filter the data with more than one option if you go to *Format - Selection Controls* and turn off the *Single Seleciton* option.

![](/Module%201%20-%20Visualizations%20I/Images/9.PNG)


## Maps and Treemaps
Power BI has also great mapping capabilities. It's very easy to represent our data in an interactive map, in order to look at the geographical relationships in the data. We are going to use embebbed Bing maps in the report, and customize them with our particular data. For example, let's see the units sold by province.

Open a new page, click on the *Map* visualization and then drag the province in the *Location* field and the Units in the Size field. This will show us a map with different shapes of circles, regarding the units sold in the provinces. We can also customize it with a legend. Drag and drop the province in the *Legend* field. We should see a map like this one:

![](/Module%201%20-%20Visualizations%20I/Images/10.PNG)


Now we are going to see how can we plot a Treemap. In the same page, drag and drop the *Units* and the *Manufacturer* and then select the *Treemap*. This is a graph very similar to the pie chart. We can see the proportion of units sold of each manufacturer ordered from maximun size (up - left) to minumum (right - down).

Why have we mixed this charts? because I wanted to show you that there is another way to filter our data. Try to click on one of the Provinces of the map and see how the TreeMap chart changes with the units sold of every manufacturer, in that particular province. If you customize it a littele bit, you should have something like this:

![](/Module%201%20-%20Visualizations%20I/Images/11.PNG)

[You can find more visualizations in Module 2](https://github.com/daorti/PowerBIWorkshop/tree/master/Module%202%20-%20Visualizations%20II)



