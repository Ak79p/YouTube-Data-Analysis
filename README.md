# YouTube-Data-Analysis
A Python project for connecting to the YouTube Data API, searching and extracting video data, analyzing video statistics, and retrieving comments. The project involves creating an API key, installing necessary libraries, and performing data analysis on top videos related to a specific query.

## Overview

This project involves connecting to the YouTube Data API using a Python client to search for videos, extract data, and perform analysis. The focus is on videos related to the query "avatar movie" and includes tasks such as sorting videos by relevance, retrieving comments, and analyzing the likes vs views ratio.

## Project Structure

1. **Connect to the YouTube API**
    - Create a YouTube API key
    - Install the Google API Python client

2. **Search and Extract Data**
    - Search for videos related to the query string “avatar movie”
    - Provide statistics for the top 50 videos sorted by relevance in the US region

3. **Analyze the Data**
    - Sort the data by top 10 comments in descending order and consider the video IDs and Titles of these videos
    - Retrieve comments for the top 10 videos
    - Calculate and analyze the likes vs views ratio of the top 10 videos with the highest comments

## Getting Started

### Prerequisites

- Python 3.7 or higher
- `pip` for package management

### Installation

1. **Clone the repository**

    ```sh
    git clone https://github.com/Ak79p/YouTube-Data-Analysis.git
    cd YouTube-Data-Analysis
    ```

2. **Install the required packages**

    ```sh
    pip install google-api-python-client requests
    ```

3. **Set up the API Key**

    - Obtain your API key from the [Google Cloud Console](https://console.cloud.google.com/).
    - Replace `'YOUR_API_KEY'` in the script with your actual API key.

### Usage

1. **Connect to the YouTube API**

    Modify the `youtube_api.py` file to include your API key and configure the API connection.

2. **Search and Extract Data**

    Run the script to search for videos related to "avatar movie" and extract the top 50 videos.

    ```sh
    python search_videos.py
    ```

3. **Analyze the Data**

    Run the analysis script to sort videos by top comments, retrieve comments, and analyze likes vs views ratio.

    ```sh
    python analyze_data.py
    ```


## Contributing

Feel free to fork the repository, make improvements, and submit pull requests. For major changes, please open an issue first to discuss the change.

