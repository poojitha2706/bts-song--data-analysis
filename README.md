# 🎵 BTS: A Data-Driven Story of Global Domination

> *"How did a K-pop group from South Korea become the biggest band in the world? The answer is hidden in the data."*

---

## 📌 Project Overview

This project analyzes BTS's full discography using Spotify audio features to uncover how their sound evolved over 12 years, what changed when they went global, and what the data reveals about their formula for success.

Submitted as part of the **Codédex Data Science / Data Analysis Monthly Challenge** — *"Use data to tell a story about something you love."*

---

## ❓ Questions Explored

- How did BTS's sound (energy, mood, danceability) evolve from 2013 to 2025?
- Did their English-language releases sound measurably different from their Korean tracks?
- Does each BTS era have a distinct sonic fingerprint?
- Which albums were the most energetic, happiest, or most acoustic?

---

## 💡 Key Findings (Aha Moments)

### 🔍 More Famous = Sadder Music?
BTS's happiness score (valence) hit its **lowest point in 2018–2019** — the exact years they were breaking world records. Their emotional vulnerability, not their cheerfulness, is what made them global superstars.

### 🔍 English Songs Are a Different Product
English tracks score significantly higher in danceability and valence than Korean ones. BTS ran **two parallel sonic identities** simultaneously — deep emotional music for core fans, and bright radio-friendly hits for Western charts.

### 🔍 Their Core Sound Never Changed
Despite going global, their energy and danceability stayed consistent across all eras. BTS didn't reinvent themselves — they **brought the world to them instead.**

---

## 📊 Visualizations

| Chart | Description |
|---|---|
| 📈 Line Chart | How BTS's energy, valence & danceability evolved year by year (2013–2025) |
| 🌍 Bar Chart | Korean vs English songs — audio feature comparison |
| 🕸️ Radar Chart | Sound profile across 4 BTS eras |
| 🔥 Heatmap | Mood & energy breakdown across 15 major albums |

---

## 🗂️ Dataset

- **Source:** Kaggle — BTS Spotify Dataset
- **Size:** 421 tracks across 54 albums (2013–2025)
- **Features used:** `energy`, `valence`, `danceability`, `acousticness`, `liveness`, `speechiness`, `tempo`, `language`, `album`, `release_date`

---

## 🛠️ Tools Used

- **Google Colab** — coding environment
- **Python** — data analysis
- **Pandas** — data cleaning & manipulation
- **Plotly** — interactive visualizations
- **Google Sheets** — initial data exploration

---

## 🚀 How to Run

1. Clone this repository
```bash
git clone https://github.com/poojitha2706/bts-song-data-analysis
```
2. Open `BTS_Analysis.ipynb` in [Google Colab](https://colab.research.google.com)
3. Upload `bts.csv` when prompted
4. Run all cells in order

---

## 📁 File Structure

```
bts-data-analysis/
│
├── BTS_Analysis.ipynb   # Main notebook with all analysis & visualizations
├── bts.csv              # Dataset (BTS full discography with Spotify features)
└── README.md            # You are here!
```

---

## 👤 Author

Made with 💜 for the Codédex Monthly Challenge  
*Topic: Music — What does data reveal about BTS's global rise?*
