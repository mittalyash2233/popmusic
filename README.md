# 🇰🇷 South Korea Top 50 Playlist Analytics

### Comeback Momentum, Chart Re-Entry & Fandom Intensity Analysis

## Overview

This project analyzes South Korea's Top 50 music playlist to uncover unique K-Pop engagement dynamics such as:

* Chart Re-Entries
* Comeback Momentum
* Fandom-Driven Streaming Behavior
* Popularity Sustainability
* Content Attribute Performance
* Artist Fandom Intensity

Unlike traditional music analytics focused on chart longevity, this project investigates recurring momentum cycles that characterize the South Korean music ecosystem.

---

## Problem Statement

South Korea's music market is highly influenced by:

* Organized fandom streaming
* Comeback promotions
* Award show performances
* Viral social media trends
* Anniversary-driven engagement

Traditional chart metrics fail to capture these cyclical engagement patterns.

This project provides Atlantic Recording Corporation with momentum-centric intelligence tailored to K-Pop market behavior.

---

## Dataset

### Source

South Korea Top 50 Playlist Dataset

### Features

| Column          | Description            |
| --------------- | ---------------------- |
| date            | Playlist snapshot date |
| position        | Chart rank (1–50)      |
| song            | Song title             |
| artist          | Artist name            |
| popularity      | Popularity score       |
| duration_ms     | Song duration          |
| album_type      | Album or Single        |
| total_tracks    | Number of album tracks |
| is_explicit     | Explicit content flag  |
| album_cover_url | Album artwork URL      |

---

## Project Objectives

* Detect chart re-entry events
* Measure comeback momentum
* Analyze rank recovery behavior
* Evaluate momentum sustainability
* Compare content attributes
* Develop a fandom intensity proxy score
* Generate actionable industry insights

---

## Key Performance Indicators (KPIs)

### Re-Entry Frequency

Measures how often a song leaves and returns to the chart.

### Momentum Spike Score

Measures comeback intensity using:

Momentum Score = Rank Jump × Popularity Growth Rate

### Rank Recovery Speed

Measures how quickly songs regain chart positions.

### Post-Comeback Retention Days

Measures sustainability after a comeback.

### Rank Decay Speed

Measures how rapidly chart performance declines after a peak.

### Fandom Intensity Proxy Score

Composite metric based on:

* Re-entry frequency
* Retention duration
* Recovery efficiency
* Momentum intensity

---

## Methodology

### 1. Data Validation

* Missing value checks
* Duplicate detection
* Date validation
* Playlist consistency verification

### 2. Re-Entry Detection

Songs are classified as re-entered when:

* They disappear from the chart
* Reappear after one or more absent days

### 3. Momentum Analysis

Metrics calculated:

* Popularity Growth Rate
* Rank Jump Magnitude
* Peak Rank Achievement
* Momentum Spike Score

### 4. Sustainability Analysis

Metrics calculated:

* Retention Days
* Rank Decay Speed
* Stability Index

### 5. Content Attribute Analysis

Comparisons include:

* Single vs Album Tracks
* Explicit vs Non-Explicit Songs
* Album Size Impact
* Duration Impact

### 6. Fandom Intensity Modeling

A normalized scoring framework is used to estimate fandom-driven engagement intensity.

---

## Dashboard Features

### Overview

* Dataset statistics
* KPI cards
* Playlist health indicators

### Re-Entry Analysis

* Top re-entered songs
* Re-entry timelines
* Gap analysis

### Momentum Analysis

* Popularity growth trends
* Rank recovery charts
* Momentum spike visualizations

### Content Analysis

* Album vs Single comparison
* Explicit vs Clean content analysis
* Duration impact assessment

### Fandom Leaderboard

* Top fandom-driven songs
* Artist fandom rankings
* Intensity score leaderboard

### Report Center

* CSV export
* KPI summary export
* Executive reporting

---

## Technology Stack

### Programming Language

* Python

### Data Analysis

* Pandas
* NumPy
* Scikit-Learn

### Visualization

* Plotly
* Matplotlib
* Seaborn

### Dashboard

* Streamlit

### Exporting

* OpenPyXL
* XlsxWriter
* FPDF

---

## Project Structure

```text
SouthKorea_Momentum_Dashboard/
│
├── app.py
├── requirements.txt
│
├── data/
│   └── Atlantic_South_Korea.csv
│
├── pages/
│   ├── 1_Overview.py
│   ├── 2_ReEntry_Analysis.py
│   ├── 3_Momentum_Analysis.py
│   ├── 4_Content_Analysis.py
│   ├── 5_Fandom_Leaderboard.py
│   └── 6_Report_Center.py
│
├── utils/
│   ├── data_loader.py
│   ├── kpi_calculator.py
│   └── report_generator.py
│
└── exports/
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/SouthKorea-KPop-Momentum-Analytics.git
```

Move into the project directory:

```bash
cd SouthKorea-KPop-Momentum-Analytics
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the Streamlit dashboard:

```bash
streamlit run app.py
```

---



Submitted By:

Name:Yash Mittal

Project: South Korea Top 50 Playlist Analytics

Domain: Data Analytics

