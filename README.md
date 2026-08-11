# YouTube Trending Data Analysis

## Project Overview

This project analyzes YouTube trending video data from multiple countries using Python and Pandas.

The project was completed during my first semester of the Master's in Data Science as part of the Foundations of Computer Science course.

The analysis focuses on video engagement, tags, publishing patterns, trending videos, channels, and video categories.

## Questions Explored

The project investigates:

- Which videos have no tags?
- Which channels have the highest total number of views?
- How should videos with disabled comments, disabled ratings, or video errors be handled?
- What is the ratio between likes and dislikes?
- How are videos distributed across 10-minute publishing intervals?
- Which publishing intervals contain the most videos?
- Which tags are used most frequently?
- How does the like/dislike ratio of tags vary across countries?
- Which video has the highest number of views for each trending date and country?
- Which videos have the highest number of views for each month and country?
- How can YouTube category information be combined with the video data?
- How many videos have categories that cannot be assigned?

## Key Findings

Some observations from the analysis include:

- **ChildishGambinoVEVO** had the highest aggregated number of views among the channels analyzed, with approximately **11.0 billion views**, followed by Marvel Entertainment with approximately **10.4 billion**.
- `[none]` was the most frequently occurring tag, appearing in **35,518 videos**, followed by `"funny"` (14,834), `"comedy"` (11,900), and `"2018"` (10,567).
- The number of videos with unassignable categories varied considerably between countries. **Russia had the highest count in the analysis with 1,301 videos**, while Japan had 18.

## Dataset

The project uses YouTube Trending Video datasets from multiple countries, including:

- Canada (CA)
- Germany (DE)
- France (FR)
- Great Britain (GB)
- India (IN)
- Japan (JP)
- South Korea (KR)
- Mexico (MX)
- Russia (RU)
- United States (US)

The dataset includes information such as:

- Video titles
- Channel names
- Views
- Likes and dislikes
- Tags
- Publishing dates
- Trending dates
- Categories
- Comments and ratings information

Category information is provided through the corresponding JSON files.

## Technologies Used

- Python
- Pandas
- Jupyter Notebook
- CSV
- JSON


## Academic Context

**Course:** Foundations of Computer Science  
**Program:** Master's in Data Science  
**Project Grade:** 28/30  
**Written Exam:** 28/30

## Author

**Duaa Zahur Siddiqui**

Master's in Data Science

## Project Structure

```text
Youtube-trending-data-analysis/
├── README.md
├── youtube_trending_analysis.ipynb
├── .gitignore
├── .gitattributes
└── data/
    ├── YouTube trending CSV files
    └── YouTube category JSON files



