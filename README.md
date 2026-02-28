# Bike-Sales-Project
This project contains a Google Sheets for bike sales in different regions.

#Project-Overview
This project was completed entirely using Google Sheets on a mobile device. It focuses on cleaning, analyzing, and visualizing a bike sales dataset containing customer purchase records across Europe, North America, and the Pacific.

Each record represents a unique customer and includes attributes such as customer ID, gender, Marital Status, age, income, number of children, and purchase region.

#Data-understanding-and-preparation
To understand the dataset, all rows and columns were reviewed to identify the structure, variable, and overall scope of the data. Due to the limitations of Google Sheets on mobile, certain desktop features such as Remove Duplicates, Pivot Tables, Find and Replace, and Slicers were not available or did not function reliably.

To preserve data integrity, a copy of the original dataset was created in a new sheet titled 'cleaned_dataset', where all data cleaning was performed.

#Data-cleaning-process
The following cleaning and standardization steps were carried out:
1. Marital Status Standardization: Values originally recorded as M and S were converted to Married and Single using the IF function. 
2. Gender Standardization: Values originally recorded as M and F were converted to Male and Female, also using the IF function.
3. Age grouping: A new column titled 'Age Brackets' was created to group customers into: Youth, Middle-Aged, and Old. This grouping was done to simplify analysis and dashboard creation.
4. Data Formatting: All columns were reviewed to ensure proper formatting. For example, the income column was formatted as 'Currency'. The IF function was deliberately used instead of Find and Replace because the mobile version of Google Sheets does not handle bulk replacements reliably.

#Analysis-approach
After cleaning, a new sheet titled 'analysis_summary' was created to perform analysis. Since Pivot tables are not available on Google Sheets for mobile, summary tables were built manually using: COUNTIF, AVERAGE IF

While this approach was more manual, it provided a deeper understanding of how pivot tables work behind the scenes.

Four summary tables were created and later used for dashboard visualization.

#Dashboard-Creation
A dedicated sheet titled 'Dashboard' was created. Charts were designed using the summary tables and arranged to provide a clear, high-level overview of the dataset.

#Key-insights
From the analysis, the following insights were observed:
1. There are slightly more male customers than female customers.
2. The majority of customers fall within the Middle-Age category.
3. Customers in the Pacific Region have the highest average income, slightly higher than those in North America and significantly higher than those in Europe.
4. North America has the largest customer base, with over twice as many customers as the Pacific region and significantly more than Europe.

#Limitation-Future-Work
Due to mobile platform limitations, advanced features such as slicers, and interactive filtering could not be used.

If completed on a PC, further analysis would include:
1. Filtering customers by Gender across regions.
2. Analyzing the number of actual bike purchases per region
3. Deeper customer segmentation and trend analysis.

There is significant potential for further exploration within this dataset.
