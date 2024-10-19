# Netflix-Streaming-Data-Analysis

## Project Overview
This project conducts a comprehensive analysis of Netflix's streaming data, transforming raw data into actionable insights using Python and Power BI. The dashboard provides stakeholders with critical metrics on content distribution, genre trends, and performance to support strategic decision-making for content acquisition and user engagement.

## Objective
The main goal of this project is to:
- Transform raw Netflix data into meaningful insights.
- Identify trends in content genres and user preferences.
- Evaluate performance indicators like ratings and viewership to enhance the user experience.
- Facilitate data-driven decisions for stakeholders with clear, interactive visualizations.

## Problem Statement
Netflix and other streaming platforms face challenges such as:
- Lack of clarity in content performance metrics.
- Inefficient analysis of genre trends and user ratings.
- The need for a comprehensive visualization tool to easily interact with data.

This project addresses these challenges by creating an interactive Power BI dashboard that enables Netflix to make informed decisions about content strategy and user experience.

---

## Project Highlights

### Technologies Used
- **Python**: NumPy, Pandas
- **Power BI**: DAX, Power Query Editor
- **Tools**: Power BI Desktop

### Data Source
- Netflix catalog data in CSV format.

### Skills Demonstrated
- Data cleaning
- ETL processes
- Business intelligence and visualization

---

## Project Workflow

### 1. Data Cleaning and Preparation
- **Tools Used**: Python (NumPy, Pandas)
  - Imported the raw Netflix CSV dataset.
  - Handled missing data, normalized columns, and removed duplicates.
  - Executed data cleaning techniques like removing irrelevant rows, filling missing values, and standardizing data formats.

### 2. ETL (Extract, Transform, Load)
- Used Python to extract and transform raw data.
- Cleaned dataset loaded into Power BI for visualization.

### 3. Exploratory Data Analysis (EDA)
- Analyzed key metrics like movies vs. TV shows, genre popularity, and release trends.
- Implemented data integrity checks to ensure accuracy and consistency.

### 4. Data Visualization & Power BI Dashboard
- **Importing into Power BI**: The cleaned dataset was imported for modeling and visualization.
- **Dashboard Features**:
  - Interactive bar and line charts for content distribution by genre and year.
  - KPIs for the total number of shows, movies, and average ratings.
  - Dynamic filters and slicers for granular analysis (genre, year, rating).
  - A pie chart for content rating distribution (PG, PG-13, etc.).

### 5. DAX Functions
- Used DAX to create calculated measures like the percentage of content by genre.

---

## Dashboard Pages

### Page 1: **Home**
**KPIs Overview**:
- **Total Shows**: 7974
- **Total Directors**: 4150
- **Total Genres**: 36
- **Location**: 689
- **Start Year**: 1942
- **End Year**: 2021

### Page 2: **Movies**
**Movies Page KPIs**:
- **Total Movies**: 5651
- **Total Directors**: 4013
- **Total Genres**: 19
- **Location**: 597
- **Start Year**: 1942
- **End Year**: 2021
- **Top Director**: Raul Campos, Jan Suter
- **Top Actor**: Shah Rukh Khan
- **Top Genre**: Drama

### Page 3: **Shows**
**Shows Page KPIs**:
- **Total Shows**: 2325
- **Total Directors**: 172
- **Total Genres**: 17
- **Location**: 184
- **Start Year**: 1963
- **End Year**: 2021
- **Top Director**: Alastair Fothergill
- **Top Actor**: David Attenborough
- **Top Genre**: International TV Shows

---

## Key Insights from the Analysis
- **Genre Trends**: Drama is the most popular genre for movies, while International TV Shows dominate the shows category.
- **Content Production Peaks**: Significant ramp-ups in production occurred in specific years, aligning with Netflix’s growth strategy.
- **Ratings Distribution**: Content ratings analysis provides insights into the quality distribution across Netflix’s library.

---

## Challenges Faced
- **Data Cleaning**: Handling missing or inconsistent values required extensive transformations.
- **User-Friendly Dashboard Design**: Ensuring that the Power BI dashboard was both informative and easy to navigate required thoughtful planning and execution.

---

## Outcome
The final Power BI dashboard provides key insights into Netflix’s content catalog, enabling data-driven decision-making for content acquisition, user engagement, and content strategy. The project demonstrates proficiency in data cleaning, Python, and Power BI reporting.

---

## Visualizations
- **Bar Chart**: Displays content distribution by genre (movies vs. TV shows).
- **Line Chart**: Visualizes the number of releases per year, highlighting trends in Netflix's content production.
- **Pie Chart**: Shows content ratings distribution, helping understand the quality of the Netflix library.
- **Slicer**: Allows for interactive filtering by genre, release year, and other criteria for deeper insights.

---

## Conclusion
This project highlights how data-driven insights can help streaming platforms like Netflix make strategic decisions regarding content acquisition, marketing, and user engagement. By using Python for data preparation and Power BI for visualization, the project provides a valuable contribution to business intelligence and analytics.

---
