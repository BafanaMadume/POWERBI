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

# Select the file data to import
* After the file has connected to Power BI Desktop, the Navigator window opens.
*  This window shows you the data that is available in your data source (the Excel file in this example).
*   You can select a table or entity to preview its contents, to ensure that the correct data is loaded into the Power BI model.
* Select the check box(es) of the table(s) that you want to bring in to Power BI. This selection activates the Load and Transform Data buttons as shown in the following image.

## Change the Source File
* You might have to change the location of a source file for a data source during development, or if a file storage location changes.

* Power Query provides many ways for you to accomplish this task, so that you can make this type of change when needed.

* Data source settings
* Query settings
* Advanced Editor

## Get Data From Relational Data Sources

if your organization uses a relational database for sales ,we can use Power Bi desktop to connect directly to the database instead of using exported flat files
* connecting Power Bi to your database will help you monitor the progress of your business and identify trends
* Power BI desktop can connect to many relational databases that are either in the cloud or on-premises.

## Connect To data in a Relational database

We can use the GET DATA feature in Power BI Desktop and select the applicable option for your relational database
![Screenshot 2024-05-15 132205](https://github.com/BafanaMadume/POWERBI/assets/141032267/d8fc0b26-d972-421c-9ce9-c9e8941c2d3c)

## SELECT DATA TO IMPORT
* After the database has been connected to Power BI Desktop, the Navigator window displays the data that is available in your data source (the SQL database in this example)
* Select the check box(es) of the table(s) that you want to bring in to Power BI Desktop, and then select either the Load or Transform Data option.

* ``LOAD`` = automatically load your data into a power BI model in its current state
* ``Transform Data`` =  Open your data in Microsoft Power Query, where you can perform actions such as deleting unnecessary rows or columns, grouping your data, removing errors, and many other data quality tasks

## IMPORT DATA BY WRITING AN SQL QUERY
we can import data by writing an sql query to specify only the tables and columns that one needs

## WRITE AN SQL STATEMENT
SQL stands for Structured Query Language and is a standardized programming language that is used to manage relational databases and perform various data management operations

* SQL query starts with a Select statement, which allows you to choose the specific fields that you want to pull from your database.
* FROM specifies the name of the table that you want to pull the data from.
* When using an SQL query to import data, try to avoid using the wildcard character (*) in your query. If you use the wildcard character (*) in your SELECT statement, you import all columns that you don't need from the specified table.
* WHERE clause. This clause will filter the rows to pick only filtered records that you want.

## CREATE DYNAMIC REPORTS WITH PARMETERS
* Dynamic reports are reports in which the data can be changed by a developer according to user specifications
* Dynamic reports are valuable because a single report can be used for multiple purposes.
* If you use dynamic reports, you'll have fewer individual reports to create, which will save organizational time and resources.
* You can use parameters by determining the values that you want to see data for in the report, and the report updates accordingly by filtering the data for you.
* Creating dynamic reports allows you to give users more power over the data that is displayed in your reports; they can change the data source and filter the data by themselves.

## Create Dynamic ReportsFor Individual Values
* To create a dynamic report, you first need to write your SQL query.Then use the Get data feature in Power BI Desktop to connect to the database

Now, you need to adjust the code in SQL query to assess your new parameter:

1. Right-click Query1 and then select Advanced editor.

2. Replace the existing value in the execute statement with an ampersand (&) followed by your parameter name (SalesPerson), as illustrated in the following image.
3. Make sure that no errors are shown at bottom of the window and then select Done.
4. To confirm that the query was run, you can run a test by selecting the parameter query and entering a new value in the Current Value box.
5. A warning icon might display next to the query. If so, select that query to view the warning message, which states that permission is required to run this native database query. Select Edit Permission and then select Run.
6. Select Close and Apply to return to the report editor.

Apply parameter to the Report
1. Select Edit queries > Edit parameters.
2. On the Edit Parameters window, enter a new value and then select OK.
3. Select Apply changes and then run the native query again.

## GET DATA FROM A NoSQL Database
A NoSQL database (also referred to as non-SQL, not only SQL or non-relational) is a flexible type of database that doesn't use tables to store data.

## Import a JSON file
* it is necessary to extract and normalize the data first .it is because the JSON data is often stored in a nested or unstructured format ,which makes it difficult to analyze or report on directly.
* Json data is often stored in a nested or unstructured format, which makes it difficult to analyze or report on directly
* The data must be extracted and normalized before you can report on them, so you need to transform the data before loading it into Power BI Desktop.
* After you've connected to the database account, the Navigator window opens, showing a list of databases under that account. Select the table that you want to import. 
* The preview pane only shows Record items because all records in the document are represented as a Record type in Power BI.

* Select the Edit button to open the records in Power Query.

In Power Query, select the Expander button to the right side of the Column1 header, which displays the context menu with a list of fields.
*  Select the fields that you want to load into Power BI Desktop, clear the Use original column name as prefix checkbox, and then select OK.

## GET DATA FROM ONLINE SERVICES
*  support their daily operations, organizations frequently use a range of software applications, such as SharePoint, OneDrive, Dynamics 365, Google Analytics
*  These applications produce their own data.
*  Power BI can combine the data from multiple applications to produce more meaningful insights and reports

### CONNECT TO DATA IN AN APPLICATION
*  connecting to data in an application, you would begin in the same way as you would when connecting to the other data sources: by selecting the Get data feature in Power BI Desktop. Then, select the option that you need from the Online Services category
*  you've selected Connect, you'll be asked for your SharePoint URL. This URL is the one that you use to sign into your SharePoint site through a web browser. 

## SELECT A STORAGE MODE
* The most popular way to use data in Power BI is to import it into a Power BI semantic model. Importing the data means that the data is stored in the Power BI file and gets published along with the Power BI reports.

#### The three different types of storage modes you can choose from:

* Import
* DirectQuery
* Dual (Composite)

access storage modes by switching to the Model view, selecting a data table, and in the resulting Properties pane, selecting which mode that you want to use from the Storage mode drop-down list.

### IMPORT MODE
* Import mode allows you to create a local Power BI copy of your semantic models from your data source.
*  Data refreshes can be scheduled or on-demand. Import mode is the default for creating new Power BI reports.

## DirectQuery mode
* **DirectQuery** option is useful when you don't want to save local copies of your data because your data won't be cached.
* you can query the specific tables that you'll need by using native Power BI queries, and the required data will be retrieved from the underlying data source
*  Using this model ensures that you're always viewing the most up-to-date data, and that all security requirements are satisfied.

## Dual (Composite mode)
*  Dual mode, you can identify some data to be directly imported and other data that must be queried.
* Any table that is brought in to your report is a product of both Import and DirectQuery modes.
*  Using the Dual mode allows Power BI to choose the most efficient form of data retrieval.

## Get data from Azure Analysis Services
* Azure Analysis Services is a fully managed platform as a service (PaaS) that provides enterprise-grade semantic models in the cloud
* use advanced mashup and modeling features to combine data from multiple data sources, define metrics, and secure your data in a single, trusted tabular semantic model.
* semantic model provides an easier and faster way for users to perform ad hoc data analysis using Power BI

* Getting data from Azure Analysis Services server is similar to getting data from SQL Server, in that you can:

  - Authenticate to the server.
  - Pick the model you want to use.
  - Select which tables you need.

  Notable differences between Azure Analysis Services and SQL Server are:

Analysis Services models have calculations already created.
If you don’t need an entire table, you can query the data directly. Instead of using Transact-SQL (T-SQL) to query the data, like you would in SQL Server, you can use multi-dimensional expressions (MDX) or data analysis expressions (DAX).

## Fix Performance issues
* Power BI provides the Performance Analyzer tool to help fix problems and streamline the process.
* When you create preliminary visuals and filters, you notice that some tables are queried faster than others, and some filters are taking longer to process compared to others.

## Optimize performance in Power Query
* The variety of data sources that Power Query offers is wide, and the performance tuning techniques for each source are equally wide.
*  Good SQL Server performance tuning techniques include index creation, hardware upgrades, execution plan tuning, and data compression.
*  **Power Query ** takes advantage of good performance at the data source through a technique called Query Folding.

## QUERY FoLDING
The query folding within Power Query Editor helps you increase the performance of your Power BI reports.
**Query folding** = the process by which the transformations and edits that you make in Power Query Editor are simultaneously tracked as native queries, or simple Select SQL statements, while you're actively making transformations.
* The reason for implementing this process is to ensure that these transformations can take place in the original data source server and don't overwhelm Power BI computing resources
* You can use Power Query to load data into Power BI. Then use Power Query Editor to transform your data, such as renaming or deleting columns, appending, parsing, filtering, or grouping your data.
* when you load your data, the transformations take place independently in the original source, this ensures that performance is optimized in Power BI

**Benefits to query folding**

* **More efficiency in data refreshes and incremental refreshes.** When you import data tables by using query folding, Power BI is better able to allocate resources and refresh the data faster because Power BI doesn't have to run through each transformation locally.

* **Automatic compatibility with DirectQuery and Dual storage modes**. All DirectQuery and Dual storage mode data sources must have the back-end server processing abilities to create a direct connection, which means that query folding is an automatic capability that you can use. If all transformations can be reduced to a single Select statement, then query folding can occur.

* Query Diagnostics
determine what bottlenecks may exist while loading and transforming your data, refreshing your data in Power Query, running SQL statements in Query Editor, and so on.

To access query diagnostics in Power Query Editor, go to Tools in the Home ribbon. When you're ready to begin transforming your data or making other edits in Power Query Editor, select Start Diagnostics in the Session Diagnostics section. When you're finished, make sure that you select Stop Diagnostics.

## Resolve Data import Errors

When importing data into Power BI, you may encounter errors resulting from factors such as:
* Power BI imports from numerous data sources
* Each data source might have dozens (and sometimes hundreds) of different error messages.
* Other components can cause errors, such as hard drives, networks, software services, and operating systems
* Data often can't comply with any specific schema

## Query Timeout Expired
Relational source systems often have many people who are concurrently using the same data in the same database. Some relational systems and their administrators seek to limit a user from monopolizing all hardware resources by setting a query timeout.

## Power BI Query Error: Timeout expired
This error indicates that you’ve pulled too much data according to your organization’s policies. Administrators incorporate this policy to avoid slowing down a different application or suite of applications that might also be using that database.

## DATA TYPE ERRORS
Sometimes, when you import data into Power BI, the columns appear blank,The resolution to this error is unique to the data source.

Instead of using this query:

SELECT CustomerPostalCode FROM Sales.Customers

Use this query:

SELECT CAST(CustomerPostalCode as varchar(10)) FROM Sales.Customers

By specifying the correct type at the data source, you eliminate many of these common data source errors.

You may encounter different types of errors in Power BI that are caused by the diverse data source systems where your data resides.

---
---
---

# CLEAN ,TRANSFORM ,AND LOAD DATA IN POWER BI
When examining the data, you discover several issues, including:

- A column called Employment status only contains numerals.
- Several columns contain errors.
- Some columns contain null values.
- The customer ID in some columns appears as if it was duplicated repeatedly.
- A single address column has combined street address, city, state, and zip code.

### Clean data has the following advantages:

- Measures and columns produce more accurate results when they perform aggregations and calculations.
- Tables are organized, where users can find the data in an intuitive manner.
- Duplicates are removed, making data navigation simpler. It will also produce columns that can be used in slicers and filters.
- A complicated column can be split into two, simpler columns. Multiple columns can be combined into one column for readability.
- Codes and integers can be replaced with human readable values.

## SHAPE THE INITIAL DATA
- Power Query Editor in Power BI Desktop allows you to shape (transform) your imported data.
- accomplish actions such as renaming columns or tables, changing text to numbers, removing rows, setting the first row as headers

### GET STARTED WITH POWER QUERY EDITOR
* start shaping your data, open Power Query Editor by selecting the Transform data option on the Home tab of Power BI Desktop
* The data in your selected query displays in the middle of the screen and, on the left side, the Queries pane lists the available queries (tables)
*  Power Query Editor only makes changes to a particular view of your data, so you can feel confident about changes that are being made to your original data source.

## STEPS IN SHAPING YOUR DATA

## 1. IDENTIFY COLUMN HEADERS AND NAMES
*  first step in shaping your initial data is to identify the column headers and names within the data and then evaluate where they are located to ensure that they are in the right place
*  When you have identified where the column headers and names are located, you can make changes to reorganize the data.

### PROMOTE HEADERS
* When a table is created in Power BI Desktop ,Power Query Editor assumes that all data belongs in table rows.
* Promote headers in two ways:
   1. By selecting the Use First Row as Headers option on the Home tab
   2. By selecting the drop-down button next to Column1 and then selecting Use First Row as Headers.
 
 ## 2.RENAME COLUMNS
 The next step in shaping your data
 * is to examine the column headers , might discover that one or more columns have the wrong headers, a header has a spelling error, or the header naming convention is not consistent or user-friendly.

###  Can rename column headers in two ways
1. Rename column headers in two ways.
2. Alternatively, you can double-click the column header and overwrite the name with the correct name
3. Work around this issue by removing (skipping) the first two rows and then renaming the columns to the correct name.

### REMOVE TOP ROWS
*  you might need to remove some of the top rows,are blank or if they contain data that you do not need in your reports
*  To remove these excess rows, select Remove Rows > Remove Top Rows on the Home tab.

### REMOVE COLUMNS
key step in the data shaping process is to remove unnecessary columns
1.One way to remove columns would be to limit the column when you get data from data source. 

* Removing columns at an early stage in the process rather than later is best, especially when you have established relationships between your tables.
* Removing unnecessary columns will help you to focus on the data that you need and help improve the overall performance of your Power BI Desktop semantic models and reports

**Can remove columns in two ways.** 
1. To select the columns that you want to remove and then, on the Home tab, select Remove Columns.
2. you can select the columns that you want to keep and then, on the Home tab, select Remove Columns > Remove Other Columns.

## PIVOT COLUMNS
* If the data that you are shaping is flat (in other words, it has lot of detail but is not organized or grouped in any way)
* Pivot Column feature to convert your flat data into a table that contains an aggregate value for each unique value in a column. For example, you might want to use this feature to summarize data by using different math functions such as ,``**Minimum**``, ``**Maximum**``,`` **Median**``, ``**Average**``, or ``**Sum**``.

* On the Transform tab, select Transform > Pivot Columns.

* Power Query Editor records all steps that you take to shape your data, and the list of steps are shown in the Query Settings pane.
* If you have made all the required changes, select Close & Apply to close Power Query Editor and apply your changes to your semantic model.

## SIMPLIFY THE DATA STRUCTURE

### Rename A Query
good practice to change uncommon or unhelpful query names to names that are more obvious or that the user is more familiar with
* if you import a product fact table into Power BI Desktop and the query name displays as FactProductTable, you might want to change it to a more user-friendly name, such as Products

### REPLACE VALUES
* Replace Values feature in Power Query Editor to replace any value with another value in a selected column.
*  Query Settings pane. When you have completed all steps that you want to take, you can select Close & Apply to close Power Query Editor and apply your changes to your data model.

### REPLACE NULL VALUES
* If the value stays null, the averages will not calculate correctly. One solution would be to change the nulls to zero, which will produce the more accurate freight average

### REMOVE DUPLICATES
*  Can also remove duplicates from columns to only keep unique names in a selected column by using the Remove Duplicates feature in Power Query

### BEST PRACTICES FOR NAMING TABLES ,COLUMNS AND VALUES

* Naming conventions for tables, columns, and values have no fixed rules; however, we recommend that you use the language and abbreviations that are commonly used within your organization.
* A best practice is to give your tables, columns, and measures descriptive business terms and replace underscores ("_") with spaces.
* Be consistent with abbreviations, prefixes, and words like "number" and "ID."
* Removing prefixes or suffixes that you might use in table names and instead naming them in a simple format, you will help avoid confusion.
* When replacing values, try to imagine how those values will appear on the report. Values that are too long might be difficult to read and fit on a visual.
* Values that are too short might be difficult to interpret.
* Avoiding acronyms in values is also a good idea, provided that the text will fit on the visual.

## EVALUATE AND CHANGE COLUMN DATA TYPES
* When importing a table from any data source, Power BI Desktop automatically starts scanning the first 1,000 rows (default setting) and tries to detect the type of data in the columns.
* You have a higher chance of getting data type errors when you're dealing with flat files, such as comma-separated values (.CSV) files and Excel workbooks (.XLSX).
* Because data was entered manually into the worksheets and mistakes were made.because data was entered manually into the worksheets and mistakes were made.

* best practice is to evaluate the column data types in Power Query Editor before you load the data into a Power BI semantic model

## IMPLICATIONS OF INCORRECT DATA TYPES
* Incorrect data types will prevent you from creating certain calculations, deriving hierarchies, or creating proper relationships with other tables.
* Another issue with having an incorrect data type applied on a date field is the inability to create a date hierarchy, which would allow you to analyze your data on a yearly, monthly, or weekly basis.

## CHANGE THE COLUMN DATA TYPE
* **Power Query Editor**, you can change the column data type in two ways.
* One way is to select the column that has the issue, select Data Type in the Transform tab, and then select the correct data type from the list.

## EVALUATE AND CHANGE COLUMN DATA TYPES

* When you import a table from any data source, Power BI Desktop automatically starts scanning the first 1,000 rows (default setting) and tries to detect the type of data in the columns.
You have a higher chance of getting data type errors when you're dealing with flat files, such as comma-separated values (.CSV) files and Excel workbooks (.XLSX), because data was entered manually into the worksheets and mistakes were made.
* Another issue with having an incorrect data type applied on a date field is the inability to create a date hierarchy, which would allow you to analyze your data on a yearly, monthly, or weekly basis.
* It's a best practice to use a date table and turn off the auto date/time to get rid of the auto generated hierarchy.

## CHANGE THE COLUMN DATA TYPE
*  can change the data type of a column in two places: in ``**Power Query Editor**`` and in the ``**Power BI Desktop Report**`` view by using the column tools.
*  best to change the data type in the Power Query Editor before you load the data

### CHANGE THE COLUMN DATA TYPE IN POWER QUERY EDITOR
*  Power Query Editor, you can change the column data type in two ways
  1. Is to select the column that has the issue, select Data Type in the Transform tab, and then select the correct data type from the list.
![Screenshot 2024-05-31 114033](https://github.com/BafanaMadume/POWERBI/assets/141032267/ce0c5b6f-d3ea-4c00-a958-dec893a5c9fc)

2.  is to select the data type icon next to the column header and then select the correct data type from the list.
![Screenshot 2024-05-31 114344](https://github.com/BafanaMadume/POWERBI/assets/141032267/81066254-c559-4bc6-a6b5-fc2b534df016)


