# Netflix Content Trends Analysis (VOIS AICTE Oct 2025 Major Project)

## Table of Contents
- [Overview](#overview)
- [Objective](#objective)
- [Dataset](#dataset)
- [Features Analyzed](#features-analyzed)
- [Methodology](#methodology)
- [Key Insights](#key-insights)
- [Tools & Libraries](#tools--libraries)
- [Project Structure](#project-structure)
- [Future Enhancements](#future-enhancements)
- [Author](#author)

---

## Overview
This project analyzes Netflix’s Movies and TV Shows released from **2008 to 2021**, containing **7,789 records**. The analysis focuses on understanding content trends, identifying popular genres, analyzing release patterns, and evaluating regional contributions. The insights aim to help **streaming platforms, content creators, and researchers** make informed decisions about content production and acquisition.

---

## Objective
- Examine the distribution of Movies vs TV Shows.  
- Identify popular genres and categories over time.  
- Analyze geographical contributions to Netflix content.  
- Explore content ratings trends and their patterns.  
- Provide actionable insights for strategic content planning.

---

## Dataset
The dataset contains the following key attributes:

| Attribute      | Description |
|----------------|-------------|
| **Title**      | Name of the movie or TV show |
| **Director**   | Director(s) of the content |
| **Cast**       | Actors/Actresses involved |
| **Country**    | Country where the content was produced |
| **Date Added** | Date when the content was added to Netflix |
| **Release Year** | Year of original release |
| **Rating**     | Content rating (PG, TV-MA, etc.) |
| **Duration**   | Length of the movie or number of seasons |
| **Genres/Category** | Type of content (Action, Comedy, Drama, etc.) |

**Source:** Public Netflix dataset from Kaggle / VOIS project dataset.

---

## Features Analyzed
- **Content Type Analysis:** Movies vs TV Shows  
- **Genre Popularity:** Distribution of different content categories  
- **Temporal Trends:** Content added over the years  
- **Regional Contribution:** Top countries producing Netflix content  
- **Rating Trends:** Most common ratings and audience preferences  

---

## Methodology
1. Data Cleaning & Preprocessing: Handling missing values, standardizing formats, converting dates.
2. Exploratory Data Analysis (EDA): Using Python, Pandas, Matplotlib, and Seaborn to visualize trends.
3. Insights Extraction: Identifying patterns such as genre popularity, content distribution, and regional trends.
4. Reporting: Summarizing results for strategic decision-making.

---

## Key Insights

- Movies dominate Netflix’s library, but TV Shows are growing rapidly in recent years.
- Drama, Comedy, and Thriller are the most popular genres.
- United States, India, and UK contribute the majority of Netflix content.
- Content ratings focus on TV-MA and PG-13, indicating a predominantly adult audience.
- The addition of content spikes during certain months, likely influenced by Netflix’s global release strategy.
- Tools & Libraries
- Python: Main programming language
- Jupyter Notebook: For analysis and visualization
- Pandas & NumPy: Data handling and processing
- Matplotlib & Seaborn: Data visualization
- Scikit-learn (optional): For ML-based trend predictions

## Future Enhancements

- Sentiment Analysis on user reviews to predict content reception
- Recommendation System using ML to suggest trending content
- Interactive Dashboard for real-time insights on Netflix content trends
- Predictive Analytics to forecast future popular genres or content additions

## Author

### Dhruv Tiwari
- VOIS AICTE Major Project, Oct 2025
- Email: tiwaridhruv.dh12@gmail.com
- GitHub: https://github.com/tiwaridhruv-12
