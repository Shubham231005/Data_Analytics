🎵 Billboard Analytics Dashboard – Power BI

A comprehensive Power BI Interactive Dashboard built to analyze Billboard music performance, rankings, and artist trends using a well-designed Star Schema Data Model. This project focuses on transforming raw data into meaningful insights through engaging visuals, filters, DAX measures, and an optimized data model.

📌 Project Overview

This project presents an analytical dashboard that highlights trends in Billboard music rankings over time.
I created:

A fully interactive Power BI Dashboard

A clean and efficient Star Schema Data Model

Custom DAX Measures for metrics

Insightful visualizations for rankings, artists, genres, and weekly performance

⭐ Key Features
✔ 1. Rank of Song (Billboard 200)

Displays the ranking of top performing songs

Highlights cumulative rank performance using bar charts

Helps identify which albums/songs dominated the charts

✔ 2. Heroes of Weeks (Tree Map)

Shows which songs held strong positions across multiple weeks

Uses color-coded treemaps for quick pattern recognition

✔ 3. Artist Performance

Pie chart showing number of artists active per year

Helps understand trends across decades and genres

✔ 4. Sum of Last Week (Gauge + Line Chart)

Gauge visualization showing total score of last week

Line chart showing how last week’s numbers changed across songs

✔ 5. Song Table (Interactive Filter)

Display list of songs with their artists

Users can select any song to filter entire report dynamically

✔ 6. Peak Position Analysis

Visual to showcase maximum chart position reached by each song

Helps detect high-performing songs instantly

🧩 Data Modelling – Star Schema
<img width="1003" height="705" alt="Screenshot 2025-11-29 132336" src="https://github.com/user-attachments/assets/fe27195f-a481-41f7-83df-ecc1da15270f" />

I created a Star Schema Model to maintain clean relationships and optimized analytics.

Dimensions (Lookup Tables):

DimSong

DimArtist

DimYear

DimGenre (if applicable)

Fact Table:

FactBillboard
Contains rank, last week score, peak position, and week-by-week performance metrics.

Benefits of Using Star Schema:

Faster query performance

Simplified relationships

Easily scalable

Optimized for DAX calculations and visualization

🛠 Technologies Used

Power BI Desktop

DAX (Data Analysis Expressions)

Power Query (ETL)

Star Schema Data Modelling

Data Visualization Techniques

📊 Dashboard Screenshot

<img width="1197" height="696" alt="image" src="https://github.com/user-attachments/assets/ed6ea52f-371e-4c56-b531-46227262f70d" />


🎯 Insights Derived

Identified which songs held top Billboard ranks consistently

Analyzed performance patterns year-wise

Understood artist dominance over various decades

Compared last-week vs overall performance trends

Highlighted songs with exceptional peak positions

🚀 How to Use

Download the .pbix file from the repository

Open it in Power BI Desktop

Explore insights using filters, tree maps, and interactive charts

📌 Future Improvements

Add genre-wise analytics

Integrate external API for automatically updated data

Include forecasting models using Power BI AI features
