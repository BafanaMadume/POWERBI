![Screenshot 2024-06-27 091911](https://github.com/BafanaMadume/POWERBI/assets/141032267/211b09cf-7bc9-4e67-9bf1-2694c6643603)

## WRITE DAX FORMULAS FOR POWER BI DESKTOP models

**Data Analysis Expressions(DAX)**

- Calculated tables
- Calculated columns
- Measures

* DAX can also be used to define row-level security (RLS) rules,, which are expressions that enforce filters over model tables.

## CALCULATED TABLES

* The formula can duplicate or transform existing model data, or create a series of data, to produce a new table.
* Calculated table data is always imported into your model
* so it increases the model storage size and can prolong data refresh time.

**Calculated tables can be useful in various scenariod**
* Date tables
* What-if analysis
* Role-playing dimensions

### DATE TABLES
* Date tables are required to apply special time filters known as time intelligence.
* DAX time intelligence functions only work correctly when a date table is set up.
* When your source data doesn't include a date table
  - you can create one as calculated tables by using the CALENDAR
  - CALENDARAUTO DAX functions.
 
### ROLE-PLAYING DIMENSIONS
* When two model tables have multiple relationships, it could be because your model has a role-playing dimension
*  the Date table is described as a role-playing dimension because it could play the role of order date or ship date.
*  Any remaining relationships between the two tables are inactive. In a model diagram, the relationships are represented as dashed lines. Inactive relationships are only used when they're expressly requested in a calculated formula by using the USERELATIONSHIP DAX function.

### WHAT-IF ANALYSIS
*  When you create a what-if parameter, a calculated table is automatically added to your model.
*  What-if parameters allow report users to select or filter by values that are stored in the calculated table.
* Notably, what-if calculated tables aren't related to other model tables because they're not used to propagate filters. For this reason, they're sometimes called disconnected tables.

### CALCULATED COLUMNS
* You can write a DAX formula to add a calculated column to any table in your model.
* The formula is evaluated for each table row and it returns a single value.

### MEASURES
* You can write a DAX formula to add a measure to any table in your model
* The formula is concerned with achieving summarization over model data
* Similar to a calculated column, the formula must return a single value.

# WRITE DAX FORMULAS

* Each model calculation type, **calculated table**, **calculated column**, or measure is defined by its name, followed by the **equals symbol (=)**,

* <Calculation name> = <DAX formula>
* For example, the definition of the Ship Date calculated table that duplicates the Date table data is:
  - Ship Date = 'Date'

## DAX FUNCTIONS
* DAX functions have arguments that allow passing in variables

## DAX OPERATORS 
Formulas also rely on operators 

## REERENCE TO MEDEL OBJECTS
* Formulas can only refer to three types of model objects: tables, columns, or measures.
* A formula can't refer to a hierarchy or a hierarchy level. (Recall that a hierarchy level is based on a column, so your formula can refer to a hierarchy level's column.)

### TABLE REFERENCES
* When you reference a table in a formula, officially, the table name is enclosed within single quotation marks.

  **Single quotation marks can be omitted when both of the following conditions are true**
  1. The table name does not include embedded spaces.
  2. The table name isn't a reserved word that's used by DAX,Date is a DAX function name, which explains why, when you are referencing a table named Date, that you must enclose it within single quotation marks.

  ## COLUMN REFERENCES
  * When you reference a column in a formula, the column name must be enclosed within square brackets
    Revenue = SUM([Sales Amount])
  * you can disambiguate the column reference by preceding it with its table name
  * This disambiguated column is known as a fully qualified column

  ## MEASURE REFERENCES
  * When you reference a measure in a formula, like column name references, the measure name must be enclosed within square brackets
  * Profit = [Revenue] - [Cost]
 
  ## DAX Variables
  * Formulas can declare DAX variables to store results.
 
  **WHITESPACE**

  * Whitespace refers to characters that you can use to format your formulas in a way that's quick and simple to understand.
    - Whitespace characters include:
      - Spaces
      - Tabs
      - Carriage returns

  * Whitespace is optional and it doesn't modify your formula logic or negatively impact performance.,
  - Use spaces between operators.
  - Use tabs to indent nested function calls.
  - Use carriage returns to separate function arguments, especially when it's too long to fit on a single line. Formatting in this way makes it simpler to troubleshoot, especially when the formula is missing a parenthesis.
  - Err on the side of too much whitespace than too little.
 
![Screenshot 2024-06-27 112516](https://github.com/BafanaMadume/POWERBI/assets/141032267/42c5829a-ef8c-4c71-8bc8-fa4c7bb6778b)

![Screenshot 2024-06-27 142815](https://github.com/BafanaMadume/POWERBI/assets/141032267/fea15c9d-977c-42f4-bf80-85b47c07a50f)
![Screenshot 2024-06-27 142833](https://github.com/BafanaMadume/POWERBI/assets/141032267/71d30d09-8c08-4344-9c9c-e9f6cae79d43)

# QUESTIONS
1.
![Screenshot 2024-06-27 132136](https://github.com/BafanaMadume/POWERBI/assets/141032267/e2d55e06-6724-43d6-8c5c-871933b69288)
2.
![Screenshot 2024-06-27 132307](https://github.com/BafanaMadume/POWERBI/assets/141032267/dc74b247-ed2c-440d-805f-15729f6e40a9)
3.
![Screenshot 2024-06-27 132615](https://github.com/BafanaMadume/POWERBI/assets/141032267/33c0ee0c-dcba-4c86-8f88-332e18c399e1)
4.
![Screenshot 2024-06-27 132708](https://github.com/BafanaMadume/POWERBI/assets/141032267/8ef54bde-7d1c-44eb-81e0-bd7b3e82d8b9)
5.
![Screenshot 2024-06-27 132828](https://github.com/BafanaMadume/POWERBI/assets/141032267/ab8b3958-49f7-48b9-a730-b199dbe40da3)
6.
![Screenshot 2024-06-27 133139](https://github.com/BafanaMadume/POWERBI/assets/141032267/700649d2-fa95-44de-b862-19c97b2f21d1)
7.
![Screenshot 2024-06-27 134045](https://github.com/BafanaMadume/POWERBI/assets/141032267/03a91e8d-2c42-4eee-8726-9715cebbb60f)
