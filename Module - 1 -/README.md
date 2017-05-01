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
If you grab a categorical field or text field and drag that on to the canvas, you'll get a table of results by dafault. This is because it's a textual data, and the easiest way of viewing all of those things is in a table, you can scroll up and down through them and by default it's shorted alphabetically. But we can also short it just clicking on the column name, for example by Revenue:
IMAGEN 12
You can also reorder the columns. If you wan to see the CountryZip between Manufacturer and Revenue, you can do it moving them from the Values field
IMAGEN 13
Another tabular visualization is the matrix. Here you can have different categories on the columns, as well as on the rows. Create a Matrix with the Manufacturer on the Rows, the Year on Columns and Units in the Values Field. That should look like this:
IMAGEN 14
Now we've got all of the units sold for each manufacturer, sorted by year. Notice that a new columns and a new row had been added, with the total units of each year and Manufacturer respectively.

## Scatter Chart
A really common visualization is the Scatter Chart. Let's take a look on how we can create it. We are going to compare the revenue and the units. So first of all, click on the Scatter Plot Visualization:
IMAGEN 15
Then select the axis, Revenue on the X Axis and Unis in the Y one. But you are not done. You'll see a dot in the middle of the chart because you are aggregating your total revenue and your total unit sales across all of your data. You need to specify another field in the details, for example the Segment. So now we can see for example that the Convenience has the highest revenue or that the productivuty sells the hisghest number of units.
We can also add a new dimension to our chart, adding the manufacturer field in the legend. By doing this, we'll see a bubble foe each manufacturer.

Now we are going to add another dimension and some colour. Put the Category field in the Legend and Segment again in the Size. Now we should have a chart like this:
IMAGEN 16
There is one more thing that we can show thats's really useful here. We can animate this chart over the time. Drag the year field and drop it in the Play Axis.
IMAGE 17
Now we can see diferent charts for each year and we can even see an animated year and see the evolution of the revenue and the units in all of these years.
If you click in one of the bubbles, you can see all of the previous bubbles. For example, go to 2006 an dclick in a random bubble. Ypu'll see a trace line of the previous revenues and units and if you then click in the play button, the trace will continue.
So as you can see, scatter plot a good way to compare three different measures on your X and Y axis, but you can also heck and track that and animate it over the time and get the idea of how the data is changing over year.


## Gauge and cards
The visualizations we've looked at have tipically been used to compare values across different categories our to compare two different values. However, if you're building a report, sometimes you want to just show a single KPI or a single metric just so that you can track that as it changes over time. We have a few different visuals for that. Graufes a really good one if you want to show progress towards a particular target, for example out total revenue. Select the Gauge visualization.
IMAGE 18
Now click on the revenue. By default the maximum value of the revenue will be the double of the total revenue. Here we have a variety of options to configure, in the Format tab. For instance, we can set a target value from the Gauge Axis. We can also set a maximum. Put your own values and you'll get a chart like this:
IMAGE 19

Another thing that we can do is to use a card visualization, which show us a numeric representation as come text. For instance, we'll represent the revenue. Select the Card Visualization and the Revenue:
IMAGE 20

We can also have a KPI visuals as well that can be really useful for showing this sort of imformation. This will show us an indicator and also a trend over the last few time periods of how that number has changed. Click on the KPI visualization and the in the Units Field:
IMAGE 21


