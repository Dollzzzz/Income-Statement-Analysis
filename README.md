
# Basic Income Statement Analysis

### Dashboard Link : https://app.powerbi.com/view?r=eyJrIjoiZmExYjc3N2EtOTlmMi00MDU1LWE3Y2MtMjNjODM4MTliM2IxIiwidCI6ImJlOWY4YzM3LTc4MjctNGQ2ZC04NDg3LTQ4ZjhjYmFjZGJlZiIsImMiOjl9

## Problem Statement

There is a need for an income statement analysis, particularly one that compares several years. This provides actionable insights into a company’s financial trajectory, cost management, and profitability. It helps to pinpoint areas that require attention, whether it’s boosting revenue, controlling costs, or optimizing operational efficiency, ensuring the company is well-positioned for long-term success. By providing insights into net income, gross profit margin, and expense control, an income statement analysis helps to evaluate financial health and make informed investment decisions. The data is sourced from Finex Skills hub for a fictitious company. 

## Approach
This dashboard contains several visualizations that provide the fictitious company with a summary of the income statement line items, and helps to compare the current and future numbers, while showing the percentage change, and a sparkline to reflect high and low points.

By using slicers, we can readily view the nine selected line items across three buckets: 

(i)     **Year**: 2019 & 2020.

(ii)    **Division**: East, North, South & West.

(iii)   **Month**: January through December.

The nine selected line items are in line with a typical income statement format zooming into (i) Revenue (ii) Cost of Goods Sold (iii) Gross Profit (iv) Expenses (v) EBIT (vi) Finance Costs (vii) Net Income Before Tax (viii) Tax (ix) Net Income. The visualizations for each of these line items are also shown, allowing us to tell the story behind each of them, compare the 2019 performance against the 2020 performance, reflect any changes which could be favorable or unfavorable, and identify trends.

## Findings
**Revenue:** In 2020, services revenue increased by $240,000, from $2.88 million in 2019 to $3.12 million. This increase represents the primary driver of the company's revenue growth, representing a 10% rise in services revenue. However, product revenue declined by $187,000, from $251,000 in 2019 to $64,000 in 2020, while licensing revenue fell by $20,000, from $208,000 to $188,000. The drop in product and licensing revenue may reflect changes in market demand, reduced sales efforts, or challenges in the product offering. The strong performance in services could indicate the company’s increasing reliance on service-based offerings, which are typically higher-margin but may require more investment in human capital.


**Cost of Goods Sold (COGS):** In 2020, COGS rose by 13%, totaling $894k compared to $794k in 2019. This was driven by a combination of factors.  Although Direct labor costs, Direct overhead costs and Commissions fell by roughly $24k in total, these reductions were absorbed by the significant increase in Volume Discounts, which rose by roughly $110k. The increase in Volume Discounts, while potentially increasing customer sales, ultimately offset the cost savings from the reduction in direct labor and materials. This highlights a shift where the company’s efforts to incentivize customers with greater discounts may have contributed to higher overall COGS, despite cost reductions in other areas.

In essence, while the company managed to reduce labor and material costs, these reductions were not enough to prevent an increase in COGS due to the larger volume discounts, which suggests that the company may have been offering more favorable pricing terms to stimulate sales or manage customer expectations in a competitive environment.

**Gross Profit:** Gross profit decreased by 3% year-over-year, from $2.55 million in 2019 to $2.48 million in 2020. The increase in COGS outpaced the modest revenue growth, mainly due to the decline in product sales and the increase in material costs. The company's ability to manage direct costs like labor and overheads is crucial, as rising material costs and a higher percentage of revenue derived from services (which may carry different profit margins) have weighed on the gross profit margin.

**Expenses:** Total expenses increased by roughly $100k (5%) from 2019 to 2020. The breakdown is as follows:

Advertising increased by $37k, from $195k to $232k. This rise indicates that the company increased its marketing efforts, likely to drive the growth in services revenue. However, the effectiveness of these expenditures should be closely monitored, as advertising did not significantly increase total revenue.

Depreciation and amortization rose by $31k. This increase could reflect higher investments in capital assets or intangible assets, such as intellectual property or software.

