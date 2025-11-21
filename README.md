# Understanding Bicycle Theft Patterns in Toronto  
Exploratory Data Analysis (EDA) in R

---

## 1. Title  
Understanding Bicycle Theft Patterns in Toronto: When, Where, and Which Bikes Are Stolen

---

## 2. Executive Summary  
This project analyzes reported bicycle thefts in Toronto to identify when, where, and what types of bikes are most frequently stolen. The analysis reveals seasonal and weekly patterns, with thefts peaking in the summer (especially July) and most commonly occurring on Fridays and during evening hours. Mountain and road bicycles are the most frequently stolen, and the highest-risk areas are concentrated in Toronto’s downtown core (Divisions D52, D14, D51). These insights can support cyclists, city planners, and law enforcement in developing better prevention strategies.

Monthly Trend of Bicycle Thefts  
![Thefts by Month](graphs/thefts_by_month.png)

Bicycle Thefts by Day of the Week  
![Thefts by Day](graphs/thefts_by_day.png)

Most Common Bike Types Stolen  
![Thefts by Bike Type](graphs/thefts_by_bike.png)

---

## 3. Business Problem  
Bicycle theft affects thousands of Toronto cyclists each year, resulting in financial loss and reduced confidence in urban cycling. Without understanding the underlying patterns in theft behavior, it is difficult for both individuals and public organizations to take informed action.

Core questions answered in this project:
1. When are bike thefts most likely to occur (month, weekday, hour)?
2. Where are thefts concentrated (police divisions, neighborhoods)?
3. Which bike types are at highest risk?
4. How can data support theft prevention and resource allocation?

---

## 4. Methodology  
- Dataset: Toronto Police Service Open Data – Bicycle Theft Records  
- Tools Used: R (dplyr, ggplot2) for data cleaning, analysis, and visualization  
- Steps Taken:
  - Cleaned and standardized theft records (date, time, bike type, premise type)
  - Performed time-based trend analysis (monthly, weekday, hourly patterns)
  - Conducted categorical breakdowns (bike type, premise type)
  - Mapped theft concentration by police division and neighborhood
  - Created visual summaries (bar charts, heatmaps, and ranking tables)

Thefts by Time and Location (Heatmap)  
![Thefts by Location and Time](graphs/thefts_by_location.png)

Bicycle Thefts by Police Division  
![Thefts by Police Division](graphs/thefts_by_police_division.png)

Bike Theft Hotspots in Downtown West  
![Thefts by Downtown West](graphs/thefts_by_downtown_west.png)

Note: R scripts will be uploaded to this repository under `/src`.

---

## 5. Skills  
| Category | Skills Demonstrated |
|----------|---------------------|
| Programming & Analysis | R, data wrangling, grouping, summarization |
| Visualization | Time-series charts, heatmaps, bar charts |
| Domain Knowledge | Crime analytics, public safety data |
| Data Communication | Insight storytelling, structured reporting |
| Repository Skills | GitHub organization, project documentation |

---

## Dataset  
This project uses publicly available bicycle theft data from the Toronto Police Service Open Data Portal.

- Official source: https://data.torontopolice.on.ca/datasets/TorontoPS::bicycle-thefts-open-data/about  
- Local copy included in this repository: [`/data/Bicycle_Thefts_Open_Data.csv`](data/Bicycle_Thefts_Open_Data.csv)

The dataset contains more than 36,000 reported bicycle thefts, including variables such as theft date, report date, location type, police division, and bike type.

---

Repository structure:

