# Spotify Data Analysis Projects

This repository contains two data analysis projects using a Spotify dataset. In these projects, we clean the data, analyze song popularity, explore trends over the years, and visualize data to gain insights into different genres. Below are the steps and explanations of both projects.

## Project 1: Analyzing Popular Songs on Spotify

### Steps Involved:

1. **Collect and Clean Data:**
   - First, we collected the Spotify dataset and cleaned it to ensure accuracy for our analysis. Data cleaning included removing duplicates, handling missing values, and standardizing formats.

2. **Finding Top 10 Popular Songs:**
   - After cleaning, we extracted the top 10 most popular songs from the dataset. This was done by sorting the data by the `popularity` column and selecting the top 10 songs with the highest popularity scores.

3. **Filtering Songs with Popularity > 90:**
   - We filtered the dataset to find all songs that had a popularity score greater than 90, focusing on only the most popular tracks.

4. **Handling Release Date:**
   - We converted the `release_date` column from `datetime` format into a more readable `year` column, which allowed for better analysis and visualization by year.

5. **Checking Artist Information:**
   - We explored the artist details present in column 18 of the dataset. This column contained artist names, which were useful for deeper analysis of song trends by artist.

6. **Converting Duration:**
   - The song durations in the dataset were initially in milliseconds. We converted this to seconds to make the data easier to interpret.

7. **Creating a Sample DataFrame:**
   - A sample DataFrame was created from the original dataset for exploratory analysis and testing purposes.

8. **Regression Plots:**
   - We created regression plots to understand the relationships between certain variables:
     - **Loudness vs. Energy**: A regression plot was created to examine the correlation between song loudness and energy.
     - **Popularity vs. Acousticness**: Similarly, a regression plot was created to analyze the relationship between song popularity and acousticness.

9. **Creating a `year` Column:**
   - From the `release_date` column, we extracted the year and created a new `year` column to analyze trends over time.

10. **Analyzing Song Duration Over the Years:**
    - We explored how the duration of songs changed over the years. This provided insights into how song length trends evolved.

11. **Line Plot of Song Duration by Year:**
    - A line plot was created to visualize the average duration of songs across different years.

### End of First Project

## Project 2: Analyzing Song Genres on Spotify

### Steps Involved:

1. **Analyzing Song Duration by Genre:**
   - We explored how the duration of songs varied across different genres. This analysis helped us understand the characteristics of different genres based on song length.

2. **Top 5 Genres by Popularity:**
   - We analyzed the top 5 genres by popularity by filtering and sorting the dataset based on the genre and popularity columns.

### End of Second Project

## Conclusion

These two Spotify data analysis projects provided valuable insights into the most popular songs on the platform, trends over the years, and differences across music genres. The analysis included both statistical analysis and visualization using various plots.

## Tools and Libraries Used

- **Pandas**: For data cleaning, manipulation, and analysis.
- **Matplotlib/Seaborn**: For data visualization (line plots, regression plots).
- **Python**: For scripting and processing the dataset.

## Future Work

- Explore the impact of specific artists on song popularity.
- Analyze user interaction data (like streaming counts) for deeper insights into song performance.
- Expand genre analysis with more granular data on sub-genres.

### THE END OF OUR TWO SPOTIFY DATA ANALYSIS PROJECTS.
