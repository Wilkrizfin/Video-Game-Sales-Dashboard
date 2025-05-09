# 🎮 Global Video Game Sales – Excel Portfolio Project

## 📌 Project Overview

This Excel project explores global video game sales data from Kaggle. It showcases data cleaning, transformation, analysis, and interactive dashboard creation skills using a dataset of over 16,000 games across various platforms, genres, and regions.

---

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

## 🧹 Data Cleaning & 🔁 Data Transformation

- Converted range to Excel table for structured referencing.
- Checked and removed blank rows and duplicate entries.
- Used Power Query to format the `Year` column as Date.
- Replaced `N/A` values in the `Year` column with blank cells.
- Removed rows for years 2017 and 2020 due to insignificant data.
- Ensured `Global_Sales = NA + EU + JP + Other Sales` across all rows.

---

## 📊 Data Analysis

Key insights derived using PivotTables and visual exploration:

- Global sales trend by year  
- Sales distribution by region  
- Sales performance by genre  
- Top-selling video games  
- Platform market share  
- Leading publishers by sales  

---

## 📈 Dashboard

Created a dynamic Excel dashboard featuring:

- Column, bar, pie, and treemap charts  
- Timeline visualization for year-over-year sales  

![Dashboard](https://github.com/user-attachments/assets/08ebf64e-b7b5-4474-93c0-5c8555123d8d)

---

## 💡 Key Findings

- **Year 2008** recorded the highest global game sales.  
- **North America** is the top-performing region in terms of revenue.  
- **Action** and **Sports** dominate as the most popular genres globally.  
- **Wii Sports** holds the title of the best-selling game.  
- **PlayStation 2** leads in platform market share.  
- **Nintendo** is the highest-selling publisher by total sales.

---

## 🛠 Tools Used

- Microsoft Excel  
- Power Query  
- PivotTables  
- Data Cleaning 
- Charting & Timeline

---

## 📎 Files

- [`Global_Video_Game_Sales_Project.xlsx`](./vgsales%20analysis.xlsx) – Single Excel workbook with the following sheets:
  - `vgsales`: Original dataset  
  - `working_sheet`: Documented cleaning and transformation steps  
  - `analysis`: PivotTables and exploratory visualizations  
  - `analysis2`: PivotTable for regional sales distribution  
  - `dashboard`: Final interactive dashboard  

- [Dataset Source (Kaggle)](https://www.kaggle.com/datasets/thedevastator/global-video-game-sales)

---

## 👤 Author

**Wilkrizfin Penaranda**  
Entry-Level Data Analyst | 9 yrs in Sales & BizDev | Google-Certified 
[LinkedIn](https://www.linkedin.com/in/wilkrizfin-penaranda-90755197/)





