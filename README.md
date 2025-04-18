# 🎧 Spotify Streaming Analytics Dashboard

An interactive Power BI dashboard that analyzes Spotify listening behavior using real-world streaming data. This project focuses on uncovering user engagement patterns, trends across tracks, artists, and albums, as well as identifying high-performing content over time.

---

## 📌 Objective

To explore Spotify user streaming activity and provide actionable insights through advanced data visualization techniques and time-based trend analysis.

---

## 🧩 Dataset Overview

The dataset includes the following key fields:

- `spotify_track_uri` – Unique ID of the track
- `ts` – Timestamp when track playback stopped
- `platform` – Device or platform used (mobile, desktop, web, smart speaker)
- `ms_played` – Milliseconds a track was played
- `track_name`, `artist_name`, `album_name`
- `reason_start`, `reason_end` – Start/stop triggers
- `shuffle`, `skipped` – Playback behavior indicators

---

## 📊 Key Features

### 📅 Time Series Analysis
- Total albums, artists, and tracks played over time
- Year-over-year (YoY) growth tracking
- Weekday vs. weekend listening behavior

### 🏆 Top Content Insights
- Top 5 tracks, albums, and artists by frequency
- Quadrant analysis: high engagement vs. low popularity

### ⏱️ Listening Pattern Breakdown
- Heatmap showing peak listening hours by day and time
- Drill-downs by platform, artist, or track

### 📈 Comparative Analysis
- Latest year vs. previous year comparisons
- Dynamic filters for in-depth exploration (category, platform, time range)

### 📁 Grid View & Export
- Tabular view of key fields with drill-through support
- Export filtered data as CSV for further analysis

---

## ⚙️ Tools & Technologies

- **Power BI** – Dashboard creation and data modeling
- **Power Query** – Data transformation and enrichment
- **DAX** – Calculated columns, KPIs, and time intelligence
- **SQL** – Pre-processing and data validation

---

## 📌 Outcome

This dashboard enables users to:
- Identify streaming trends and preferences
- Discover top-performing and skipped tracks
- Optimize recommendations and playlist curation strategies
- Support business decisions with data-driven insights

---



