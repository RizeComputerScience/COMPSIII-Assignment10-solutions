# Assignment #10: Analyzing Music Streaming Data

Every year, millions of Spotify users eagerly await the results of their yearly Spotify Wrapped. The yearly list showcases a user's top artists, songs, genres, minutes listened, and much more.

![Spotify Wrapped](img/Wrapped.png)
**Source**: [Spotify](https://newsroom.spotify.com/2024-12-04/the-art-and-science-behind-spotify-wrapped/)

This yearly event requires a massive amount of data analysis for each individual Spotify user. For each user Spotify needs to calculate the minutes listened, top artists, top genre, and much more! How do computer programmers perform data analysis and create visualizations for millions of users?

![Spotify ](img/Spotify.png)
**Source**: [Spotify Design](https://spotify.design/article/making-moves-designing-motion-for-2022-wrapped)

**TASK**: You will perform your own Spotify Wrapped analysis using the `pandas` and `matplotlib` libraries using the personal listening history CSV that has been provided with this assignment. From the data that is stored in this CSV, you’ll generate statistical insights and data visualizations using the `pandas` and `matplotlib` libraries.

## Assignment Requirements

A completed `streaming_analysis.py` file should contain:
- A DataFrame with at least 4 columns and 10 items/entries. The DataFrame should contain data stored in [`streaming_data.csv`](streaming_data.csv) that is read using the [`.read_csv()`](https://www.w3schools.com/python/pandas/pandas_csv.asp) method.
- A descriptive statistical analysis on your DataFrame using Pandas. This analysis should include:
    - Average of `completion_rate` column
    - Calculated total time the listener spent listening to music
    - A Dataframe of the top 5 most listened to artists. 
    - A Datagrame of the top 10 most listened to songs.
    - A DataFrame of the top 5 most streamed genres.
    - Calculated value for the amount of songs listened to by day.
    - Calculated value for the amount of songs listened to by month.
- Code to generate a line graph, bar chart, and histogram using Matplotlib.

## Example Inputs and Outputs

```bash
'''
Your Year in Music Summary: 
Average Completion Rate: XXXXX 
Total Listening Time (seconds): XXXXX

Top Artists: 
artist 
Artist 1          139 
Artist 2          132 
Artist 3          130 
Artist 4           98 
Artist 5           96 
Name: count, dtype: int64

Top Songs
song 
Song 1        44 
Song 2        42 
Song 3        38 
Song 4        37 
Song 5        33 
Song 6        31 
Song 7     31
...more songs not shown

...grere, day, and month information not shown
'''
```