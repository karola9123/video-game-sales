# Video Games Sales Analysis

Analysis of global video game sales to identify key trends in publishers, genres, and top-performing titles.  
The dataset includes sales figures for different regions: North America (NA), Europe (EU), Japan (JP), and Other.

## Dataset

- Source: [Kaggle - Video Game Sales](https://www.kaggle.com/datasets/gregorut/videogamesales)
- Rows: 16,599
The dataset contains 12 rows of detailed information on video game sales, including:
Rank – overall sales ranking
Name – title of the game
Platform – the gaming platform on which the game was released (e.g., Wii, PS2, PC)
Year – year of release
Genre – game genre (e.g., Sports, Adventure, Platform).
Publisher – game publisher.
Regional Sales – sales in millions of units for:
NA – North America
EU – Europe
JP – Japan
Other – other regions
Global Sales – total worldwide sales

## Tools Used

- **Excel** – Pivot Tables, Slicers, Charts
- **Data visualization** – Column and bar charts for comparative analysis
- **Interactive filtering** – Slicers

## Analysis Overview

Project Goal:
The aim of this analysis was to explore global video game sales data to uncover insights about publishers, genres, and top-selling games across different regions and years.

**Objectives:**
- Identify which publishers sell the most games regionally and globally.
- Determine the most common game genres and which genres sell best.
- Highlight the most popular game titles overall and in each region.
- Analyze the number of games released and their sales by year.

**Data Cleaning:**
Initially, the year column contained empty values, which I cleaned before proceeding with the analysis.

### 1. Sales by Region

I created pivot tables to show sales by publisher for regions (EU, JP, NA, Other).
Created a chart for global sales by publisher.

**Findings:**
Nintendo is the top publisher in most regions; only in "Other" does Electronic Arts lead.
In Japan, the ranking differs: Nintendo is first, followed by Namco Bandai Games and Konami, showing a distinct Japanese market.
<img width="1443" height="592" alt="sales by region" src="https://github.com/user-attachments/assets/b700c856-65cf-4f3e-9e43-4c9370bf16f2" />
I also added a table of publishers by the number of released games shows Nintendo only in 7th place, yet it leads in total sales.
<img width="500" height="510" alt="publisher and count of games" src="https://github.com/user-attachments/assets/a50184c3-f729-423f-b636-8c4574838ced" />

### 2. Games by Genre

I created pivot table showing the number of games per genre, with a chart and pivot table showing sum of global sales per genre, with a slicer for platforms. Selecting a platform updates the table and chart.

<img width="1413" height="601" alt="games by genre" src="https://github.com/user-attachments/assets/8bede557-7c12-439a-b836-a3b007985d7a" />

**Findings:**
The most common genres are Action and Sports.
Platform affects genre distribution:
Wii: mostly Sports games
PC: Strategy, Action, Shooter, Simulator
PS1 & PS2: mostly Sports
PS3 & PS4: mostly Action
Interestingly, Shooter ranks third in total sales but only fifth in number of titles.


### 3. Best-Selling Games

I created pivot table of top 10 game titles by sales in different regions, with color highlighting for the top three titles in each region. Added interactive slicers for Year and Genre.

<img width="1367" height="541" alt="best games" src="https://github.com/user-attachments/assets/91ef54d1-e461-4d93-88b8-b1890755c05f" />

**Findings:**
The best-selling game overall is Wii Sports, but in Japan, it ranks only 6th.
Other top-selling games include GTAV, Super Mario Bros., and Tetris.


## 4. Games by Year

Pivot table showing the number of games released per year and their total sales.

<img width="1333" height="487" alt="sales by year" src="https://github.com/user-attachments/assets/132c2255-c404-4181-9305-6a98e4eeefbd" />


**Findings:**

Years with the most titles released: 2009, 2008, 2010, 2007, 2011.
Years with the highest sales: 2008, 2009, 2007, 2010, 2006.

## Files in this repository
- `game_sales.xlsx` – Full Excel analysis with pivot tables, slicers, and charts
- `README.md` – Project description and key insights
