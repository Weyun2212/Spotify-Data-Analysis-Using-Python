# Spotify-Data-Analysis-Using-Python
In this project, we analyze Spotify music data using Python to uncover insights about song attributes, artists, and user listening behaviors. By performing exploratory data analysis (EDA), we aim to identify patterns in music preferences, the relationship between different song features and trends over time.
📌 Project Overview

The objective of this analysis is to explore Spotify track and artist data to:

- Identify the least and most popular songs

- Understand the distribution of track attributes (danceability, energy, acousticness, etc.)

- Analyze correlations between audio features

= Study how music has evolved over time

- Explore genre-specific characteristics, including popularity and duration

📂 Dataset Description

This project uses two primary datasets:

1. tracks.csv

- Contains detailed information about songs, including:

- Track ID, name, artists

- Popularity

- Duration (ms)

- Release date

- Explicit status

Audio features:
danceability, energy, loudness, speechiness, acousticness, instrumentalness, liveness, valence, tempo, time_signature

2. artists.csv

Includes:

- Artist ID

- Artist name

- Followers

- Popularity

- Genres (may include multiple genres per artist)

🧠 Methodology
1. Data Loading

- Imported both CSV files into Pandas DataFrames.

2. Data Inspection

- Checked null values, data types, and dataset structure.

3. Data Cleaning & Transformation

- Converted duration_ms → duration in seconds

- Parsed release_date into datetime format

- Extracted release_year for time-series analysis

- Cleaned and exploded multi-genre fields for accurate genre-level insights

4. Exploratory Data Analysis (EDA)

- Identified most and least popular tracks

- Generated descriptive statistics

- Computed Pearson correlation across numerical features

- Created regression plots for feature relationships

Analyzed yearly trends in:

- Number of songs released

- Average song duration

- Grouped tracks by genre to compute:

- Average popularity

- Average duration

5. Visualization

- Using Matplotlib and Seaborn, the analysis includes:

- Correlation heatmap

- Regression plots

- Histograms

- Yearly trend line charts

- Genre-level bar charts

⭐ Key Findings
1. Popularity

Several songs recorded zero popularity, often older or niche tracks.

Top track examples included songs like “Peaches”.

2. Feature Correlation

Strong positive correlation between loudness and energy.

Negative correlation between acousticness and popularity, indicating acoustic tracks tend to be less mainstream.

3. Temporal Trends

Steady rise in number of songs released per year.

Noticeable shifts in average song duration, with trends varying across decades.

4. Genre Insights

Genres like newcastle nsw indie and pittsburgh indie ranked highest by average popularity.

Dark hardcore and bulgarian experimental had the longest average durations, reflecting unique stylistic patterns.

📊 Visualizations Included

✔ Correlation Heatmap

✔ Loudness vs Energy (Regression Plot)

✔ Popularity vs Acousticness (Regression Plot)

✔ Histogram of Song Releases by Year

✔ Average Song Duration per Year

✔ Genre-wise Average Duration (Horizontal Bar Plot)

✔ Top 5 Genres by Popularity (Bar Plot)

🏁 Conclusion

This project provides a comprehensive analysis of Spotify’s musical landscape, revealing how audio features, genres, and trends evolve over time. By examining popularity, correlations, and genre-level attributes, we gain valuable insights into listener preferences and industry dynamics.
The project also demonstrates effective data cleaning, transformation, and visualization techniques—making it a solid foundation for more advanced music recommendation systems or predictive models.
