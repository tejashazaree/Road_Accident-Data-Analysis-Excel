# Road Accident Data - Analysis

 #### Analyzing road accident data in Excel can help you identify trends, hotspots, and potential areas for safety improvements. Here’s a detailed step-by-step guide to analyze such data:

---
## Data Import and Preparation</p>


- Import Data: Load your road accident data into Excel. You can do this by opening the CSV file directly in Excel or using the Data tab to import from various sources.
- Data Cleaning: Ensure your data is clean. This involves checking for and handling any missing values, duplicates, and incorrect entries. Use Filter, Conditional Formatting, and Data Validation tools for this.
- Data Structuring: Structure your data into meaningful columns, such as:
    * Date and time of the accident
    * Location (latitude and longitude or street names)
    * Type of accident
    * Number of vehicles involved
    * Weather conditions
    * Severity of injuries

---

##  Basic Analysis</p>

- Summary Statistics: Use Descriptive Statistics from the Data Analysis Toolpak to get an overview of your data (mean, median, mode, standard deviation, etc.).
- Pivot Tables: Create pivot tables to summarize your data. For example, you can group accidents by month, day of the week, or hour of the day to identify trends.
- Count and Frequency Analysis: Count the number of accidents by type, location, or weather condition to identify the most common factors involved in accidents.

---

## Visualization</p>

- Bar Charts and Histograms: Use bar charts to compare the number of accidents by category (e.g., type of accident or weather condition). Histograms are useful for visualizing the distribution of numeric data (e.g., number of accidents per hour).
- Line Graphs: Plot line graphs to show trends over time, such as the number of accidents per month.
- Heat Maps: Create heat maps to visualize accident hotspots. You can do this using conditional formatting or by plotting geographic data on a map (e.g., using Excel’s built-in map charts).

---

## Advanced Analysis</p>

- Correlation Analysis: Use correlation functions (CORREL) to find relationships between different variables (e.g., weather conditions and accident severity).
- Regression Analysis: Perform regression analysis to predict the number of accidents based on different factors. You can use the Regression tool from the Data Analysis Toolpak.
- Geospatial Analysis: If your data includes geographic coordinates, consider using Power BI or other GIS tools for more advanced spatial analysis.

---

## Reporting and Insights </p>

- Dashboard Creation: Build an interactive dashboard to display your key findings. Use Slicers and Interactive Charts to make it user-friendly.
- Summary Report: Create a summary report highlighting the key insights from your analysis. This can include textual descriptions, charts, and tables.
- Recommendations: Based on your analysis, provide recommendations for improving road safety. This could include changes in infrastructure, public awareness campaigns, or specific interventions at accident hotspots.

---

* Analyzing road accident data can provide valuable insights into the factors contributing to accidents and help in making data-driven decisions to improve road safety. If you have specific data or need help with a particular analysis, feel free to share more details! *

---

#### Note on .csv and .xlsx - Excel format has advantage over csv format in that it supports table structure, and multiple sheets in one file. Though data is mostly exported/received in csv format as this being a universal format. For our analysis we will save the data in 
---

# Cleaning the data </p>

### For cleaning purpose following steos are taken
* key column validation such as 'Accident index', and other dimensional columns such as 'Accident_Severity','Vehicle_Type' etc.
* Checking for Inconsistencies, typo error, spellings and invalid data.
* Blank columns and data not available.

### Data Processing
* Add columns 'Month' with formula =TEXT([@[Accident Date]],"mmm"). convert to values only.
* Add columns 'Year' with formula =TEXT([@[Accident Date]],"yyyy"). convert to values only.

</p>



![02_ColumnsAdded.PNG](https://github.com/tejashazaree/Road-Accident---Data-Analysis---Excel/blob/main/Images/02_ColumnsAdded.PNG)


> with the Cleaning and Processing part done our data is ready for Analysis.

### Data Analysis and Visualization

Add three worksheets for Analysis
1. Road Type - for road cndition analysis
2. Monthly Trend - Monthly accident trends
3. KPI - Key parameters


#### Import the excel table into a new excel file>Get Data>From file>From excel workbook
![03_ImportData.PNG](https://github.com/tejashazaree/Road-Accident---Data-Analysis---Excel/blob/main/Images/03_ImportData.PNG)

#### In the Import Data dialogue check 'Only Create Connection' as data file is separate from the Dashboard file.

![03_ImportData.PNG](https://github.com/tejashazaree/Road-Accident---Data-Analysis---Excel/blob/main/Images/04_connOnly.PNG)

---


---

### The Dashboard

![05_Dashboard.PNG](https://github.com/tejashazaree/Road-Accident---Data-Analysis---Excel/blob/main/Images/05_Dashboard.png)
