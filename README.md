# 🎧 Spotify SQL Project

## 📌 Overview

This project focuses on data exploration and analysis of a Spotify dataset using **SQL** and **Microsoft Excel**. The dataset includes detailed information on tracks, artists, albums, audio features, and popularity metrics such as views, likes, streams, and more.

---

## 📊 Dataset Description

The dataset contains the following key columns:

- **Artist**: Name of the artist  
- **Track**: Track title  
- **Album**: Album name  
- **Album_type**: Type of album (e.g., single, album)  
- **Audio Features**: Danceability, Energy, Loudness, Speechiness, Acousticness, Instrumentalness, Liveness, Valence, Tempo  
- **Duration_min**: Track duration in minutes  
- **Popularity Metrics**: Views, Likes, Comments, Streams  
- **Licensed**, **Official_video**: Boolean values indicating licensing and video availability  
- **Most_playedon**: Platform where the song is most streamed  

---

## 🔗 Data Source

- Dataset: [Spotify Dataset on Kaggle](https://www.kaggle.com/datasets/sanjanchaudhari/spotify-dataset)

---

## 💡 SQL Queries Breakdown

### 🟢 Beginner Level
- Retrieve all columns for tracks by a specific artist  
- List distinct album types  
- Count the total number of tracks  
- Top 5 tracks with the highest views  
- Count of tracks with an official video  

### 🟡 Intermediate Level
- Average danceability score  
- Longest track by duration  
- Artist with the most tracks  
- Top 3 most liked songs  
- Top 5 albums by total streams  

### 🔴 Advanced Level
- Use `WITH` clause to calculate energy difference by album  
- Top 5 artists with highest average valence  
- Rank tracks using `RANK()` based on views  
- Platform with highest total streams  
- Categorize songs into Low, Medium, High popularity (based on streams)  

---

## 🛠 Tools & Technologies

- **Microsoft Excel**:  
  - Data cleaning  
  - Handling missing/duplicate values  
  - Formatting and structuring data  

- **MySQL**:  
  - Importing dataset from Excel  
  - Writing SQL queries (basic to advanced)  
  - Data analysis and insights extraction  

- **Microsoft PowerPoint** (Optional):  
  - Visual presentation of insights  

---

## 🧾 Requirements

- Microsoft Excel  
- MySQL or any SQL-compatible DBMS  
- (Optional) Microsoft PowerPoint  

---

## 📈 Project Highlights

- Total of **231 albums** and **54 tracks** analyzed  
- **"Feel Good Inc."** holds the highest number of views  
- Average **danceability**: ~0.645  
- Longest track: **"Master of Puppets (Remastered)"** - 8.58 minutes  
- Artist with most tracks: **Gorillaz** (10 tracks)  
- Most liked artist: **Beyoncé**  
- Most streamed songs include: *Lovely*, *Memories*, *The Eminem Show*, etc.  
- Most viewed track: **"X"** by **Nicky Jam**  
- Most popular platform: **Spotify**

---

