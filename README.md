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

* the change that you make to the column data type is saved as a programmed step.The Step is called ``Changed Type `` and it will be iterated every time the data is refreshed.


## COMBINE MULTIPLE TABLES INTO A SINGLE TABLE

* WHEN WE HAVE THE ABILITY TO COMBINE QUERIES IT IS POWERFUL because it allows one to append or merge different tables or queries together

* can combine tables into a single table in the following circumstances:
  - Too many tables exist, making it difficult to navigate an overly complicated semantic model.
  - Several tables have a similar role.
  - A table has only a column or two that can fit into a different table.
  - You want to use several columns from different tables in a custom column.
 
  Two ways of combining ,we have ``**Merging**`` and ``**Appending**``

  ## APPEND QUERIES
  * when you append queries ,you'll be adding rows of data to another table or query
  *  When you merge queries, you'll be adding columns from one table (or query) into another.
  *  To merge two tables, you must have a column that is the key between the two tables.

* the pertinent columns that you require in your combined table must be named the same in your original data tables to see one consolidated view.
* Before you begin combining queries, you can remove extraneous columns that you don't need for this task from your tables.
* To complete this task, format each table to have only four columns with your pertinent information, and rename them so they all have the same column headers: ID, company, name, and phone.
* After you have finished reformatting, you can combine the queries
* **On the Home tab on the Power Query Editor ribbon, select the drop-down list for Append Queries. You can select Append Queries as New, which means that the output of appending will result in a new query or table, or you can select Append Queries, which will add the rows from an existing table into another**

## MERGE QUERIES
* When you merge queries, you're combining the data from multiple tables into one based on a column that is common between the tables.

* ``**Left Outer**`` - Displays all rows from the first table and only the matching rows from the second.

* ``**Full Outer**`` - Displays all rows from both tables.

* ``**Inner - Displays**`` the matched rows between the two tables.

## PROFILE DATA IN POWER

* Profiling data is about studying the nuances of the data: determining anomalies, examining and developing the underlying data structures, and querying data statistics such as row counts, value distributions, minimum and maximum values, averages.
* This concept is important because it allows you to shape and organise the data so that interacting with the data is structured and contained within the tables

## EXAMINE DATA STRUCTURES
* you can view current semantic model under the MODAL tab on Power BI Desktop
* Model tab  can edit specific column and table properties by selecting a table or columns,
* Transform the data by using the Transform Data button, which takes you to Power Query Editor

## FIND DATA ANOMALIES AND DATA STATISTICS

* After a creation of a connection to a data source and have selected **Transform Data** you are brought to Power Query Editor
* Determining what those anomalies are can help you identify what the normal distribution of your data looks like and whether specific data points exist that you need to investigate further.
* Power Query Editor determines data anomalies by using the Column Distribution feature.

* Select View on the ribbon, and under Data Preview, you can choose from a few options.
* To understand data anomalies and statistics ,select the **Column Distribution**,Column Quality and column profile options

* ``Column Distribution``
=  shows you the distribution of the data within the column and the counts of distinct and unique values, both of which can tell you details about the data counts.
* Distinct values are all the different values in a column, including duplicates and null values, while unique values do not include duplicates or nulls
*  distinct in this table tells you the total count of how many values are present, while unique tells you how many of those values only appear once.

*  ``Column Profile``
*   gives you a more in-depth look into the statistics within the columns for the first 1,000 rows of data.
*   This column provides several different values, including the count of rows, which is important when verifying whether the importing of your data was successful.

*  ``Column Statistics``
*  will also include how many zeroes and null values exist, along with the average value in the column
*  the standard deviation of the values in the column, and how many even and odd values are in the column.
*  These statistics give you an idea of the distribution of data within the column, and are important because they summarize the data in the column and serve as a starting point to determine what the outliers are.

## USE ADVANCED EDITOR TO MODIFY M code
* Each time you shape data in Power Query, you create a step in the Power Query process.
* Those steps can be reordered, deleted, and modified where it makes sense
*  The M language is always available to be read and modified directly
*  After creating steps to clean data, select the View ribbon of Power Query and then select Advanced Editor.