Legal & professional fees increased by $26k, possibly indicating more legal activity or consultancy costs associated with business restructuring or compliance.

Entertainment saw an increase of $31k, which could reflect higher business development or client engagement costs.

Utilities-energy rose by $45k, possibly due to increasing energy prices or more intensive operational activities. On the other hand, utilities-communication fell slightly by $3k, while utilities-other dropped by $4k.

**EBIT:** EBIT declined by 27%, falling from $634k in 2019 to $466k in 2020. This significant decline reflects the combination of higher COGS and expenses (particularly in advertising and legal fees) without a sufficient increase in revenue. Despite the reduction in interest expenses, operational inefficiencies contributed to a notable decrease in operating profit.

**Finance Costs:** Finance costs decreased significantly by 67%, primarily due to a reduction in interest income by $94k and a slight decrease in interest expense (down by $1k). The reduction in interest income could suggest lower returns from invested capital or changes in the company’s investment strategy.

**Net Income Before Tax:** Net income before tax fell by 34%, from $777k to $514k, mainly driven by the decline in EBIT. The modest reduction in finance costs helped cushion the overall impact, but the significant fall in operating profit could indicate operational challenges and inefficient cost management.

**Tax:** Tax expenses decreased by 34%, from $194k to $128k, in line with the decline in pre-tax income. This reduction was expected, as lower profits result in a lower tax obligation. However, the tax reduction only partially mitigated the impact of the profit decline.

**Net Income:** Net income fell by 34%, from $583k in 2019 to $385k in 2020. This sharp decline was primarily due to the higher operational costs and the increased expenses that outpaced revenue growth. The drop in net income highlights the company’s struggles with maintaining profitability, especially as it navigates higher costs and reduced product sales.

## Summary
Despite a modest increase in revenue (+1%), the company faced significant profitability pressures in 2020. Revenue grew by roughly $30k, from $3.34 million in 2019 to $3.37 million in 2020, reflecting stable but limited growth. However, costs rose sharply, with COGS increasing by 13% and operating expenses growing by 5%. This resulted in a 27% decrease in EBIT (from $634k in 2019 to $466k in 2020) and a 34% decrease in net income Gross profit also declined by 3% due to the disproportionate increase in COGS.

Revenue in 2020 was primarily driven by a 10% increase in services revenue, while a decline in product and licensing sales contributed to a less diversified revenue stream. The rise in materials costs, labor costs, and advertising expenses played a major role in squeezing margins. In particular, the increased spending on advertising and legal fees suggests that the company may have invested heavily in initiatives that did not provide a sufficient return on investment. At the same time, reduced interest income and a drop in product sales were key contributors to the net income decline.

On a positive note, finance costs decreased significantly by 67%, likely due to reduced debt or refinanced loans at lower rates. This reduction helped mitigate some of the impact on EBIT. Tax expenses also fell by 34%, reflecting the lower taxable income driven by the decline in profits.

While the decrease in finance costs and taxes provided some relief, they were not enough to offset the higher operational costs. To improve profitability in the future, the company must focus on better cost control and enhancing operational efficiency. Addressing the core challenges related to rising materials and labor costs, along with more strategic advertising and legal spending, will be critical to achieving stronger financial performance going forward.

## Step-by-Step Process

- Step 1 : Load data into Power BI Desktop, select the two workbooks "COA" and "Journal", and select "Transform Data"
        A walkthrough of the starting dataset is an excel workbook with two worksheets, Journal and COA (Chart of Account). The Journal worksheet records each transaction showing the date, division, description, the double entry accounts and the amount. We will use the Journal worksheet to create our trial balance, and rely on the COA, which would give us the attributes necessary for analysis. The COA shows the Account Code, the Account, whether an item is an Income Statement or a Balance Sheet entry, the Category, debit or credit for each line, and then the Account Group.
