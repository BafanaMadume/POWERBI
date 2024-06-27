![Screenshot 2024-06-27 151636](https://github.com/BafanaMadume/POWERBI/assets/141032267/e033849d-2ff6-4525-bef4-6469b5bfb9ab)![Screenshot 2024-06-27 091911](https://github.com/BafanaMadume/POWERBI/assets/141032267/211b09cf-7bc9-4e67-9bf1-2694c6643603)

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
![Screenshot 2024-06-27 153232](https://github.com/BafanaMadume/POWERBI/assets/141032267/ddbf68a6-0dcc-4695-8342-e8a2162b2a02)
![Screenshot 2024-06-27 153158](https://github.com/BafanaMadume/POWERBI/assets/141032267/01d5ccd7-38c3-4318-a75f-695be8fcecc2)
![Screenshot 2024-06-27 153125](https://github.com/BafanaMadume/POWERBI/assets/141032267/2b0d1356-dc0b-4f13-9a92-cf9378adf102)
![Screenshot 2024-06-27 153055](https://github.com/BafanaMadume/POWERBI/assets/141032267/d6d7ca06-2c26-48e6-9184-74ff4a6b795d)
![Screenshot 2024-06-27 153022](https://github.com/BafanaMadume/POWERBI/assets/141032267/26adcea8-2541-4881-9d25-09a966f5b576)
![Screenshot 2024-06-27 152943](https://github.com/BafanaMadume/POWERBI/assets/141032267/519248a1-f5eb-4ace-9c27-4a1d0b693f28)
![Screenshot 2024-06-27 152845](https://github.com/BafanaMadume/POWERBI/assets/141032267/9df08127-a187-42d9-930d-72af4ed3d2f0)
![Screenshot 2024-06-27 152810](https://github.com/BafanaMadume/POWERBI/assets/141032267/62aee9b4-b5ad-488d-a7f8-59a6fd0330b5)
![Screenshot 2024-06-27 152722](https://github.com/BafanaMadume/POWERBI/assets/141032267/083e388f-5871-4da2-b0cb-02dc22c11182)
![Screenshot 2024-06-27 152639](https://github.com/BafanaMadume/POWERBI/assets/141032267/ea63a946-6478-40e4-94ed-1d568ff5a6a4)
![Screenshot 2024-06-27 152539](https://github.com/BafanaMadume/POWERBI/assets/141032267/add53ece-3463-4a74-822a-77b23eb65be8)
![Screenshot 2024-06-27 152430](https://github.com/BafanaMadume/POWERBI/assets/141032267/74c2a9b3-f8ec-466a-ac9e-747196bb06d2)
![Screenshot 2024-06-27 152315](https://github.com/BafanaMadume/POWERBI/assets/141032267/f162c121-3bb1-49bd-b4ad-8c0b12bdb0d0)
![Screenshot 2024-06-27 152205](https://github.com/BafanaMadume/POWERBI/assets/141032267/1ddf01e0-b511-484d-9b69-70bc58c06920)
![Screenshot 2024-06-27 152125](https://github.com/BafanaMadume/POWERBI/assets/141032267/472f01fe-6ea9-4ccf-9d3b-e1443a028aee)
![Screenshot 2024-06-27 152008](https://github.com/BafanaMadume/POWERBI/assets/141032267/a23c750f-3aad-4658-ac6c-5176e48b7e9d)
![Screenshot 2024-06-27 151916](https://github.com/BafanaMadume/POWERBI/assets/141032267/51519819-1ac1-4d0d-8f88-d0ce9d4ee4f4)
![Screenshot 2024-06-27 151756](https://github.com/BafanaMadume/POWERBI/assets/141032267/c98b8c2b-398b-4e62-9261-1597be5ab896)
![Screenshot 2024-06-27 151719](https://github.com/BafanaMadume/POWERBI/assets/141032267/34a7788f-7300-405d-a13b-7a5389a2e507)
![Screenshot 2024-06-27 151636](https://github.com/BafanaMadume/POWERBI/assets/141032267/5962feac-183e-4aff-8678-0d974dceaf83)
![Screenshot 2024-06-27 151534](https://github.com/BafanaMadume/POWERBI/assets/141032267/99f2b4bc-0909-4359-90e5-7354ce08d160)
![Screenshot 2024-06-27 151452](https://github.com/BafanaMadume/POWERBI/assets/141032267/f3534451-0045-4975-a017-766f17837bf9)
![Screenshot 2024-06-27 151344](https://github.com/BafanaMadume/POWERBI/assets/141032267/4b784b0a-3717-4274-8776-b6c2a902a689)
![Screenshot 2024-06-27 151241](https://github.com/BafanaMadume/POWERBI/assets/141032267/0314a3ee-a2b5-4e66-b4ac-e495f80c3171)
![Screenshot 2024-06-27 151214](https://github.com/BafanaMadume/POWERBI/assets/141032267/bf758eaf-748d-4212-a5d3-2c09ed1bd4e6)
![Screenshot 2024-06-27 151132](https://github.com/BafanaMadume/POWERBI/assets/141032267/cdbc755f-9a41-4da9-ac00-d270dbfb330b)
![Screenshot 2024-06-27 151028](https://github.com/BafanaMadume/POWERBI/assets/141032267/57947398-cc1f-48e9-a158-b673b11f2460)
![Screenshot 2024-06-27 150955](https://github.com/BafanaMadume/POWERBI/assets/141032267/b0e771d8-f3a9-4712-a327-24658498d4fb)
![Screenshot 2024-06-27 150917](https://github.com/BafanaMadume/POWERBI/assets/141032267/e182649b-4d3f-4406-8e59-e735baf95006)
![Screenshot 2024-06-27 150757](https://github.com/BafanaMadume/POWERBI/assets/141032267/17a4d08e-629b-4409-bd16-19975002ab70)
![Screenshot 2024-06-27 150625](https://github.com/BafanaMadume/POWERBI/assets/141032267/caf08b5a-53ba-4170-aed1-6ed688fcd3cc)
![Screenshot 2024-06-27 150359](https://github.com/BafanaMadume/POWERBI/assets/141032267/df6e3f46-de79-4518-b863-b3d04ab948f8)
![Screenshot 2024-06-27 150204](https://github.com/BafanaMadume/POWERBI/assets/141032267/a0abb917-6046-435c-93b9-a86eef9f4ecf)
![Screenshot 2024-06-27 150113](https://github.com/BafanaMadume/POWERBI/assets/141032267/ac3cf235-8b2a-4de2-a122-bd7cae365bcb)
![Screenshot 2024-06-27 150025](https://github.com/BafanaMadume/POWERBI/assets/141032267/5936e161-7ac0-4e52-8d6c-35568da6f5c3)
![Screenshot 2024-06-27 145918](https://github.com/BafanaMadume/POWERBI/assets/141032267/4a108be3-5cff-4f6f-aa53-163a75e41067)
![Screenshot 2024-06-27 145751](https://github.com/BafanaMadume/POWERBI/assets/141032267/c53b56fc-eb67-4e13-80a4-30f4ea1863dd)
![Screenshot 2024-06-27 145708](https://github.com/BafanaMadume/POWERBI/assets/141032267/cde2545c-11f5-4bca-aff3-16cf2900e556)
![Screenshot 2024-06-27 145612](https://github.com/BafanaMadume/POWERBI/assets/141032267/9aa1054f-bddb-4fb9-9169-c9a6e3da0e05)
![Screenshot 2024-06-27 145520](https://github.com/BafanaMadume/POWERBI/assets/141032267/7685ff75-0dfd-4030-b682-5327211ab1a2)
![Screenshot 2024-06-27 145452](https://github.com/BafanaMadume/POWERBI/assets/141032267/ea855ab4-866f-45b1-847a-540e057221e8)
![Screenshot 2024-06-27 145359](https://github.com/BafanaMadume/POWERBI/assets/141032267/2060dc91-9503-4277-9fbd-fd36145c7a4c)
![Screenshot 2024-06-27 145301](https://github.com/BafanaMadume/POWERBI/assets/141032267/20ba879f-010e-4df0-a7cb-2d29d6224863)
![Screenshot 2024-06-27 142833](https://github.com/BafanaMadume/POWERBI/assets/141032267/a67cef52-16c1-4fbc-bb76-fa64a822efc5)
![Screenshot 2024-06-27 142815](https://github.com/BafanaMadume/POWERBI/assets/141032267/ea6efe82-207c-45fd-88b2-2a1c67ccc179)
![Screenshot 2024-06-27 134353](https://github.com/BafanaMadume/POWERBI/assets/141032267/3542af1a-f4e0-4379-82a6-906ac1bf72c9)
![Screenshot 2024-06-27 134045](https://github.com/BafanaMadume/POWERBI/assets/141032267/a6be35e2-b1d6-479a-8ef8-d0377d834115)
![Screenshot 2024-06-27 132307](https://github.com/BafanaMadume/POWERBI/assets/141032267/fd03e8d1-7753-442b-9df3-4e63dc8ab7b3)
![Screenshot 2024-06-27 153447](https://github.com/BafanaMadume/POWERBI/assets/141032267/e6be33fa-a810-4d46-8b6b-f0505b32be5a)
![Screenshot 2024-06-27 153430](https://github.com/BafanaMadume/POWERBI/assets/141032267/f147effd-1428-4538-931a-27c0e2da4ba3)
![Screenshot 2024-06-27 153353](https://github.com/BafanaMadume/POWERBI/assets/141032267/1ca6e5a0-f811-4f07-a7d2-621a547785e2)
![Screenshot 2024-06-27 153328](https://github.com/BafanaMadume/POWERBI/assets/141032267/f8ac948f-ac69-443c-8b20-5b71dfee3534)
![Screenshot 2024-06-27 153311](https://github.com/BafanaMadume/POWERBI/assets/141032267/8b196db8-27c1-49c9-91b1-8ec903240366)

![Screenshot 2024-06-27 142815](https://github.com/BafanaMadume/POWERBI/assets/141032267/99842a9d-5836-41af-be91-0f476f1ea518)

![Screenshot 2024-06-27 153353](https://github.com/BafanaMadume/POWERBI/assets/141032267/b7821b12-53b3-4a08-a01f-b8dc2381840a)


![Screenshot 2024-06-27 153430](https://github.com/BafanaMadume/POWERBI/assets/141032267/016b1f7c-1e4f-496c-bed3-74f93d5c3dd1)

![Screenshot 2024-06-27 153447](https://github.com/BafanaMadume/POWERBI/assets/141032267/c01e23da-5d3c-4606-b360-4eb3e7691af4)

