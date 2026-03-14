# US Birth Data Analysis (1994–2014)

## Project Overview
This project analyzes United States birth data using Python.  
The dataset contains daily birth records including year, month, date, day of the week, and number of births.

The goal of this project is to explore birth trends and patterns using data analysis and visualization techniques.

---

## Dataset
Two datasets were used in this project:

- US_births_1994-2003_CDC_NCHS.csv
- US_births_2000-2014_SSA.csv

Each dataset contains the following columns:

| Column | Description |
|------|-------------|
| year | Year of birth |
| month | Month of birth |
| date_of_month | Day of month |
| day_of_week | Day of week |
| births | Number of births |

---

## Questions Answered

1. What is the total number of births between 1994 and 2003?
2. How many births occurred each year?
3. Which month has the highest number of births?
4. Which month has the lowest number of births?
5. How many babies were born in May 1998?
6. What is the average number of births per day?
7. Which day of the week has the highest number of births?
8. How do birth patterns vary by month and weekday?

---

## Key Results

- Total births (1994–2003): **39,722,137**
- Total births (2000–2014): **62,187,024**
- Month with highest births: **August**
- Month with lowest births: **February**
- Births in May 1998: **330,519**
- Average births per day: **10,876**

---

## Visualizations

The project includes the following visualizations:

- Line chart showing birth trends by year
- Bar chart showing total births by year
- Bar chart showing births by day of week
- Heatmap showing birth patterns by month and weekday

---

## Tools and Libraries

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Imports the correct for your project are: 
```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
```
## Import the dataset
```python
df = pd.read_csv("US_births_1994-2003_CDC_NCHS.csv")
print(df.head())
```
---
|year| month| date_of_month| day_of_week| births|
|......|......|........|........|.........|
|0| 1994| 1| 2| 7| 8006|
|2|1994| 1| 3| 1| 11363|
|3| 1994| 1| 4| 2| 13032|
|4|1994| 1| 5| 3| 12558|
---

## Author

Shiva  
Data Analytics Enthusiast
