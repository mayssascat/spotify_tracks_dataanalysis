# spotify_tracks_dataanalysis
what makes a Spotify track a hit ? is it a certain feature ? 
# 🎵 Spotify Tracks Analysis: What Makes a Hit?

&gt; *I analyzed 114,000 Spotify tracks to find the formula for a hit song. I failed — and learned something better.*

---

## 📊 The Dataset

| Detail | Info |
|---|---|
| **Source** | [Spotify Tracks Dataset](https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset) |
| **Size** | 114,000 tracks × 21 features |
| **Features** | Audio metrics (danceability, energy, valence, etc.) + metadata |

---

## 🔍 Key Findings

| # | Finding | Surprise Level |
|:---|:---|:---|
| 1 | **Most music is unpopular** — average popularity is 33/100 | 😐 Expected |
| 2 | **Explicit songs score higher** (36.5 vs 32.9) — but only because they cluster in high-engagement genres | 🤔 Interesting |
| 3 | **Danceability has ZERO correlation with popularity** (r = 0.013) | 😮 Surprising |
| 4 | **Sad songs are slightly more popular than happy ones** (valence: -0.089) | 😮 Surprising |
| 5 | **Audio features explain only 4.7% of popularity** — a machine learning model confirmed it | 🤯 Mind-blown |

---

## 🛠️ Tools & Libraries
Python 3.x
├── pandas      # Data manipulation
├── numpy       # Numerical operations
├── matplotlib  # Static visualizations
├── seaborn     # Statistical plots
└── scikit-learn # Machine learning (Linear Regression)
