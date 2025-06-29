# Excel-Dashboard
# 🎬 Netflix Trends Dashboard (Excel)

An interactive Excel dashboard visualizing global Netflix trends across genres, countries, and release types. The project focuses on cleaning, analysis, and storytelling using Excel features like Pivot Tables, Charts, and Slicers.

 #📌 Project Overview

This dashboard analyzes:

- Top creators/directors by number of titles
- Most popular release year for Movies & TV Shows
- Country-wise content production
- Genre and rating distribution
- Comparison between Movies vs. TV Shows

 #🧹 Data Cleaning Approach

✅ Done in Python (Pandas):

- Removed major **null values** and empty records  
- Standardized **column formats**
- **Fixed opposite-switched columns** (e.g., swapped values in `Country` & `Listed_in`)
- Removed irrelevant whitespace and deduplicated values

 ✅ Done in Excel:

- Corrected **data types** for compatibility (dates, numbers)  
- Handled minor conflicts in column headers & formats that caused issues while importing  
- Applied conditional formatting, data validation, and cleaned slicer items  

 🧪 Final clean dataset was used to build the dashboard entirely in Excel.

# 📊 Features of the Dashboard

- 📌 Pie Chart: Country-wise Netflix content share  
- 📈 Bar Chart: Movies vs. TV Show distribution by rating count  
- 📅 Top Years: Filter by release year  
- 🎥 Top Creators: Count of titles by most frequent creators  
- 📍 Country Filter: Analyze trends across different countries  
- 🧭 Multiple slicers:to navigate type, genre, country & year

#  🧰 Tools Used

- Python (Pandas) – Data cleaning & transformation  
- Microsoft Excel – Dashboard design using:
  - Pivot Tables
  - Charts (Bar, Pie, Column)
  - Slicers
  - Conditional Formatting

# 📁 Dataset

Netflix title data including:
- Type (Movie/TV Show)
- Release Year
- Country
- Genre (`Listed_in`)
- Rating
- Creator/Director

> 🔐 Note: Dataset used is sample data from a public domain.

-
