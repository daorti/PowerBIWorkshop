# Create Visualizations II

## Table and Matrix
If you grab a categorical field or text field and drag that on to the canvas, you'll get a table of results by dafault. This is because it's a textual data, and the easiest way of viewing all of those things is in a table, you can scroll up and down through them and by default it's shorted alphabetically. But we can also short it just clicking on the column name, for example by Revenue:

![](/Module%202%20-%20Visualizations%20II/Images/12.PNG)

You can also reorder the columns. If you wan to see the CountryZip between Manufacturer and Revenue, you can do it moving them from the Values field

![](/Module%202%20-%20Visualizations%20II/Images/13.PNG)

Another tabular visualization is the matrix. Here you can have different categories on the columns, as well as on the rows. Create a Matrix with the Manufacturer on the Rows, the Year on Columns and Units in the Values Field. That should look like this:

![](/Module%202%20-%20Visualizations%20II/Images/14.PNG)

Now we've got all of the units sold for each manufacturer, sorted by year. Notice that a new columns and a new row had been added, with the total units of each year and Manufacturer respectively.

## Scatter Chart
A really common visualization is the Scatter Chart. Let's take a look on how we can create it. We are going to compare the revenue and the units. So first of all, click on the Scatter Plot Visualization:

![](/Module%202%20-%20Visualizations%20II/Images/15.PNG)

Then select the axis, Revenue on the X Axis and Unis in the Y one. But you are not done. You'll see a dot in the middle of the chart because you are aggregating your total revenue and your total unit sales across all of your data. You need to specify another field in the details, for example the Segment. So now we can see for example that the Convenience has the highest revenue or that the productivuty sells the hisghest number of units.
We can also add a new dimension to our chart, adding the manufacturer field in the legend. By doing this, we'll see a bubble foe each manufacturer.

Now we are going to add another dimension and some colour. Put the Category field in the Legend and Segment again in the Size. Now we should have a chart like this:

![](/Module%202%20-%20Visualizations%20II/Images/16.PNG)

There is one more thing that we can show thats's really useful here. We can animate this chart over the time. Drag the year field and drop it in the Play Axis.

![](/Module%202%20-%20Visualizations%20II/Images/17.PNG)

Now we can see diferent charts for each year and we can even see an animated year and see the evolution of the revenue and the units in all of these years.
If you click in one of the bubbles, you can see all of the previous bubbles. For example, go to 2006 an dclick in a random bubble. Ypu'll see a trace line of the previous revenues and units and if you then click in the play button, the trace will continue.
So as you can see, scatter plot a good way to compare three different measures on your X and Y axis, but you can also heck and track that and animate it over the time and get the idea of how the data is changing over year.


## Gauge and cards
The visualizations we've looked at have tipically been used to compare values across different categories our to compare two different values. However, if you're building a report, sometimes you want to just show a single KPI or a single metric just so that you can track that as it changes over time. We have a few different visuals for that. Graufes a really good one if you want to show progress towards a particular target, for example out total revenue. Select the Gauge visualization.

![](/Module%202%20-%20Visualizations%20II/Images/18.PNG)

Now click on the revenue. By default the maximum value of the revenue will be the double of the total revenue. Here we have a variety of options to configure, in the Format tab. For instance, we can set a target value from the Gauge Axis. We can also set a maximum. Put your own values and you'll get a chart like this:

![](/Module%202%20-%20Visualizations%20II/Images/19.PNG)

Another thing that we can do is to use a card visualization, which show us a numeric representation as come text. For instance, we'll represent the revenue. Select the Card Visualization and the Revenue:

![](/Module%202%20-%20Visualizations%20II/Images/20.PNG)

We can also have a KPI visuals as well that can be really useful for showing this sort of imformation. This will show us an indicator and also a trend over the last few time periods of how that number has changed. Click on the KPI visualization and the in the Units Field:

![](/Module%202%20-%20Visualizations%20II/Images/21.PNG)
