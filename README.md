# 🎵 Spotify & YouTube Data Analysis (EDA)

This project provides a comprehensive **Exploratory Data Analysis (EDA)** on a dataset combining metrics from the world's leading music and video platforms: **Spotify** and **YouTube**.

## 🎯 Project Objectives
The primary goal is to analyze the correlation between streaming numbers, views, likes, and comments to understand audience engagement patterns. The study also identifies top-performing artists, tracks, and the distribution of various album types.

## 🚀 Key Analysis Features
- **Data Cleaning & Preprocessing:** Handling missing values and removing redundant columns (URLs, URIs) to ensure data integrity.
- **Artist Performance:** Identifying the top 10 artists based on total YouTube views (e.g., Ed Sheeran, CoComelon).
- **Streaming Trends:** Finding the most and least streamed tracks on Spotify, featuring hits like "Blinding Lights" and "Shape of You".
- **Album Analysis:** Visualizing the market share of different release types (Albums, Singles, Compilations) using pie charts.
- **Engagement Metrics:** Calculating Like-to-View ratios to measure how effectively content connects with its audience.
- **Correlation Mapping:** Using Heatmaps to visualize the relationships between Views, Likes, Comments, and Streams.

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** - `Pandas` & `NumPy`: For efficient data manipulation and aggregation.
  - `Matplotlib` & `Seaborn`: For advanced data visualization and heatmap generation.

## 📊 Key Findings
* **T-Series dominance:** The T-Series channel leads significantly in total YouTube views.
* **Engagement vs. Popularity:** High view counts do not always correlate linearly with high like ratios; specific singles often show more "loyal" engagement.
* **Format Popularity:** Standard "Album" releases make up the vast majority (over 70%) of the dataset compared to singles and compilations.

## 📁 File Structure
- `Spotify-Youtube-Analysis.ipynb`: The Jupyter Notebook containing all cleaning, analysis, and visualization code.
- `Spotify_Youtube_Dataset.csv`: The raw dataset used for this project.

## 🏁 How to Run
1. Clone this repository.
2. Install dependencies: `pip install pandas matplotlib seaborn numpy`.
3. Open the Jupyter Notebook and run all cells sequentially.

---
*This project was developed to showcase data science and analytical storytelling skills.*
