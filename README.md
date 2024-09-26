
# Netflix Movies and TV Shows - Exploratory Data Analysis (EDA)

## Project Overview
This project performs an Exploratory Data Analysis (EDA) on a Netflix dataset containing information about movies and TV shows available on the platform. The goal of the project is to uncover insights about Netflix’s content, such as the distribution of movies and TV shows, content production trends, and identifying the most popular genres, directors, and regions producing content.

## Dataset Information
The dataset contains the following features:
- **show_id**: Unique ID for each movie or TV show.
- **type**: Indicates whether the content is a movie or TV show.
- **title**: Title of the movie/TV show.
- **cast**: Main cast members.
- **country**: Country of origin.
- **date_added**: Date the content was added to Netflix.
- **release_year**: Year the content was released.
- **rating**: Content rating (e.g., PG, R).
- **duration**: Duration of the movie or the number of seasons (for TV shows).
- **listed_in**: Genres or categories of the content.
- **description**: Short description of the content.

## Objectives
- **Content Distribution**: Analyze the balance between movies and TV shows.
- **Content Production Over Time**: Discover trends in content production by year.
- **Country and Regional Analysis**: Identify which countries produce the most Netflix content.
- **Genre Analysis**: Understand the distribution of genres across movies and TV shows.
- **Director and Actor Insights**: Explore the most frequent directors and actors.
- **Missing Data**: Handle and assess the impact of missing values.

## Key Insights
1. **Movies vs. TV Shows**: Netflix has more movies than TV shows, but TV shows have a larger presence in recent years.
2. **Content Production Over Time**: Content production peaked in recent years, with most content being released after 2010.
3. **Country Distribution**: The United States is the largest producer of Netflix content, followed by India.
4. **Popular Genres**: Drama and Comedy are the most common genres, and there is a significant amount of International content.
5. **Missing Values**: Missing data is present in columns like `director` and `cast`, which may affect specific analyses.

## Tools and Libraries Used
- **Pandas**: For data cleaning, manipulation, and exploration.
- **NumPy**: For handling numerical operations and arrays.
- **Matplotlib**: For creating static, visually appealing graphs.
- **Seaborn**: For enhanced data visualization and aesthetics.

## Analysis Workflow
1. **Data Loading**: The dataset is loaded into a Pandas DataFrame.
2. **Initial Exploration**: A preliminary analysis is conducted to understand the structure of the data.
3. **Handling Missing Data**: Missing values are identified and handled appropriately to avoid bias in analysis.
4. **Data Visualization**: Visualizations (bar plots, histograms, and heatmaps) are created to explore content distribution, trends, and correlations.

## Conclusion
This EDA reveals interesting trends about Netflix's content, highlighting the platform's global reach, increasing content production, and audience preferences. The analysis provides valuable insights that can inform content recommendations, marketing strategies, and further research into viewer preferences.

---
