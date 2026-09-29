# Spotify Data Analysis

## 📂 Dataset

The original dataset is too large to upload directly to GitHub.

You can download the base dataset from Google Drive:

**[Download the Spotify Dataset](https://drive.google.com/file/d/1YtYpHPsIPjBKDyndwibncC69_iUTfAy2/view)**

---

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on a large Spotify music dataset using Python.

The analysis focuses on understanding song popularity, audio characteristics, release trends, song duration, and genre-level patterns.

The project uses two datasets:

- `tracks.csv` – Contains information about Spotify tracks and their audio features.
- `artists.csv` – Contains information about artists, including their genres.

The datasets are analyzed together to extract useful insights about songs, artists, genres, and Spotify popularity.

---

## 🎯 Objectives

The main objectives of this analysis are:

- Explore the structure and quality of the Spotify dataset.
- Identify missing values.
- Analyze the most and least popular songs.
- Understand the distribution of Spotify audio features.
- Analyze relationships between audio characteristics.
- Study the relationship between loudness and energy.
- Study the relationship between popularity and acousticness.
- Analyze the number of songs released over different years.
- Examine changes in song duration over time.
- Analyze song duration across different genres.
- Identify popular genres from the dataset.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📊 Dataset Overview

The tracks dataset contains **586,672 records and 20 columns**.

The main columns include:

- `id` – Unique track ID
- `name` – Song name
- `popularity` – Spotify popularity score
- `duration_ms` – Song duration in milliseconds
- `explicit` – Indicates whether the track is explicit
- `artists` – Artist name
- `id_artists` – Artist ID
- `release_date` – Track release date
- `danceability` – Measure of how suitable a track is for dancing
- `energy` – Perceptual measure of intensity and activity
- `key` – Musical key
- `loudness` – Overall loudness of the track
- `mode` – Major or minor mode
- `speechiness` – Presence of spoken words
- `acousticness` – Confidence that the track is acoustic
- `instrumentalness` – Likelihood that the track contains no vocals
- `liveness` – Presence of an audience
- `valence` – Musical positivity
- `tempo` – Estimated tempo in BPM
- `time_signature` – Estimated time signature

---

## 🔍 Exploratory Data Analysis

The analysis starts by loading the datasets using Pandas.

### 1. Dataset Exploration

The first few rows of the datasets are examined to understand the structure and type of information available.

The `info()` function is also used to check:

- Number of rows
- Number of columns
- Data types
- Memory usage
- Non-null values

---

### 2. Missing Value Analysis

Missing values are checked using:

```python
pd.isnull()
