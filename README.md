# YouTube Data Harvesting and Warehousing

This project is a **Streamlit-based** application that integrates the **YouTube API**, **MongoDB**, and **PostgreSQL** to enable efficient data harvesting, storage, and analysis of YouTube channel data. The tool offers a user-friendly, interactive interface for collecting, storing, and analyzing YouTube channel-related data, such as channels, videos, playlists, and comments. It provides a seamless experience for data migration between MongoDB and PostgreSQL, alongside powerful data query capabilities.

## Features

### YouTube API Integration
The application integrates with the **YouTube Data API v3** to collect data about:
- **Channels**: Information like the channel name, description, subscriber count, view count, and the playlist ID associated with the channel.
- **Playlists**: Data about related playlists, including the title, video count, and publish date.
- **Videos**: Video details, such as the video title, description, tags, published date, view count, like count, and more.
- **Comments**: Retrieves the first 50 comments of each video, including text, author, and timestamp.

### Data Storage
The tool allows data to be stored in:
- **MongoDB**: Used for unstructured data storage. MongoDB's flexibility allows for easy management and retrieval of YouTube data.
- **PostgreSQL**: A relational database used to store the data in structured tables. The data can be queried and analyzed using SQL for better insights.

### Interactive Interface
- **Streamlit Dashboard**: The application provides a simple and user-friendly dashboard to interact with the data, migrate between databases, and perform analysis on YouTube channel data.
- **Data Collection**: Collect data from YouTube by entering a channel ID and storing it in MongoDB.
- **Data Migration**: Migrate data from MongoDB to PostgreSQL.
- **Data Visualization**: View tables and run various SQL queries to analyze YouTube data, such as the most viewed videos, most liked videos, total views per channel, etc.

### Advanced Queries
Pre-defined SQL queries can be executed, such as:
- Top 10 most viewed videos.
- Channels with the most number of videos.
- Videos with the highest number of comments.
- Videos published in a specific year (e.g., 2022).
- Average duration of videos in each channel.

---

## Requirements

### Python Libraries
This application uses several Python libraries that you need to install before running the application. You can install all dependencies from the `requirements.txt` file.

```bash
pip install -r requirements.txt