Questions
1. What is a risk of having null values in a numeric column? =
=AVERAGE takes the total and divides by the number of non-null values. If NULL is synonymous with zero in the data, the average will be different from the accurate average.

2.  If you have two queries that have different data but the same column headers, and you want to combine both tables into one query with all the combined rows, which operation should you perform?
   = Append will take two tables and combine it into one query. The combined query will have more rows while keeping the same number of columns.

3.  Which of the following selections aren't best practices for naming conventions in Power BI?
  = Abbreviations lead to confusion because they're often overused or not universally agreed on.

# MODEL DATA WITH POWER BI
* what a Power BI semantic model is, which data loading approach to use, and how to build out your semantic model to get the insights you need.
* prepare for the Microsoft Certified: Data Analyst Associate certification.

### INTRODUCTION
* the semantic model underpins report and dashboard development.
* To produce the right reports and dashboards, you should have a clear understanding of the questions that your report and dashboard users will ask.

* When developing the model, you will complete the following tasks:
  - Connect to data
  - Transform and prepare data
  - Define business logic by adding Data Analysis Expressions (DAX) calculations.
  - Publish the model to Power BI
 
 * A semantic model can be developed in many ways, yet one or several of those ways are more optimal.
 *  Optimal models are important for delivering good query performance and for minimizing data refresh times and the use of service resources, including memory and CPU


## STAR SCHEMA DESIGN
* A single-table model can be a simple design, perhaps one that's suitable for a data exploration task or proof of concept
* An optimal model adheres to star schema design principles.
* Star schema refers to a design approach that's commonly used by relational data warehouse designers because it presents a user-friendly structure and it supports high-performance analytic queries
* This design principle is called a star schema because it classifies model tables as either fact or dimension

## Fact Tables

* Role of a fact table is to store an accumulation of rows that represent observations or events that record a specific business activity

## Dimension Tables
* Dimension tables describe your business entities, which commonly represent ``people``, ``places``, ``products``, or ``concepts``.
*  Date dimension table, which contains one row for each date, is a common example of a concept dimension table.columns in dimension tables allow filtering and grouping of fact table data.
*  Each dimension table must have a unique column, which is referred to as its key column, A unique column doesn't contain duplicate values and it should never have missing values
*  Product dimension table ,the column could be named **ProductKey** or **ProductID**, additional columns will store descriptive values

