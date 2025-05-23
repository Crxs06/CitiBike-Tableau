# CitiBike-Tableau
# 📊 Citi Bike Summer 2013 Data Analysis

## 🛠️ Project Overview
This Tableau project analyzes Citi Bike trip data from **June–August 2013** to uncover two unexpected phenomena in New York City’s bike-sharing system.

Using cleaned and combined CSVs, we created visualizations that explore:

- Imbalanced station usage across the city
- Behavioral differences between Subscriber and Customer riders

The analysis is presented in two interactive dashboards and compiled into a clear, professional Tableau Story intended for city officials and transportation planners.

---

## 🧩 Datasets Used
- `201306-citibike-tripdata.csv`
- `201307-citibike-tripdata.csv`
- `201308-citibike-tripdata.csv`

Each CSV contains trip history logs including start/end times, station locations, user types, and trip durations.

---

## 📈 Dashboards

### Dashboard 1: Station Popularity
- Visualizes the top 10 and bottom 10 start and end stations by number of trips.
- Reveals heavy usage at key hubs like **Penn Station** and **Central Park**, while many stations remain underutilized.

### Dashboard 2: User Type Behavior
- Compares average trip durations and trip counts between **Subscribers** (members) and **Customers** (casual users).
- Shows that **Subscribers** tend to take shorter, more regular trips (likely commuters).
- **Customers** take longer trips, likely tourists or infrequent riders.

---

## 📘 Tableau Story
The story combines both dashboards with descriptive captions and a summary slide. It’s designed to be readable by non-analyst audiences, with a focus on public sector decision-makers.

---

## 🔍 Key Insights
- **Disproportionate Station Usage**: A few stations account for the majority of trips, suggesting some stations may be poorly placed or under-promoted.
- **Distinct User Behavior**: Different rider types have distinct needs — offering potential to optimize pricing, bike availability, and outreach.

---

## ✅ Files Included
- `/CitiBikeCSVs/`: Folder with cleaned CSVs for June–August 2013  
- `CitiBike_Tableau_Project.twb`: Tableau workbook with all sheets, dashboards, and story  
- `README.md`: Project summary (this file)

---

## 💡 Future Improvements
- Add a dynamic map showing station activity over time  
- Overlay socioeconomic data (e.g., zip code income levels) for deeper geographic insights  
- Expand analysis to other seasons or more recent years
