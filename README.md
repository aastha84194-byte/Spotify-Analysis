# Spotify-Analysis
A comprehensive end to end analysis project transforming raw spotify listening history into actionable business insights through advanced visualization, DAX modelling, and automated governance frameworks 
# Spotify Listening Data Analysis 🎵

## Project Overview
This project provides a comprehensive analysis of personal Spotify listening history. By processing raw telemetry data, the project uncovers trends in artist preferences, album engagement, and daily listening habits. 

The analysis transitions from raw data processing to high-level business intelligence insights, visualized through interactive dashboards.

## Key Features
- **Temporal Analysis:** Heat maps identifying peak listening hours and weekday vs. weekend patterns.
- **Artist & Album Metrics:** Identification of Top 5 artists/albums and Year-over-Year (YoY) growth analysis.
- **Engagement Quadrants:** Scatter plots categorizing tracks by frequency and total listening time.
- **Drill-Through Reporting:** Detailed grid views allowing for deep dives into specific tracks and albums.

## Data Pipeline
1. **Requirement Gathering:** Defining business questions (e.g., "What are my top-played albums?").
2. **Data Cleaning:** Handling null values and formatting timestamps from `spotify_history.csv`.
3. **Data Modeling:** Creating relationships between tracks, artists, and time dimensions.
4. **DAX Calculations:** Implementing custom measures for LY (Latest Year) and PY (Previous Year) comparisons.
5. **Insights Generation:** Identifying niche vs. mainstream listening patterns.

## Tech Stack
- **Analysis Tool:** Power BI / Excel (as detailed in the PPTX)
- **Data Source:** Spotify Personal Data (CSV)
- **Concepts:** DAX, Data Modeling, Root Cause Analysis (RCA), Heat Maps.

## Files in this Repository
- `spotify_history.csv`: The raw dataset containing track URIs, timestamps, and playback details.
- ``: The raw dataset containing track URIs, timestamps, and playback details.

## Visuals
*(Optional: Add screenshots of your dashboard here to make the README pop!)*