- Step 2 : Load the data in Power BI desktop, open power query editor & ensure that all the columns have the correct datatypes. In view tab under "Data Preview" section, check "Column Distribution", "Column Quality" & "Column Profile" options. It was observed that there was no error in any of the columns.
- Step 3 : Have the "Dr" and the "Cr" columns in the Journal workbook combined to one column as an attribute, and rename the column.
        Select the "Dr" column, include the "Cr" column (shift + right arrow), right-click and select "Unpivot Columns". Whether it is a Debit or Credit goes into one column as an attribute and the entries go into another column. Rename the "Attribute" and "Value" columns to "Type" and "Account" respectively, using the code = Table.RenameColumns(#"Unpivoted Columns",{{"Attribute","Type"},{"Value","Account"}})
- Step 4 : Negate the Debit amounts, and let the credit amounts remain positive, to help with trial balance calculations
        A custom column was used.  Go to the Add Column tab, under the "General" section, click "Custom Column". In the dialogue box, under "New Column Name", enter "TB Amount", and under the "Custom Column Formula", enter a formula that negates the amount, when they are debit transactions. In this case, =if [Type]="Dr" then [Amount]*-1 else [Amount]. Then click "ok". Here, it is important to change the datatype of the "TB Amount" column to Decimal Number using the code = Table.TransformColumnTypes(#"Added Custom",{{"TB Amount", type number}}).
- Step 5 : Remove the "Description" and "Amount" columns as they are no longer needed.
        This can be done by (i) using a code, which in this case is =Table.RemoveColumns(#"Changed Type1", {"Description","Amount"})  (ii)going to the Home tab under the "Manage Columns" section, click "Remove Columns" or (iii) right-clicking each column and selecting "Remove".
 Step 6 : Create a separate query for Division to be used as a slicer
        Reference the "Journal" query by right-clicking on Journal. Reference is used instead of Duplicate, because we want a link to be maintained to the original Journal query. Rename the new query from "Journal(2)" to "Division". We only need the Division column in this new query, so the other columns need to be removed. 
        Go to the Home tab, under the "Manage Columns" section, click dropdown next to "Remove Columns" and select "Remove Other Columns". A code can also be used, and in this case, it'd be = Table.SelectColumns(Source,{"Division"}). To remove duplicates, rightclick the Division column and click "Remove Duplicates". The code for this is = Table.Distinct(#"Removed Other Columns").
- Step 7 : Create a dimension table that would help to create time-intelligence calculations
        Right-click the blank part of the Queries (the left-hand side of the power query editor), then select "New Query" and then "Blank Query". Rename the query "Calendar". To generate the list of dates from the journal starting from the earliest to the latest dates table, we use the custom M-code = {Number.From(List.Min(Journal[Date]))..Number.From(List.Max(Journal[Date]))}. 
        Convert this list to table by going to the Transform tab, under "Convert", select "To Table", and then "ok". Rename the column from "Column1" to "Date" using = Table.RenameColumns(#"Converted to Table",{{"Column1","Date"}}). Change the datatype to Date using = Table.TransformColumnTypes(Custom1,{{"Date", type date}}).
- Step 8 : Add date attributes: Year, Month
        Highlight the Date column, and go to the "Add Column" tab, under the "From Date & Time" section, click the drop-down beneath Date, click on "Year" and select "Year". Repeat the same steps to derive the Month values, while replacing the last steps with "Month" instead of Year. 
        The intention is to use the Month to sort our month names. To derive the month names, highlight the Date column, and go to the "Add Column" tab, under the "From Date & Time" section, click the drop-down beneath Date, click on "Month" and select "Name of Month". 
        For simplicity, an abbreviation of month names are preferred, using the first three letters of each month. To achieve this, highlight the "Month Name" column, go to "Transform" tab, under the "Text Column" section, click the drop-down next to "Extract", select "First Characters" and enter "3" in the Count box, and select "OK". 
- Step 9 : Load to PowerBI and mark the Calendar table as a date table.
        Go to the "Home" tab under the "Close" section, select "Close & Apply". Select the "Calendar" table under Data to the far right, and select "Mark as date table", choose the "Date" column and then "OK". This way we can easily use the Calendar table for time-intelligence calculations. "Mark as date table" can be found under "Table Tools" tab, under the "Calendars" section. "Mark as date table" is simply selecting a column to be used for the date.
- Step 10: Create the Data Model
        Go to the "Model View". Here, we can see the three dimension tables "COA", "Division" and "Calendar", against the fact table "Journal". 
        A star-schema is created by dragging "Journal" table to the bottom and the three other tables to the top. We can see a 1-many relationship between "Division" & "Journal", and between "COA" & "Journal", but no relationship between "Calendar" & "Journal". 
        To create this relationship, click, hold, and drag the "Date" column in "Calendar" table on top of the "Date" column in the "Journal" table. This helps to create a 1-many relationship between the "Calendar" and "Journal" tables.

- Step 11 : Create Necessary Measures for the Lines of the Income Statement
        Go back to Report view, and we need to create a table that would host all our measures. To create this table, go to the "Modeling" tab, under the "Calculations" section, click on "New Table". The formula bar pops up, and we can name the new table "My Measures", by typing "My Measures =" and pressing enter.
        
        First Measure "Reporting Value. This is to sum the "TB Amount" in the "Journal" table. Based on the double-entry principle, this should give us 0. Right-click on "My Measures" table and select "New Measure", and enter the formula: 
        Reporting Value=sum(Journal[TB Amount]). 
        Right-click the idle column by right-clicking and choosing "Hide". This helps the Measures table to move up. The standard practice is to always have your calculation on top of your original fields.
        
        Second Measure "Revenue". Revenue=CALCULATE([Reporting Value],COA[Category]="Revenue")
        
        Third Measure "Cost of Goods Sold". Cost of Goods Sold = CALCULATE([Reporting Value],COA[Category]="Cost of Goods Sold")
        
        Fourth Measure "Gross Profit". Gross Profit = [Revenue]+[Cost of Goods Sold]. Alternatively, the Calculate function can be used Gross Profit = CALCULATE([Reporting Value],COA[Category]="Revenue")+CALCULATE([Reporting Value],COA[Category]="Cost of Goods Sold"). Plus sign is used because of the sign of the Cost of Goods Sold. 

        Fifth Measure "Expenses". Expenses = CALCULATE([Reporting Value],COA[Category]="Expenses")
        
        Sixth Measure "Earnings Before Interest and Tax (EBIT)". EBIT = [Gross Profit]+[Expenses]
        
        Seventh Measure "Finance Costs". Finance Costs= CALCULATE([Reporting Value],COA[Category]="Finance Costs")
        
        Eighth Measure "Net Income Before Tax". Net Income before Tax=[EBIT]+[Finance Costs]
        
        Ninth Measure "Tax". Tax is 25%. Tax = IF([Net Income before Tax]>0,-[Net Income before Tax]*0.25,0)
        
        Tenth Measure "Net Income". Net Income = [Net Income before Tax]+[Tax]

- Step 12 : Create a layout for the Income Statement
        In Excel, type out the heading "Category" and the line items "Revenue", "Cost of Goods Sold", "Gross Profit", "Expenses","EBIT","Finance Cost","Net Income Before Tax", "Tax", and "Net Income". 
        In the next column, enter "Sort" as the heading, and using Sequence as the formula, enter numbers 1-9, so that the line items can always appear in that order. Copy all the columns and on the PowerBI Desktop, go to the "Home" tab, under the "Data" section, click on "Enter Data", and paste the entries on Column 1. Set the name to "Layout" and select "Load"

- Step 13 : Create an Income Statement visual
        Matrix Visual: Add the "Category" column from the "Layout" table under the Rows and the "Reporting Value" to the Values. To ensure that the categories are sorted in an income statement format, under "Column tools" tab, go to the "Sort" tab and select the dropdown next to "Sort by column" and choose "Sort"
        The measures created in Step 11 above need to be linked to the correct income statement label in the matrix visual. We need a new measure named "Current". The concept is that we are going to use SELECTEDVALUE and we would declare a variable that would use these 9 categories as basis to connect using the filter context.

Declare the first variable, saying if we select any of the 9 current categories from the category column in the layout table

Declare the second variable, called Amount. This would be any of the measures created in step 11. To assign the value to each selected value, we would use SWITCH and set it to True. We would write 9 lines for each measure, from Revenue to Net Income. An example using Revenue is, if the CurrentCategory, that is what is selected, is equal to "Revenue", then the result should be the revenue that we just calculated.
        Then we set the final result to 0 if none of the above is matched.To conclude the measure, we set the RETURN value. The return value is Amount, as is defined earlier in the measure formula.

        Current = 
        VAR CurrentCategory= SELECTEDVALUE(Layout[Category])

        VAR Amount=SWITCH(TRUE(),
                CurrentCategory="Revenue", [Revenue],
                CurrentCategory="Cost of Goods Sold", [Cost of Goods Sold],
                CurrentCategory="Gross Profit", [Gross Profit],
                CurrentCategory="Expenses", [Expenses],
                CurrentCategory="EBIT", [EBIT],
                CurrentCategory="Finance Costs", [Finance Costs],
                CurrentCategory="Net Income before Tax", [Net Income before Tax],
                CurrentCategory="Tax", [Tax],
                CurrentCategory="Net Income", [Net Income],
                0)
        RETURN
                Amount
- Step 14 : Create Previous Measures using Time Intelligence Function

Previous=CALCULATE([Current],SAMEPERIODLASTYEAR('Calendar'[Date])

Without the year slicer, the values that we currently have is cumulative. To get the noncumulative numbers, bring in the year slicer.

Select the slicer visualization, and pull in the year from the Calendar table. To change the slicer to a tile, select "Format Your Visual"--> "Slicer Settings"--> Under "options", select the dropdown under "Style" and choose "Tile". 

Change background colour to Blue #118DFF. Visualizations-->"Format Your Visual"-->Values -->Background--> Color--> More Colors-->Under Hex, type #118DFF.

Change the font color to white
Visualizations-->"Format Your Visual"-->Values--> Font Color--> select white.

With the slicer "2020 =" selected will show us the current and previous year

- Step 15 : Calculate the Percentage Change between the two periods, and add this to the matrix
        Create a new measure name "% Change" and use the DIVIDE function to get the percentage  change between both periods.
        % Change=DIVIDE([Current]-[Previous],abs([Previous]),0)
        Change the format of the "% Change" measure to percentage, by going to "Measure Tools" --> Formatting Section --> Select "%"
        Format the "% Change" measure in such a way that the positive values are green and the negative values are red. 
        Change the theme to "Classic": View--> under "Themes" subsection, select "Classic". This gives us the default red and green to help us format the percentage change.
        Then we can apply data bars. Under "Visualizations" --> "Add Data to Your Visual"--> Under "Values", select the dropdown next to "% Change"--> "Conditional Formatting"--> "Data Bars"--> Select "Show Bars Only" --> "OK". Ensure that we have green for positive and red for negative before selecting ok

- Step 16 : Format Visual
        Remove Row Subtotals: Visualizations--> Format Your Visual --> Row Subtotals --> Click Off
        Increase Size of Values: Visualizations--> Format Your Visual --> Values --> 12
        Increase Size of Column Headers: Visualizations--> Format Your Visual --> Column Headers --> Text --> Font --> 12
        Increase Size of Row Headers: Visualizations--> Format Your Visual --> Row Headers --> Text --> Font --> 12

**Snap of the matrix**
 ![image](https://github.com/user-attachments/assets/1aa7b83d-788e-420a-a0ec-ade8288af687)

- Step 17 : Create a Donut Chart with Net Income Margin
 Create two measures and add them to the donut chart (i) to calculate Net Income, and format it as a percentage, Net Income Margin = [Net Income]/[Revenue] (ii) the inverse, also formatted as a percentage Inv Net Margin = 1-[Net Income Margin]
 Format the visual 
 a) Turn off detailed labels 
 Visualizations --> Format Your Visual --> Visual --> Detail Labels --> Turn off toggle
 b) Format "Inv Net Margin" color.
 Visualizations --> Format Your Visual --> Visual --> Colors --> "Inv Net Margin" --> select "White, 10% Darker"
 c) Turn off title
 Visualizations --> Format Your Visual --> General --> Title --> Turn off toggle
 d) Have the percentage showing the middle of the donut chart.
 Visualizations--> "Add data to Your Visual"--> Select Card --> Add the "Net Income Margin" to the Fields. Format it by reducing the callout value font to 22, making the text bold, and turning off the "Category Label". This way, we would have a dynamic display of the net income margin.

We import a canvas background previously saved as a "Scalable Vector Graphics Format (*.svg)--> "Format Your Report Page --> Canvas Backgorund --> Click on Browse under image --> reduce transparency to 0%. Afterwards, you'd be able to see the background. Rearrange the existing visuals to fit the new background. 

**Snap of Net Income Margin Donut Chart**

![image](https://github.com/user-attachments/assets/1eb33d62-523a-4daa-b380-20c17f2db9d9)
- Step 18 : Create a Current versus Previous visuals
a) Create a new table
Modeling --> New Table -->name it "KPIs".
b) Create Revenue Current KPI
Revenue Current =CALCULATE([Current], Layout[Category]="Revenue")
c) Create Revenue Previous KPI
Revenue Previous = CALCULATE([Previous], Layout[Category]="Revenue")
d) Calculate Revenue % Change
Revenue % Change= CALCULATE([% Change], Layout[Category]="Revenue")

