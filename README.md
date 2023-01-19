# Data-Cleaning-And-Analyzing-using-Excel

<h1>Data Cleaning</h1>

In this Project we are importing dataset containing information about the fleet of vehicles. The data is in comma-separated value (CSV) format. The data is cleaned up to run any kind of analysis on it.


<h1>Tasks performed:</h1>

1.**Saved the CSV file as an XLSX file**: Saved Montgomery_Fleet_Equipment_Inventory_FA_PART_1_START.CSV file as .XLSX file using Excel for the web.

2.**Column widths**: Sorted out the widths of all columns so that the data is clearly visible in all cells.

3.**Empty rows**: Used the Filter feature to look for blanks and remove all empty rows from the data.

4.**Duplicate records**: Used Remove Duplicates feature to look for and remove any duplicated records from the data.

5.**Spelling**: Checked for spelling mistakes in the data and fixed them.

6.**Whitespace**: Used the Find and Replace feature to remove all double-spaces from the data.

7.**Department names**: Used Flash Fill to reduce the department names to just one column, and then removed any unnecessary columns.

8.**Save workbook**: Use ‘Save As’ to Saved completed workbook as Montgomery_Fleet_Equipment_Inventory_FA_PART_1_END.XLSX using 'Save As'.



<h1>Data Analyzing</h1>

Here we are using Excel pivot tables to analyze the data. 

<h1>Tasks performed</h1>

1.**Opening .XLSX file**: Opening the input dataset Montgomery_Fleet_Equipment_Inventory_FA_PART_2_START.XLSX file in Excel for the web.

2.**Format the data as a table**: Used Format as Table option to format the data as a table.

3.**Use AutoSum to calculate values**: Used AutoSum to find the following values for column ‘C’ and record each of the values:

<ul>SUM
AVERAGE
MIN
MAX
COUNT</ul>

4.**Create a Pivot Table**: Used the PivotTable feature to create a pivot table that displays the Department field in the Rows section, and the Equipment Count in the Values section, so that the pivot table displays the sum of equipment count by department.

5.**Sort the pivot table data**: Used the Sort By Value setting on the pivot table to sort it in descending order by the sum of equipment count.

6.**Make two more pivot tables**: Created two more identical pivot tables so that you end up with 3 worksheets that contain identical pivot tables.

7.**Analyze data in the pivot table**: Use the PivotTable Fields pane to manipulate and analyze data in the two copied pivot table as follows:

In pivot table 2 added the Equipment Class field below the Department field so that the different vehicle types appear under each department with their respective counts.
Collapsed all fields except the top one - Transportation
In pivot table 3 added the Equipment Class field above the Department field so that the different vehicle types appear first, with the different departments listed underneath each vehicle type with their respective counts.
Collapsed all fields except the top one - CUV

8.**Save workbook**: Saved workbook as Montgomery_Fleet_Equipment_Inventory_FA_PART_2_END.XLSX using Save As.
