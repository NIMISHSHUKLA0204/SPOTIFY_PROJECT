# SPOTFY_PROJECT with SQL
## Overview
This repository contains SQL queries and data analysis for a music dataset. The dataset includes details about tracks, artists, albums, and popularity metrics such as views, likes, streams, and various audio features.
## Dataset
The dataset consists of the following key columns:
•	Artist: Name of the artist
•	Track: Track title
•	Album: Album name
•	Album_type: Type of album (e.g., single, album)
•	Danceability, Energy, Loudness, Speechiness, Acousticness, Instrumentalness, Liveness, Valence, Tempo: Audio features
•	Duration_min: Duration of the track in minutes
•	Views, Likes, Comments, Stream: Popularity metrics
•	Licensed, official_video: Boolean values indicating licensing and official video availability
•	most_playedon: The platform where the song is most played
## DATA SOURCE 
Data source used for this project was taken from Kaggle :[spotify] (https://www.kaggle.com/datasets/sanjanchaudhari/spotify-dataset)
## SQL Queries
The repository includes SQL queries categorized by difficulty level:
Beginner
1.	Retrieve all columns for tracks by a specific artist.
2.	List distinct album types in the dataset.
3.	Count the total number of tracks.
4.	Get the top 5 tracks with the highest views.
5.	Count the number of tracks with an official video.
Intermediate
6.	Calculate the average danceability score.
7.	Find the longest track by duration.
8.	Identify the artist with the most tracks.
9.	Retrieve the top 3 most liked songs.
10.	List the top 5 albums with the highest total streams.
Advanced
11.	Use a with clause to calculate the difference between the highest and the lowest energy value for tracks in each album.
12.	Find the top 5 artists with the highest average valence.
13.	Rank tracks based on views using the RANK() function.
14.	Identify the platform with the highest total streams.
15.	Categorize songs into Low, Medium, and High popularity based on streams.
## Tools and Techniques
Microsoft Excel:
. Data cleaning and formatting.
. Removing duplicate values and null values.
. Arranging cleaned and ordered data.
MySQL:
. Transforming data from excel into MySQL and make required changes .
. Gaining insights and data exploration . 
. Using various aggregations , filters ,  basic queries and complex queries .

## Requirements
•	Microsoft Excel
•	MySQL or any compatible SQL database
•	Microsoft Power Point 
## Conclusion
. There are 231 distinct album with total 54 tracks.
. The Feel Good Inc. the track with highest number of views.
. The Average Danceability for all tracks is 0.645 approx.
. Longest track by duration minute is master of puppets(Remastered) with 8.58 minute.
. The artist with most tracks is Gorillaz with 10 tracks and artist with most likes is Beyonca.
. The most streamed songs are lovely , memories , The Eminem Show , etc.
. The track with most views is X and the artist is Nicky Jam.
. The most loved and played platform is Spotify.