Insert a card in the "Revenue" tile, and add "Revenue Current". Reduce Callout Value to 16, turn off Category label, and make it bold.

Copy and paste the "Revenue Current" card, and change it to "Revenue Previous". Change the color to "White 30% Darker"

Copy and paste the "Revenue Previous" card, and change it to "Revenue % Change". Change the format to a % , apply conditional formatting that makes it green when there's an increase and red when there is a decrease. To set the rule, select the card, under "Color" in "Callout Value, select fx. Change format style to "Rules", leave the current rule, and then add a new rule that says if value ">=" 0 and <= Max then  choose colour green. 

Import Sparkline by OKViz
After Downloading the visual, import into PowerBI by Visualizations --> "Add Data To Your Visual" --> click on the "..." --> "Import a Visual From A File"--> OK

Insert the Sparkline visual,and add the "Month Name" and "Revenue" to the visual, and then resize it to fit the Revenue tile.

Group the four items in the tile, by highlighting them all, going to "Format" and clicking "Group.

Select the group, and copy and paste in the "Cost of Goods Sold" tile. Create new measures, adding the ABS function to get rid of the negative sign
a) Create Cost of Goods Sold Current KPI
Cost of Goods Sold Current = abs(CALCULATE([Current],Layout[Category]="Cost of Goods Sold"))
b) Create Cost of Goods Sold Previous KPI
Cost of Goods Sold Previous = abs(CALCULATE([Previous],Layout[Category]="Cost of Goods Sold"))
c) Calculate Cost of Goods Sold % Change
Cost of Goods Sold % Change = (CALCULATE([% Change],Layout[Category]="Cost of Goods Sold"))

