# Data Analysis on Restaurants and Food 🍽️📊

![Hackathon Banner](https://media.licdn.com/dms/image/v2/D5622AQE6KZvF5g_hsw/feedshare-shrink_800/B56ZZMqBYKGcAg-/0/1745042809148?e=1747872000&v=beta&t=Ah4nat9CDTX2I_0cm10cemqldMlC2dujJbU9JQ4XZWs)

## 📝 Project Overview
This repository contains a comprehensive analysis of restaurant trends in Bangalore using Zomato's real-world dataset. Developed as part of the **Innomatics Research Labs Hackathon**, this project demonstrates data cleaning, exploratory analysis, and geospatial visualization techniques to uncover valuable insights about Bangalore's food scene.

## 🎯 Hackathon Objectives
- Perform exploratory data analysis (EDA) on restaurant data
- Create cuisine-specific geospatial maps using Folium
- Develop interactive density visualizations with marker clustering
- Extract actionable business insights for food delivery platforms

## 📊 Dataset
The analysis uses two primary datasets:
1. **zomato_data.csv** - Contains:
   - Restaurant details (name, type, cuisines)
   - Operational features (online_order, book_table)
   - Performance metrics (ratings, votes, approx_cost)
   - Location data (listed_incity areas)

2. **Geographical_Coordinates.csv** - Provides latitude/longitude for Bangalore areas

## 🛠️ Technologies Used
- **Python** (Pandas, NumPy) for data wrangling
- **Folium** for interactive geospatial visualizations
- **Geopy** for geocoding support
- **Matplotlib/Seaborn** for statistical visualizations
- **VS Code** as development environment

## 🔍 Key Findings
### Restaurant Metrics
- 📊 Ratings cluster between 3.5-4.0 (median: 3.7)
- 💰 Average cost for two: ~554 INR (range: 40–6000 INR)
- 🍽️ Quick Bites and Casual Dining dominate the market

### Cuisine Trends
- 🍛 North Indian, Chinese, South Indian most popular
- 🍕 Italian and Continental in high-demand areas

### Spatial Distribution
- 🗺️ High density in BTM, Koramangala, Indiranagar
- 📍 Premium restaurants cluster in central Bangalore

## 🚀 Project Structure
1. **Data Cleaning**:
   - Handled missing values and special characters
   - Converted ratings/costs to numeric types
   - Encoded binary features (online_order, book_table)

2. **Exploratory Analysis**:
   - Rating distribution analysis
   - Cost vs. cuisine correlations
   - Votes and popularity trends

3. **Geospatial Visualization**:
   - Interactive Folium maps with marker clustering
   - Cuisine-specific heatmaps
   - Restaurant density by locality

## 📌 Hackathon Tasks Completed
✔️ Task 1: Comprehensive EDA with statistical insights  
✔️ Task 2: Cuisine-Specific Folium Mapping  
✔️ Task 3: Interactive Density Mapping with Clustering 

## 📈 Business Applications
This analysis helps food platforms:
- Identify high-potential locations for expansion
- Understand pricing strategies by area
- Optimize marketing for popular cuisines
- Improve customer experience through data-driven decisions

---

*Developed during the Innomatics Research Labs Hackathon • April 2025*  
*Special thanks to mentors and organizers for this learning opportunity*
