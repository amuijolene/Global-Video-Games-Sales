# Global-Video-Games-Sales-Analysis

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset Breakdown](dataset-breakdown)
- [Tools](tools)
- [Data Cleaning/Preparation](data-cleaning/preparation)
- [Data Analysis](data-analysis)
- [Exploratory Data Analysis](exploratory-data-analysis)
- [Key Findings](key-findings)
- [Recommendations](recommendations)
- [Limitations](limitations)


## Project Overview

This project analyzes sales data from video games, exploring trends, regional preferences, and publisher strategies. By examining the complex relationships between game sales, genres, platforms, and publishers, this analysis provides valuable insights for industry stakeholders seeking to navigate the dynamic video game market.

### Dataset breakdown

The dataset utilized in this analysis consists of comprehensive sales data for the video game industry. It includes:
- 16,500+ video games with sales > 100,000 copies
- Fields: Rank, Name, Platform, Year, Genre, Publisher, Sales (NA, EU, JP, Other, Global)

### Tools

**Power BI** was utilized for data cleaning, analysis and creating a detailed report.

### Data Cleaning/Preparation

- Replaced N/A values with 0 where necessary
- Changed data types, ie. 6 decimal places to rounded up figues
- Used **DAX** to create calculated measures. This was done by converting decimal sales figures to millions by multiplying by 1,000,000.
  

### Data Analysis

This analysis explores key trends, factors, and relationships within the video game industry. It seeks to discover the below listed.
- Popular video games and revenue comparison
- Revenue trends and influencing factors over time
- Regional preferences, publisher strategies, and platform performance
- Revenue distribution across major geographical regions
- Impact of publishers, genre diversity, and platform availability on revenue trends

### Exploratory Data Analysis

This stage aimed to understand the dataset, identify patterns, and generate insights to inform our research questions.

Methods:
- Calculated descriptive statistics such as sum and average for sales figures.
- Created visualizations like bar charts and a pie  charts to illustrate data distributions.

Research questions:
1. What are the best-selling video games globally?
2. How have video game revenue trends evolved over time?
3. How do regional preferences and publisher strategies impact sales?
4. How does revenue distribution vary across geographical regions?
5. What factors directly influence revenue trends?


### Key Findings

Key insights derived from this analysis include:
1. North America leads global game revenue
2. Japan excels in role-play games and handheld gaming while other regions prefer action and sports games
3. Top publishers of all time are Nintendo, EA, Activision Blizzard, Sony
4. Regional preferences significantly impact games popularity and revenue distribution
5. The success of video games is influenced by the complex relationship between publishers and platforms.
   

### Recommendations

Strategic implications of this analysis include:
- Publishers should expand into digital and mobile platforms, address regional genre preferences
- Developers must leverage new technologies such as cloud gaming and subscription services to reach broader audiences
- Industry stakeholders can monitor shifting consumer preferences and adapt strategies accordingly to increase their revenue

### Limitations

This study acknowledges the following constraints and areas for future research:
- Missing sales data from 2017-2020 and some earlier years
- Incorporate additional data sources, explore microtransactions and DLC revenue in my next analysis
