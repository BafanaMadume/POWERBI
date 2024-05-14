# POWERBI

# MICROSOFT POWER BI

is a complete reporting solution that offers ``data preparation``,``data visualization`` ,``disttribution and management`` through development tools and an online

* Power BI can scale from simple reports using a single data source to reports requiring complex data modeling and consisten themes
* we use power bi to create stunning,interactive reports to serve as the analytics and decision engine behind group projects
* It is an essential tool to data analysts and their organization,all data professionals benefit from understanding how Power bi works to explore and present data insights within the organization

## USING POWER BI
For Creating reports with Power BI ,we need the three primary components to Power BI
1.`` Power BI Desktop`` (desktop application)
2. ``Power BI service`` (online platform)
3. ``Power BI Mobile`` (cross-platform mobile app)

* We can access Power BI service at https://app.powerbi.com/
* Power Bi mobile allows consumers to view reports in a mobile-optimized format

* ![Screenshot 2024-05-13 134259](https://github.com/BafanaMadume/POWERBI/assets/141032267/2549b0ae-62f5-4895-a7c8-e5707aa8c7d7)

## EXPLORE THE FLOW OF POWER BI
* we start with Power BI desktop to connect to data and create the report,then you publish the report to the Power BI service and distribute to consumers

* THE POWER BI FLOW:
1. Connect to data with Power Bi Desktop
2. Transform and model data with Power BI Desktop
3. Create visualizations and reports with Power Bi Desktop
4. Publish report to Power BI service
5. Distribute and manage reports in the Power BI service

* From Power BI it allows us to create high-level dashboards that drill down to reports and apps to easily group related reports to users in a simple format.

## BUILDING BLOCKS OF POWER BI
* 2 Building Blocks of Power BI
  1. Semantic models
  2. Visualizations

## 1.CREATE A SEMANTIC MODEL
Semantic model consists of all connected data ,transformations,relationships and calculations. 
* we first connect to ``data`` ,``transform data`` ,and ``create relationships and calculations`` to create a semantic model
* Connect to as many data sources that you need,then clean and transform the data to your needs,
* Add relationships between tables and calculations to extends the semantic model

## CREATE VISUALIZATIONS IN A REPORT
* you add it to canvas for a report page,choose your visuaization to build pages in your report
* valuable features of power bi reports is the interactivity between visuals.where consumers can select different data points in the visual and see how that affects the other visualsj

## CREATE A DASHBOARD
You can also create dashboards after you,ve published a report.In a way dahsboards consists of a single page  made up of tiles.Add tiles to a dashboard by pinning a visual in a report to the dashboard.Tiles aren't interactive like visuals ,so in a way when a user interacts with the tile ,they go to the underlying report for more information
* Dashboards are an excellent way to provide high-level information to consumers
* Power BI Service ,We can distribute content

## Organize Items With WorkSpaces
- When publishing any report ,you must choose a workspace.My workspace is ideal only for testing ,whenever you want to share content with other individuals we create and use a shared workspace.

Questions on Power BI

1. What is the common flow of activity in Power BI?
   = CReate a report in power bi desktop,share it to the power bi service and interact with reports in the service and power bi mobile

2. Which of the following are building blocks of Power BI?
   = Semantic models and visualizations

3. What is a collection of reports and dashboards called in Power BI?
   = An App

Summary 
Power Bi offers a complete data analytics solution that includes data preparation ,visualization, and distribution.Semantic models and visualizations are the building blocks of power BI

* ``Power BI Desktop`` = for creating ``semantic models`` and ``reports with visualizations``.
* ``Power BI SERVICE`` = creating dashboards from published reports and distributing content with apps
* ``Power BI Mobile`` = for on the go access to the power Bi service content ,designed for mobile

# Build  A BASIC DASHBOARD

### Steps we need to follow

* ``Prepare Your Data`` : Prepare data ato ensure that it is in a format that Power Bi can easily consume
* ``Build A Report`` : Report contains visuals that you want to include in your dashboard depending on the scenario can be built in either Power Bi Desktop or using Power BI service.
* ``Pin the Report visuals to a dashboard``: Dashboards are the primary element that users use for viewing data.it includes data from multiple reports as needed
* ``Share a link to the dashboard`` any users with link and necessary permissions are easily able to view and interact with the data

## Knowledge check
1. Power BI helps with which of the following business processes?
   = Analyzing and displaying data
2. What can Power BI do to help you effectively use your data?
   - analyze sales data to better allocate resources and placr orders,optimizing operations
   - Analyze customer data to better target and promote specific items to specific customers
3. What are the three modalities of Power BI designed to let people create, share, and consume business insights in the way that serves them, or their role, most effectively?
   = Desktop ,service and mobile Apps
4. What is the purpose of Power BI's insights feature?
   = To easily identify insights such as anomalies and trends in your data


# EXPLORE WHAT POWER BI CAN DO
Power Bi can help make your job easier and more effective at the same time 

How To Know if you're a power  BI consumer
![Screenshot 2024-05-14 111634](https://github.com/BafanaMadume/POWERBI/assets/141032267/96353a36-1923-40eb-b6d7-d1a54a67e35f)

# Open and view the dashboard and report

1. Select one of the column chart or line chart tiles to open the detailed report.

- To return to the dashboard, select the back arrow of your browser.

## Create an Alert

- Select Manage alerts
  
- Select + Add alert rule.

- Scroll down to the Threshold field and type in 49000.

- Select the checkbox for At most every 24 hours.

- Select the checkbox for Send me email, too.

- Select the Save and close

---
# GET DATA FROM FILES
* One possible file format is a ``flat file`` .A flat file is a type of file that has only one data table and every row of data is in the same structure,the file does not contain hierarchies
* comma-separated values (.csv)
* delimited text(.txt)
* Fixed width files

Power BI Desktop allows one to get data from many types of files,the list is available under options when you use the **Get Data** feature un Power BI Desktop.

## FLAT FILE LOCATION
the first step is to determine which file location one wants to use to export and store your data

* **Local** = we import data from a local file into powerBI.The file is not moved into Power BI ,and a link does not remain to it.
  -A new Semantic model is created in Power BI and data from the excel file is loaded into it
  
* **OneDrive*** - Personal = You can use data from files on a personal OneDrive account, and get many of the same benefits that you would with OneDrive for Business. However, you'll need to sign in with your personal OneDrive account, and select the Keep me signed in option. Check with your system administrator to determine whether this type of connection is allowed in your organization.

* **SharePoint** -Team Sites Saving your Power BI Desktop files to SharePoint Team Sites is similar to saving to OneDrive for Business. The main difference is how you connect to the file from Power BI. You can specify a URL or connect to the root folder.