## Analytic queries
* analytic query is a query that produces a result from a semantic model.
* Each Power BI visual, in the background, submits an analytic query to Power BI to query the model.
*  The analytic query is written as a Data Analysis Expressions (DAX) query statement.
*  analytic query has three phases that are implemented in the following order
  
  1. **Filter** =it targets the data of relevance , Filtering is also applied in the background when row-level security (RLS) is enforced.
 
  2.**Group** = or dicing, divides query results into groups,
 
  3. **Summarize** = numeric columns are summarized by using summarization methods (sum, count, and many others). These methods are simple summarizations. More complex summarizations, like a percent of grand total, can be achieved by defining measures that are written in DAX.

 ![Screenshot 2024-06-04 130156](https://github.com/BafanaMadume/POWERBI/assets/141032267/280b1292-fefd-4621-87a7-85930507a8cd)

# Configure Report Visuals
* Report authors produce report designs by adding report visuals and other elements to pages,Other elements include text boxes, buttons, shapes, and images. Each of these elements is configured independently of semantic model fields.

* Fields is a collective term that is used to describe a model resource that can be used to configure a visual. The three different model resources that are fields include:

- Columns
- Hierarchy levels
- Measures

## COLUmNS 
*  columns to filter, group, and summarize column values. Summarizing numeric columns is common, and it can be done by using sum, count, distinct count, minimum, maximum, average, median, standard deviation, or variance.
*  also summarize text columns by using first (alphabetic order), last, count, or distinct count. Additionally, you can summarize date columns by using earliest, latest, count, or distinct count.

## HIERARCHY LEVELS
* hierarchy levels are based on columns, they can be used to filter and group but not to summarize.
* Report authors can summarize the column that the hierarchy level is based on, provided that it's visible in the Fields pane.

## MEASURES
* Measures are designed to summarize model data; they can't be used to group data.
* measures can be used to filter data in one special case: to use a measure to filter a visual when the visual displays the measure and the filter is a visual-level filter (so, not a report or page-level filter).
* a measure filter is applied after the analytic query has summarized data.

questions

1. In a Power BI Desktop model design, which type of object do you create to connect multiple tables?
   - A relationship connects two tables together to allow filtering and further analysis.

2.  Which of the following statements is correct regarding a star schema design?
   -  Fact tables store accumulations of business events, like sales orders or currency exchange rates.

3. In what order does an analytic query implement its phases?
   -  Filter is used to first restrict the data to query. Group then divides the query result into groups. Summarize then produces single value aggregations for each group.


# Choose a Power B model framework
 Microsoft continues to make deep investments in enterprise **business intelligence (BI)**. **Azure Analysis Services (AAS)** and **SQL Server Analysis Services (SSAS)** are based on mature BI data modeling technology used by countless enterprises.

## DESCRIBE POWER BI model Fundamentals

* ``Data model``
* ``Power Bi dataset``
* ``Analytic query``
* ``Tabular model``
* ``Star schema design``
* ``Table storage mode``
* ``Model framework``

### Data Model
* Power BI data model is a query-able data resource that’s optimized for analytics.
* Reports can query data models by using one of two analytic languages: **Data Analysis Expressions (DAX)** or **Multidimensional Expressions (MDX)**

### POWER BI DATASET
* We develop a Power BI model in a  Power BI Desktop,
* once published to a workspace in the Power BI service, it’s then known as a dataset
* ``Dataset``is a Power BI artifact that’s a source of data for visualizations in Power BI reports and dashboards.

### Analytic query
* Power BI reports and dashboards must query a dataset.
* An analytic query produces a query result from a model that’s easy for a person to understand, especially when visualized.
* An analytic query has three phases that are executed in this order
1. Filter
2. Group
3. Summarize

**Filtering** =  (sometimes known as slicing) narrows down on a subset of the model data.Filter values aren’t visible in the query result analytic queries apply filters because it’s common to filter by a time period, and usually other attributes.
* In a Power BI report, you can set filters at report, page, or visual level.
* Report layouts often include slicer visuals to filter visuals on the report page.

## Star schema design
* Star schema design is a mature modeling approach widely adopted by relational data warehouses. It requires you to classify model tables as either dimension or fact
* Dimension tables describe business entities; the things you model. Entities can include products, people, places, and concepts including time itself. 
A fact table contains dimension key columns that relate to dimension tables, and numeric measure columns
A fact table forms the center of a star, and the related dimension tables form the points of the star.

## Table Storage Mode
* **import** = Queries retrieve data that’s stored, or cached, in the model
* **DirectQuery** - Queries pass through to the data source
* **Dual** - Queries retrieve stored data or pass through to the data source .Power Bi determines the most efficient plan ,striving to use cached data whenever possible

## MODEL FRAMEWORK
* Table storage mode settings determine the model framework, which can be either import, DirectQuery, or composite.
*  import model comprises tables that have their storage mode property set to Import.
*  DirectQuery model comprises tables that have their storage mode property set to DirectQuery

## Determine when to develop an import model
* import model comprises tables that have their storage mode property set to Import. It includes calculated tables, which you define with a DAX formula.
* Support all Power BI data source types, including databases, files, feeds, web pages, dataflows, and more.
* Can integrate source data. For example, one table sources its data from a relational database while a related table sources its data from a web page.
* Support all DAX and Power Query (M) functionality.
* Support calculated tables.
* Deliver the best query performance. That’s because the data cached in the model is optimized for analytic queries (filter, group, and summarize) and the model is stored entirely in memory.

## DETERMINE WHEN TO DEVELOP A COMPOSITE MODEL

* Composite model comprises more than one source group.
* There's always the import source group and a DirectQuery source group

## COMPOSITE MODEL BENEFITS 
* Composite model provide you with design flexibility
* Can integrate data using different storage modes ,striking the right balance imported data and pass-through data
* Composite models can also boost the performance of a DirectQuery model by providing Power BI with opportunity to satisfy some analytic queries from imported data.
* Querying cached data almost always performs better than pass-through queries.

## COMPOSITE MODEL LIMITATIONS

1. Import (or dual, as described later) storage mode tables still require periodic refresh. Imported data can become out of sync with DirectQuery sourced data, so it’s important to refresh it periodically.
2. When an analytic query must combine imported and DirectQuery data, Power BI must consolidate source group query results, which can impact performance.
3. When chaining models (DirectQuery to Power BI datasets), modifications made to upstream models can break downstream models.
4. Relationships between tables from different source groups are known as limited relationships. A model relationship is limited when the Power BI can’t determine a “one” side of a relationship.

## BOOST DIRECTQUERY MODEL PERFORMANCE WITH IMPORT DATA

### IMPORT AGGREGATION TABLES
* You can add import storage mode user-defined aggregation tables or enable automatic aggregations
* Power BI directs higher-grain fact queries to a cached aggregation
* To boost query performance further, ensure that related dimension tables are set to use dual storage mode

### DUAL STORAGE MODE
* dual storage mode table is set to use both import and DirectQuery storage modes
* At query time, Power BI determines the most efficient mode to use. Whenever possible
* Power BI attempts to satisfy analytic queries by using cached data.
* Dual storage mode tables work well with import aggregation tables. They allow Power BI to satisfy higher-grain queries entirely from cached data.
* Slicer visuals and filter card lists, which are often based on dimension table columns, render more quickly because they’re queried from cached data

## DELIVER REL TIME DATA FROM AN IMPORT MODEL
* When Power BI queries a hybrid table, the query uses the cache for older data, and passes through to the data source to retrieve current data.

## CHOOSE A MODEL FRAMEWORK
*  It especially applies to enterprise solutions, where data volumes are large, query throughput is high
* importantly, choose the import model framework whenever possible. This framework offers you the most options, design flexibility, and delivers fast performance.
* Choose the DirectQuery model framework when your data source stores large volumes of data and/or your report needs to deliver near real-time data.

**Choose the composite model framework to:**
* Boost the query performance of a DirectQuery model.
* Deliver near real-time query results from an import model.
* Extend a Power BI dataset (or AAS model) with additional data.

* boost the query performance of a DirectQuery model by using aggregation tables, which can use import or DirectQuery storage mode

1. Geoffrey is a data modeler at Adventure Works who developed a DirectQuery model that connects to the data warehouse. To improve the query performance of higher-grain sales queries, Geoffrey added an import aggregation table. What else should Geoffrey do to improve query performance of the higher-grain queries?
= **Setting the related dimension tables to dual storage mode will allow Power BI to satisfy higher-grain queries entirely from cache.**

2. Breana is a data modeler at Adventure Works who developed a manufacturing model, which is an import model. Breana needs to ensure that manufacturing reports deliver real-time results. Which type of table should Breana create?
= A hybrid table includes a DirectQuery partition for the current period to deliver near-real time results.

3. Mousef is a business analyst at Adventure Works who wants to create a new model by extending the sales dataset, which is delivered by IT. Mousef wants to add a new table of census population data sourced from a web page. Which model framework should Mousef use?
=  A composite model would comprise a DirectQuery source group containing the sales dataset tables, and an import source group containing the imported web page data.

# DESIGN A SEMANTIC MODEL IN POWER BI

*  If your data is coming in from more than one transactional system, before you know it, you can have dozens of tables that you have to work with.
*  Building a great semantic model is about simplifying the disarray
* A star schema is one way to simplify a semantic model, and you learn about the terminology and implementation of them in this module.

**Good semantic model offers the following benefits:**

* Data exploration is faster.
* Aggregations are simpler to build.
* Reports are more accurate.
* Writing reports takes less time
* Reports are easier to maintain in the future


* Providing set rules for what makes a good semantic model is difficult because all data is different, and the usage of that data varies
* a smaller semantic model is better because it performs faster and will be simpler to use.
* a smaller semantic model is composed of fewer tables and fewer columns in each table that the user can see.
* Removing unneeded columns to provide a more manageable number increases the likelihood that the user reads all column names.

![Screenshot 2024-06-14 144318](https://github.com/BafanaMadume/POWERBI/assets/141032267/fed21b0c-80f7-485a-aad5-320f846c7df3)

* Relationships are defined between tables through primary and foreign keys. Primary keys are column(s) that identify each unique, non-null data row.
*  This process becomes important when you are referencing rows in a different table, which is what foreign keys do.
*   Relationships between tables are formed when you have primary and foreign keys in common between different tables.
*  Power BI allows relationships to be built from tables with different data sources, a powerful function that enables you to pull one table from Microsoft Excel and another from a relational database.

## STAR SCHEMAS
*  In a star schema, each table within your semantic model is defined as a dimension or a fact table,

![Screenshot 2024-06-14 145631](https://github.com/BafanaMadume/POWERBI/assets/141032267/c8a3ef6d-80de-4a56-bddd-6a6793d22495)

 **Fact tables** 
* contain observational or event data values: sales orders, product counts, prices, transactional dates and times, and quantities.
* Fact tables can contain several repeated values
* The numbers can be units of measurement, such as sale amount, or they can be keys, such as a customer ID.
* The dates represent time that is being recorded, like order date or shipped date.

**Dimension tables**
*  contain the details about the data in fact tables: products, locations, employees, and order types.
* These tables are connected to the fact table through key columns. Dimension tables are used to filter and group the data in fact tables.
* The fact tables, on the other hand, contain the measurable data, such as sales and revenue, and each row represents a unique combination of values from the dimension tables.
* Fact tables are much larger than dimension tables because numerous events occur in fact tables, such as individual sales.
*  Dimension tables are typically smaller because you are limited to the number of items that you can filter and group on
*  When creating this relationship, you can build the visual according to the requirements, as shown in the following figure.
*  Star schemas and the underlying semantic model are the foundation of organized reports; the more time you spend creating these connections and design, the easier it will be to create and maintain reports.

# WORK WITH TABLES
* When users see fewer tables, they will enjoy using your semantic model considerably more.

## SIMPLE TABLE STRUCTURE
* Be **simple to navigate because of column and table** properties that are specific and user-friendly.
* Have **merged or appended tables** to simplify the tables within your data structure.
* Have **good-quality relationships** between tables that make sense

## CONFIGURE SEMANTIC MODEL AND BUILD RELATONSHIPS BETWEEN TABLES
* To manage these relationships, go to Manage Relationships on the ribbon
* you can create, edit, and delete relationships between tables and also autodetect relationships that already exist
*  When you load your data into Power BI, the Autodetect feature will help you establish relationships between columns that are named similarly
*  Relationships can be inactive or active
*  Only one active relationship can exist between tables
*  Manage Relationships feature allows you to configure relationships between tables, you can also configure table and column properties to ensure organization in your table structure

## CONFIGURE TABLE AND COLUMN PROPERTIES
* Model view in Power BI desktop provides many options within the column properties that you can view or update.
*  A simple method to get to this menu to update the tables and fields is by Ctrl+clicking or Shift+clicking items on this pag

![Screenshot 2024-06-24 101015](https://github.com/BafanaMadume/POWERBI/assets/141032267/e6a1978a-39a9-4118-87f8-d4dca454b2c8)

**UNDER THE GENERAL TAB**
* Edit the name and description of the column.
* Add synonyms that can be used to identify the column when you are using the Q&A feature
* Add a column into a folder to further organize the table structure.
* Hide or show the column.

**Formatting tab**


