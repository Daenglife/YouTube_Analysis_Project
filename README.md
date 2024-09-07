
# YouTube Channel Analytics Project

This project is designed to provide comprehensive insights into YouTube channel and video performance using the YouTube API. It involves data extraction, transformation, visualization, and reporting through Python and Power BI.

## Features

- **YouTube Channel Analytics**: Extracts channel-level metrics such as:
  - Channel Name
  - Subscriber Count
  - Total Views
  - Number of Videos
  
- **YouTube Video Analytics**: Focuses on extracting video-level performance metrics:
  - Video Titles
  - View Counts
  - Likes
  - Comments

- **Data Analysis & Visualization**:
  - Data is organized into Pandas DataFrames for analysis.
  - Visualizations are created using Seaborn to present insights on channel and video performance clearly.

- **Power BI Report**: 
  - Data transformed using DAX functions and Power BI queries to build dynamic, interactive visualizations.
  - Key insights presented through Power BI include:
    - Subscriber growth trends.
    - Video performance analysis (views, likes, engagement).
    - Comparative analysis of channel statistics.
  - Data modeling and transformation were performed to structure the data in a way that allowed for efficient analysis.

## Technology Stack

- **Python**:
  - `google-api-python-client` for interacting with the YouTube Data API.
  - `pandas` for data manipulation and analysis.
  - `seaborn` for data visualization.
  
- **Power BI**:
  - DAX (Data Analysis Expressions) for creating calculated columns and measures.
  - Queries to transform and shape data.
  - Interactive dashboards for reporting.

## Prerequisites

To run the project, you will need:

- Python 3.x installed
- YouTube API Key (Refer to [YouTube API Documentation](https://developers.google.com/youtube/v3) for setup instructions)
- Python libraries: `google-api-python-client`, `pandas`, `seaborn`

Install the required packages using:
```bash
pip install google-api-python-client pandas seaborn
```

## Setup Instructions

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/YouTube_Channel_Analytics.git
    ```

2. Obtain your YouTube API Key and update the API key section in the script.

3. Run the Python script to extract and analyze data:
    ```bash
    python youtube_analysis.py
    ```

4. To view interactive visualizations and insights, open the provided Power BI report file.

## Example Visualizations

- Bar charts comparing subscriber counts across channels.
- Scatter plots showing video views versus likes for performance analysis.

## Power BI Report

The Power BI report provides additional insights and interactivity, allowing users to:
- Filter data dynamically by time periods and engagement metrics.
- View growth trends and identify high-performing content.

## Contributions

Feel free to contribute to this project by submitting issues or pull requests. Any feedback is welcome!

