#Global Video Game Sales Analysis (1980-2016)

## Overview
This Power BI dashboard provides an interactive analysis of historical video game sales data from 1980 to 2016. It explores trends across publishers, platforms, genres, and regions to identify key insights about the gaming industry's evolution and market dynamics.
## Key Features
- **Publisher Performance**: Top companies by global sales
- **Sales Trends**: Yearly sales evolution (1980-2016)
- **Platform Comparison**: Sales distribution across consoles
- **Genre Analysis**: Popularity of game genres
- **Regional Breakdown**: Sales in NA, EU, JP, and other regions
- **Interactive Filters**: Filter by year, platform, genre, and publisher

## Data Processing
Data was cleaned and transformed due to inconsistencies in the original dataset:
- Removed columns with significant missing values (e.g., critic scores)
- Handled null values in `Year` and `Publisher`
- Created calculated columns:
  - `Decade` (e.g., "1990s")
  - `Sales_Category` (e.g., "Blockbuster", "Hit")
- Used Excel for initial cleaning before loading into Power BI

## Tools Used
- **Microsoft Power BI**: Dashboard design and DAX calculations
- **Power Query**: Data transformation and integration
- **DAX**: Measures for sales percentages, rankings, and trends
- **Microsoft Excel**: Initial data cleaning
- **Kaggle**: Data sourcing

## Insights Discovered
1. **Nintendo dominated global sales** due to iconic franchises like Mario and Pokémon
2. **The gaming industry peaked in sales** between 2005-2010 (Wii/PS3 era)
3. **Action and Sports genres** were the most profitable globally
4. **Regional preferences** were significant:
   - Japan favored RPGs and Nintendo platforms
   - North America preferred shooters and Xbox platforms
   - Europe showed balanced preferences across genres

## 📎 Data Source
[Video Game Sales - Kaggle Dataset](https://www.kaggle.com/datasets/gregorut/videogamesales)  
*Note: Data includes sales until 2016*

## 👨‍💻 Author
**Your Name**  
- 📧 Email: marcosghc11@gmail.com
- 💼 LinkedIn: https://www.linkedin.com/in/marcos-gael-hern%C3%A1ndez-cruz-80757536b?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app


