# Road Accident Data - Analysis

 ### Analyzing road accident data in Excel can help you identify trends, hotspots, and potential areas for safety improvements. Here’s a detailed step-by-step guide to analyze such data:


## 1. Data Import and Preparation

---
1. Import Data: Load your road accident data into Excel. You can do this by opening the CSV file directly in Excel or using the Data tab to import from various sources.
2. Data Cleaning: Ensure your data is clean. This involves checking for and handling any missing values, duplicates, and incorrect entries. Use Filter, Conditional Formatting, and Data Validation tools for this.
3. Data Structuring: Structure your data into meaningful columns, such as:
    * Date and time of the accident
    * Location (latitude and longitude or street names)
    * Type of accident
    * Number of vehicles involved
    * Weather conditions
    * Severity of injuries

---

## 2. Basic Analysis

1. Summary Statistics: Use Descriptive Statistics from the Data Analysis Toolpak to get an overview of your data (mean, median, mode, standard deviation, etc.).
2. Pivot Tables: Create pivot tables to summarize your data. For example, you can group accidents by month, day of the week, or hour of the day to identify trends.
3. Count and Frequency Analysis: Count the number of accidents by type, location, or weather condition to identify the most common factors involved in accidents.

---

## 3. Visualization

1. Bar Charts and Histograms: Use bar charts to compare the number of accidents by category (e.g., type of accident or weather condition). Histograms are useful for visualizing the distribution of numeric data (e.g., number of accidents per hour).
2. Line Graphs: Plot line graphs to show trends over time, such as the number of accidents per month.
3. Heat Maps: Create heat maps to visualize accident hotspots. You can do this using conditional formatting or by plotting geographic data on a map (e.g., using Excel’s built-in map charts).

---

## 4. Advanced Analysis

1. Correlation Analysis: Use correlation functions (CORREL) to find relationships between different variables (e.g., weather conditions and accident severity).
2. Regression Analysis: Perform regression analysis to predict the number of accidents based on different factors. You can use the Regression tool from the Data Analysis Toolpak.
3. Geospatial Analysis: If your data includes geographic coordinates, consider using Power BI or other GIS tools for more advanced spatial analysis.

---

## 5. Reporting and Insights

1. Dashboard Creation: Build an interactive dashboard to display your key findings. Use Slicers and Interactive Charts to make it user-friendly.
2. Summary Report: Create a summary report highlighting the key insights from your analysis. This can include textual descriptions, charts, and tables.
3. Recommendations: Based on your analysis, provide recommendations for improving road safety. This could include changes in infrastructure, public awareness campaigns, or specific interventions at accident hotspots.

---

* Analyzing road accident data can provide valuable insights into the factors contributing to accidents and help in making data-driven decisions to improve road safety. If you have specific data or need help with a particular analysis, feel free to share more details! *

---

### Note: .csv or .xlsx - Excel format has advantage over csv format in that it supports table stricture of excel sheets. Mostly data is exported/received in csv format as this being a universal format. 
---

#### Add two columns 'Month' and 'Year' for which we will extract values from the 'Accident date' column using =TEXT([@[Accident Date]],"mmm") and =TEXT([@[Accident Date]],"yyyy") formula convert the two column to 'values' only.
[02_ColumnsAdded.PNG]

## Videos
All video of this series are arranged in playlist and can be found here.

[React Native Videos](https://www.youtube.com/watch?v=kGtEax1WQFg&list=PLRAV69dS1uWSjBBJ-egNNOd4mdblt1P4c)

All future videos will be added to the playlist.

---
## Community
We are trying to build a community so that your questions and issues can be answered by other learners and you can build a community of mobile app developers. For this we are using Discord. You can join Discord server here.

[Join Discord](https://hc.lco.dev/discord)

---
## How to contribute

Contribution is simple in this project. There are 2 major ways to contribute:
1. By joining Discord and help others to solve their bugs or share your projects.
2. By writing articles of your learning on [Hashnode](https://hashnode.com). With each video, I will assign some task to study or code and you can share them via articles. You can share these articles in respective contribution files such as Project-one-contribution.md etc. Please don't send any Pull Request to change Readme file or code files till we finish this series.

We constantly check all articles shared to us and feature them. Please DO NOT SEND PR to feature you on readme. Thanks.

---
## Must read from Hashnode

1. [Installation Guide for React Native (Linux)](https://josephjosedev.hashnode.dev/installation-guide-for-react-native-linux)

2. [React Native: Prerequisites & Installation](https://mohitharge.hashnode.dev/react-native-prerequisites-installation)

3. [Understanding Main-axis and Cross-axis in React-Native](https://sharetogrow.hashnode.dev/introduction-to-stylesheet-and-understanding-main-axis-and-cross-axis-in-react-native)