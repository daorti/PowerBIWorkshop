# Module - 0 Exploring the portal
**Objective:** In this module we will see the different components of portal. The aim is to get some insights about them and highlight the most important ones.

## The Dashboard

The main features are:

1) Left-hand side
2) Icons pane
3) Q&A box
4) Help buttons
5) Title of the pane
6) Office 365 indicator
7) Button for the main page of Power BI
8) Some additional actions

 ![](/Module%200%20-%20Exploring%20the%20portal/Images/theDashboard.png)


## Left-hand side menu
Here we can find all of the sections of the Power BI Service. What can they do for us?
* Favourites: we can add dashboards, reports and databases to that section to enable quick acces to our most used resources.
* Recent: here you can find the last activity of the choosen workspace.
* Applications: we won't focus on this section, but it is used to packetize Power BI resources, such as dashboards, reports or data and sharing them to a customer's Power BI Service.
* Shared with me: all of the content shared in your company, related to Power BI is in this blade.
* Workspaces: The content in Power BI is organized in workspaces. This enables you to classify all of your works, for example in departments or in teams.

 ![](/Module%200%20-%20Exploring%20the%20portal/Images/workspaces.png)



## Create a workspace
If you have started this lab with other colleagues, it's possible to create a unique workspace for all of you, and you can share every new content in the same workspace. It is recomended to start using the sharing options because it is one of the most powerful features of Power BI.
So go to the left-hand side menu, click on **Workspaces** and select **Create app workspace**. A new blade will appear on the right hand. Write a name group and an ID. Remember that the ID must be unique. Invite colleagues to the dashboard and click **Save**.

![](/Module%200%20-%20Exploring%20the%20portal/Images/creatingWorkspace.png)
 
After that, set the workspace to private in order to share the content only with the people that you want. In the next question click on the option that enables the other participants of the dashboard to not only view the content, but edit it as well.
And finally add the members of your team. Right after that, a new workshop appears in the left-hand side of the portal

![](/Module%200%20-%20Exploring%20the%20portal/Images/createdWorkspace.png)

Invited members of this workshop will receive an e-mail with a link to the new workshop.

### Datasets
Here are the data that you can import to the Power BI Service or connect from other sources. You can add [different kind of data](https://powerbi.microsoft.com/en-us/documentation/powerbi-service-get-data/).

So now we can import a Dataset. Click the button "Get Data", then select Files, and click again in Local File.

![](/Module%200%20-%20Exploring%20the%20portal/Images/getData.png)

Select the Canada sales data.xlsx and finally click in import Excel into Power BI if we want o create some graphs with it. The other option is just for visualizing the Excel in a Workbook. 

### Reports
They are one or more pages of visualizations (charts, graphs, treemaps and many many more). All of the visualizations on a report come from a single dataset. You can create a report from the scratch or a collegue can share a report with you. The other members of the workshop will see the same databases and they can start working with it from their own dasboard. One report can be associated with multiple dashboards.

### Dashboards
A dashboard is something you create or something a colleague creates and shares with you. It is a single canvas that contains zero or more tiles and widgets. Each tile displays a single visualization that was created from a dataset and pinned to the dashboard.

### Q&A question box.
If you click in the dashboard you've just created importing the dataset, you can make queries in natural language, for example, you can ask:

![](/Module%200%20-%20Exploring%20the%20portal/Images/QandA.PNG)

### Quick Insights
First of all, we need to know what the HoL is about, and the best way to do that is taking a look to the dataset. Please open the Excel and see the type of columns that we have.

We can also see some graphs or statistics from the portal. From the left-side bar, click in the workspace - DATASETS, and click in the three dots next to the dataset name. A new blade will appear. Select VIWE INSIGHTS. Wait a few seconds and you'll see some interesting graphs that Power BI make for you without teaching it anything. 

Ok so in this dataset we can see statistics about sales of products, sold in Canada. We have several information, such as the Product ID, the province where it is sold, the revenue produced for that sell, units sold there and when whas it sold.

[Let's create some visualizations of our new data](https://github.com/daorti/PowerBIWorkshop/tree/master/Module%201%20-%20Visualizations%20I)
