# Create Visualizations
Now that we know how the dashboard works and our data is imported, we can start making our first visualizations. For example, let's create a table with some data. First of all, go to the left-hand bar menu and click on the dashboard "Canada sales data.xlsx". In spite of clicking in the dashboards, what we are doing is creating a new report.
NOTE: notice that two new columns have appeared in our table, Month and Year. This is very useful for making our visualizations. All of this information was in the Date field, but Power BI makes it automatically for you. In POwer BI Desktop doesn't to that for you because you have many different options of managing and transforming your data.
IMAGEN 1
If you click on the "Save" button and enter a name, you will see that you'll have a new report on the left-side menu. Notice that you have a visualizations menu, where you can customize your graphs (choose the visualization, filter the data and change the format), and you have the "Fields" menu. Here you'll have all of your tables with it's respectives columns. So let's create out first report!
IMAGEN 2

## Table, bar and pie chart
EXPLICAR LOS SIBOLITOS AL LADO DE CADA FIELD
For creating the table, go to the Visualizations menu on the right-side and select the table. A new box will appear on the blank page.
IMAGEN 3
So now we can fill the table with some data. You just have to click in the box of the column that you want in the table, for example, Revenue, and Manufacturer. Now we can find in the table all the units sold by month. You'll likely can't see the numbers because of the font size, go to the format tab, - General - Text Size.
IMAGEN 4
Ok, let's see how easy is to create a graph. You just click on the table that we have just created, and then in the visualizations, select the second one, the stacked column chart. Now we have we have the revenue in Canada, represented by Manufacturer.
IMAGEN 5
What do we have to do if we want to make another visualization but with the same data, for example in a pie chart? You just click in the bar chart and then select the pie chart in the "Visualizations" menu.
IMAGEN 6
Easy right? We can customize it a little bit from the Format menu, turning on the Legend. You can also make the visualizations selecting the fields first. Try it yourseld! Drag and drop units and months in the same chart and a new Clustered Column Chart will appear. Your report should look like this:
IMAGEN 6.1
Let's continue with more complicated visualizations

## Bar chart with line
In order to visualize better the charts, create a new page here:
IMAGE OF NEW PAGE. NO ESTA HECHA
Now we have a new challenge. We'll try to make a 4 dimension chart in a 2 dimension one. Let's see how we can do that. Select the Line and Staked column chart and fill the fields with the followings:
IMAGEN 7
what have we done here? For each year we can see all of the revenue spent in that year, wich is represented by the whole bar. At the same time, we can compare it with the units sold in all of the years, represented with the line. And dinally, we can see in which segment we have gain that revenue, each year, represented for the colours in the legend.

## Slicer
Here we introduce the Slicer option. This is used to filter our data, so that we can focus on individual Provinces. How can we do this? Just go to the visualizations pane and choose the slicer icon. The click on the Province field
IMAGEN 8
Now if we click one of the provinces, all the charts will automaticlly update with the information of that province. You can filter the data with more than one option if you go to Format - Selection Controls and turn off the Single Seleciton option.
IMAGEN 9

## Maps and Treemaps
Open a new Page
Power BI has also great mapping capabilities. It's very easy to represent our data in an interactive map, in order to look at the geographical relationships in the data. For example, let's see the units sold by province. Click on the map visualization and then drag the province in the Location Field and the Units in the Size field. This will show us a map with different shapes of circles, regarding the units sold in the province. We can also customize it with a legend. Drag and drop the province in the legend. We should see a map like this:
IMAGEN 10
Now we are goind to see how can we plot a Treemap. In the same page, drag and drop the units and the manufacturer and then select the Treemap. This is a graph very similar to the pie chart. In this one we can see the proportion of units sold of each manufacturer ordered from maximun size (up - left) to minumum (right - down). Why have we mixed this charts? because there is another way to filter our data. Try to click one of the Provinces of the map and see how the TreeMap chart changes with the units sold of every manufacturer, but just in that province. IIf you customize ir a littele bit, you should have something like this:
IMAGEN 11

## Table and Matrix