Change all the visuals in the tile to "Cost of Goods Sold" measures. Change the conditional formatting rule to Cost of Goods Sold. This would be done under "What Field should we base this on?", choose "Cost of Goods Sold % Change".

We want to remove the negative sign in the % change and have the color as red, reflecting the decrease.
Model View --> Properties ( while having Cost of Goods Sold % Change selected) --> Under "Format" choose "Custom"--> Under "Custom Format", remove the negative sign. Also change the sparkline from "Revenue" to "Cost of Goods Sold"

Repeat the steps for Cost of Goods Sold" for the other seven lines of the income statement: "Expenses", "EBIT", "Finance Costs", "Net Income before Tax", "Tax" and "Net Income"

**Snap of Income Statement Line Item Cards and Sparkline**


![image](https://github.com/user-attachments/assets/94b108b5-aaac-4361-bed3-ec55cb9e5bd4)
- Step 19 : Slicers And Conclusion
Add Slicers for Division

Select "Slicer" under Visualizations, select the "Division" and apply the format of the "Year" slicer to the "Division" slicer using the "Format Painter".

Add Slicers for Month names
Select "Slicer" under Visualizations, select the "Month names" and apply the format of the "Year" slicer to the "Month names" slicer. sort the month names by the month, so that they can be sorted chronologically instead of alphabeticaly.

**Snap of Slicers**

![image](https://github.com/user-attachments/assets/eda63a19-0197-4516-983f-b0742398bc93)

**Snapshot of entire Dashboard**

![image](https://github.com/user-attachments/assets/90d91215-77e0-4048-bc5a-5c3e6e418d37)
