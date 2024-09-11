Power Query Date Dimension Table
This repository contains a Power Query script for creating a Date Dimension Table in Power BI or Excel. The script is provided in a .txt file and can be used to generate a custom date table that spans any range of dates.

Features
Supports a continuous range of dates
Automatically generates common date attributes, including:
Year
Month
Day
Fiscal Year
Quarter
Week Number
Day of Week
Customizable fields to suit business requirements
How to Use
Download the Script
Clone or download the .txt file from this repository.

Open Power BI or Excel
Launch Power BI Desktop or Excel with the Power Query Editor enabled.

Create a Blank Query
In Power BI or Excel, go to Home > Transform Data > Transform Data > New Source > Blank Query.

Open the Advanced Editor
In the query editor, go to Home > Advanced Editor.

Paste the Script
Copy the query from the downloaded .txt file and paste it into the Advanced Editor window.

Set the Date Range
Modify the following variables at the beginning of the script to define your date range:

powerquery
Copy code
StartDate = #date(YYYY, MM, DD),   // Example: #date(2020, 1, 1)
EndDate = #date(YYYY, MM, DD),     // Example: #date(2030, 12, 31)
Apply Changes
After adjusting the date range, click Done and apply the changes. This will generate a full Date Dimension Table that can be used in your data model.

Customization
The script is designed to be flexible. You can further customize it by adding fields such as:

Fiscal Periods (Fiscal Year, Fiscal Quarter)
Holiday Flags (IsHoliday column)
Custom Week Numbering (ISO Weeks, Business Weeks)
Benefits
Ensures consistent and accurate date-related fields across reports
Unlocks advanced time intelligence in Power BI
Provides flexibility for custom fiscal calendars, holidays, and more
Optimizes performance with pre-built date attributes
Contributing
If you have suggestions for improvements or new features, feel free to submit a pull request or open an issue.
