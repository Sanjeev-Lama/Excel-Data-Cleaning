# Excel Data Cleaning Essentials

## Overview

In this data cleaning process, I transform a raw dataset plagued with errors into a refined dataset suitable for presentation. Through a series of steps and techniques, I have addressed various issues such as inconsistent formatting, duplicate entries, and erroneous data points. My arsenal includes tools like "Text to Columns" and functions like "TRIM," "PROPER," "LOWER," "IFERROR," and more, enabling me to efficiently cleanse the data and ensure its accuracy and integrity.

## Key Steps

1. Autofit Rows and Columns:
Adjust the column width and row height:
Format > Adjust Row Height (Alt+H+O+I),
Format > Adjust Column Width (Alt+H+O+A)

2. Find & Replace:
Shortening the ‘Client’ Column:
Ctrl+H - to remove everything with in parenthesis
Put (*) in Find What section and leave the replace section empty

3. Lower & Upper
Converting the ‘Client’ column from all capital to all lowercase for that is used =LOWER(text) to change it to lowercase.
After converting ‘Client’ column to all lower case, select all the values inside that column by Ctrl + Shift + ⬇️, copy, then paste as value to a new column to ensure proper formatting, and finally, delete the old column.

4. Trim & Proper
Correcting data inside ‘Contact’ column:
Insert a new column, use =TRIM(PROPER(text)) to standardize capitalization and remove uneven spaces, paste the cleaned column as value, and delete the old column.

5. Text to Columns
Separating the values in ‘Department’ column:
Create a new column named Region, use Text to Columns under ‘Data’ with ‘Delimited’ option, select ‘Others’ delimiter and specify ‘_’, then choose the destination.

6. Removing Duplicates
Select all data, go to ‘Data’ and choose remove duplicates.

7. Filling Empty Cells
Select all data, under ‘Home’ go to ‘Find & Select’, choose ‘Go To Special’, select ‘Blanks’, type "NA" in the formula bar, and press Ctrl + Enter.

8. IFERROR
For the ‘Profit Margin’ column, use =IFERROR(value, value_if_error) to handle errors.

9. Formatting
Highlight column headers for better structure.

10. Gridlines
Remove gridlines from the entire dataset for a cleaner appearance.

Documenting the cleaning process, including the steps taken, formulas applied, and any deviations or challenges encountered, to facilitate transparency and reproducibility.
and the documentaiton can be found [here](https://docs.google.com/document/d/1_pSwzm_xOeKFgSp4P51mocSa29R4VGJut4gvl1oPIjM/edit#heading=h.ju77fbdmm9qy)

## Outcome

Through my meticulous data cleaning efforts, I successfully transform the raw dataset into a clean and structured format, ready for analysis and presentation. By addressing errors and inconsistencies, I enhance the reliability and usability of the data, empowering decision-makers with accurate insights for informed decision-making.

This encapsulates my journey from data chaos to clarity, showcasing the importance of effective data cleaning in ensuring data integrity and facilitating meaningful analysis.

## Data Cleaning [Video](https://screenapp.io/app/#/shared/09b99a56-c8b9-4d97-a096-7888150fecb5) 
