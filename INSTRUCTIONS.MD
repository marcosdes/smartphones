The Research Findings can be replicated using common spreadsheet software. The steps bellow detail the steps to create a pivot table that counts the relative percentages of categorical variables or the evolution of numeric variables.
For illustration purposes, this tutorial calculates the percentage representation of each smartphone form factor for each year. To investigate other categories (such as keyboard layout, touchscreen type, etc.), simply replace 'Form Factor 2' with your chosen category in the Columns section in step 3.

**Microsoft Excel:**

1. Open the dataset in Excel.
2. Navigate to the "Insert" tab on the ribbon and select "Pivot Table". Confirm the table range and choose where you want the Pivot Table to be placed (New Worksheet).
3. In the Pivot Table Settings (right side), drag and drop the 'Release Year' to Rows section, 'Form Factor 2' to Columns section, and 'ID' to Values section. 
4. In the Values section, click on the drop-down next to 'ID' and select 'Field Settings'. Change the calculation to 'Count'.
5. To compute the percentages, go to 'Field Settings' again, select 'Show Values As', then '% of Row'.
6. Now, the pivot table will show the distribution of all form factors for each year in percentages.

**Apple Numbers:**
1. Open the dataset in Numbers.
2. Click on the table, then on "Pivot Table" in the toolbar.
3. In the Pivot Options panel (right side), drag and drop the 'Release Year' to the Rows section and 'Form Factor 2' to the Columns section and also Values section.
4. In the Values section, click on information icon next to 'Form Factor 2(Count All)' and select "Show as: % of Row Total" in the drop-down menu.

**To calculate the evolution of numeric variables**, drag a numeric variable (such as Battery Capacity) to the Values section, but leave the Columns section empty. Then, in the Values section, change the field settings to 'Summarise value field by Average' (Excel) or 'Summarise by Average' (Numbers).

To generate data visualizations of these pivot tables, select the columns of the pivot table, then click on “Chart” in the toolbar and choose your preferred chart type from the dropdown menu.
