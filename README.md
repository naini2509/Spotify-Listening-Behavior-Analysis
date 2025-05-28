**Spotify Listening Analytics Dashboard (Power BI)**
![image](https://github.com/user-attachments/assets/87ce7c82-e4c1-4030-b825-6cb535474df3)

This project delivers an interactive and insightful Power BI dashboard built to analyze Spotify listening behavior. It transforms raw track data into meaningful visualizations, uncovering trends across time, platforms, artists, and user engagement patterns.

💼 **Project Purpose**

The goal is to help stakeholders — product managers, marketers, user analysts — explore:

🎶 Listening trends over time (albums, artists, tracks)

📱 Engagement patterns across platforms (desktop, mobile, web, smart speaker)

🕒 Peak listening hours and days

⏭️ Skip, shuffle, and replay behavior

🏆 Top-performing tracks, artists, and albums


🔍 **Key Features**

✅ Time-series trends (albums, artists, tracks)

✅ LY vs. PY (Latest Year vs. Previous Year) & YoY (Year-over-Year) comparisons

✅ Weekday vs. weekend breakdowns

✅ Top 5 rankings (albums, artists, tracks)

✅ Listening heat map (hour/day patterns)

✅ Scatter plot (average listening time vs. track frequency) with quadrant insights

✅ Drill-through & drill-down details grid (album, artist, track)

✅ Exportable grid data for detailed CSV analysis


📊 **Data Fields Analyzed**

🏷️ spotify_track_uri → Unique track identifier

🕓 ts → Playback end timestamp

💻 platform → Device/platform used (desktop, mobile, web, smart speaker)

⏱️ ms_played → Milliseconds played

🎵 track_name, artist_name, album_name → Key metadata

🎬 reason_start, reason_end → Behavioral triggers

🔀 shuffle, skipped → Playback behaviors


⚙️ **Tools Used**

🖥️ Power BI Desktop

🔧 DAX measures & calculated columns

📈 Heat maps, scatter plots, time-series visuals

🔍 Drill-through & hierarchical navigation

📤 CSV export functionality


🚀 **How to Run**

1️⃣ Download and open the .pbix file in Power BI Desktop

2️⃣ Connect to the provided Spotify dataset

3️⃣ Explore the dashboard interactively using filters, slicers, drill-through

4️⃣ Export data or visuals as needed
