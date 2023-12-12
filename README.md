# Movie Reviews and Data Aggregation Script

## Overview
This script is designed to fetch and analyze movie reviews from the New York Times API and detailed movie data from The Movie Database (TMDB) API. It filters for movie reviews with specific criteria, extracts relevant information, and merges it with detailed movie data from TMDB, resulting in a comprehensive dataset.

## Features
- **API Integration**: Connects with the New York Times and The Movie Database APIs.
- **Data Extraction and Transformation**: Gathers movie reviews and detailed movie information, and transforms this data into a structured format.
- **Data Normalization**: Combines data from both sources into a unified DataFrame.
- **Cleaning and Exporting Data**: Cleans the merged dataset and exports it to a CSV file.

## Prerequisites
To use this script, you need Python with the following libraries installed:
- `requests`
- `pandas`
- `python-dotenv`

Also, ensure you have a `.env` file with your NYT and TMDB API keys set as `NYT_API_KEY` and `TMDB_API_KEY` respectively.

## Usage
Run the script in a Python environment. The script will:
1. Fetch movie reviews based on specified criteria from the New York Times API.
2. Extract relevant movie titles and use them to fetch detailed movie data from TMDB API.
3. Merge, clean, and export the data to a CSV file.