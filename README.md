# 🎮 Global Video Game Sales – Excel Portfolio Project

## 📌 Project Overview

This Excel project explores global video game sales data from Kaggle. It showcases data cleaning, transformation, analysis, and interactive dashboard creation skills using a dataset of over 16,000 games across various platforms, genres, and regions.

## 📂 Dataset

- **Source**: [Kaggle: Global Video Game Sales](https://www.kaggle.com/datasets/thedevastator/global-video-game-sales)
- **Rows**: 16,598
- **Columns**: 11

### Column Description:
| Column       | Description                                     |
|--------------|-------------------------------------------------|
| Rank         | Global sales rank                               |
| Name         | Name of the video game                          |
| Platform     | Platform on which the game was released         |
| Year         | Year of release                                 |
| Genre        | Game genre                                      |
| Publisher    | Publishing company                              |
| NA_Sales     | Sales in North America (millions)               |
| EU_Sales     | Sales in Europe (millions)                      |
| JP_Sales     | Sales in Japan (millions)                       |
| Other_Sales  | Sales in other regions (millions)               |
| Global_Sales | Total global sales (millions)                   |

---

## 🧹 Data Cleaning

- Created a table format.
- Checked blank rows and duplicates.
- “Year” column formatted to date format via Power Query.
- Rows of the “Year” column with N/A values changed to blank.
- Removed 2017 & 2020 as there is no significant data.
- Ensured `Global_Sales` = sum of all regional sales.

---

## 🔁 Data Transformation

- Created `Sales_Per_Region_Percentage` columns
- Added `Decade_Released` from the `Year` column
- Aggregated data by `Platform`, `Genre`, and `Publisher`

---

## 📊 Data Analysis

Key insights:
- Global sales trend by year
- Sales Distribution by region
- Sales by Genre
- Best-selling video games
- Platform Market share 
- Top-selling publishers


Tools used:
- Power Query
- PivotTables
- Conditional formatting

---

## 📈 Dashboard

Created a dynamic dashboard with:
- Charts (column, bar, pie, treemap)
- Timeline

---

## 💡 Key Findings

- 2008 had the highest record global sales.
- The North America region contributes the largest share of game sales.
- **Action** and **Sports** are the most popular genres worldwide.
- Wii Sports is the best-selling video game.
- Playstation 2 has the largest market share among the platform followed by Playstation 3, X360 and Wii.
- Nintendo has the highest game sales among the publishers.

---

## 🛠 Tools Used

- Microsoft Excel
- Power Query
- PivotTables
- Charts and Timeline
- Data Cleaning & Formulas

---

## 📎 Files

- `Global_Video_Game_Sales_Dashboard.xlsx`: Final dashboard
- `Charts_and_PivotTables.xlsx`: All analysis visuals
- `Data_Cleaning_Steps.xlsx`: Documented cleaning process
- `Data_Dictionary.txt`: Dataset column descriptions

---

## 👤 Author

**[Wilkrizfin Penaranda]**  
Aspiring Data Analyst | Excel & Data Visualization Enthusiast  
[LinkedIn](#) | [GitHub](#)
