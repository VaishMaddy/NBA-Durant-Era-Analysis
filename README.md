# Durant Career Impact: NBA Play-by-Play Analysis

This project investigates how Kevin Durant’s transition from the Oklahoma City Thunder (OKC) to the Golden State Warriors (GSW) impacted individual scoring style, teammate roles, and team-level offensive strategy. Using NBA play-by-play data from 2013 to 2024, it breaks down player and team behavior across Durant’s career eras.

---

## Project Overview

- End-to-end play-by-play analysis covering 11 NBA seasons (2013–2024)
- Focused on shifts in shot selection, efficiency, and playmaking pre- and post-Durant’s move
- Includes clutch-time analysis, on/off-court splits, and playoff performance comparison
- Conducted entirely in Python using Google Colab

---

## Objectives

- Quantify Durant’s evolution from isolation scorer (OKC) to system-based shooter (GSW)
- Analyze how teammates (Westbrook, Curry, Klay, Draymond) adjusted roles and efficiency
- Compare OKC and GSW team shot profiles with and without Durant
- Track changes in GSW playoff metrics post-Durant
- Visualize key metrics such as shot distance, assisted rates, and clutch-time contributions

---

## Notebooks

| File Name | Description |
|-----------|-------------|
| **01_preprocessing_and_era_segmentation.ipynb** | Loads and cleans NBA play-by-play logs. Segments data into Pre-GSW, GSW, and Post-GSW eras based on Durant's career moves. Optimizes memory for large-scale filtering and transformation. |
| **02_durant_gsw_impact_analysis.ipynb** | Unified analysis notebook. Covers GSW assist structure, Durant’s shot profile shift, Curry’s influence, teammate adaptations, team-level changes, and playoff impact. Includes KDEs, bar charts, on/off comparisons, and contextual insights. |

---

## Tools & Technologies

- **Python** (Google Colab)
- `pandas` – Data wrangling & transformation
- `numpy` – Numerical operations
- `matplotlib`, `seaborn` – Visualization
- KDE plots, bar charts, density curves – Visual analysis of shot patterns and usage

---

## Key Analyses Performed

- **Durant’s Shot Profile Evolution** (OKC vs. GSW): Zone-level breakdown, assisted vs. self-created shot ratios
- **Curry-On vs. Curry-Off Impact**: KDEs of Durant’s shot distances
- **Teammate Adaptation**: Changes in usage, assist shares, and efficiency for Westbrook, Curry, Thompson, Green
- **Clutch Time Performance**: Top shot takers in final 5 minutes of close games
- **GSW Playoff Improvement**: Win%, FG%, clutch metrics before and after Durant
- **On/Off Court Shot Volume**: Shot frequency and play pacing with vs. without Durant

---

## Visual Outputs

The notebook includes:

- KDE plots of shot distances (with/without Curry)
- Bar charts comparing zone distributions and assisted shot %
- Player-level assist rankings and clutch shot volume
- Team-level playoff performance deltas
- Shot frequency timelines by Durant’s on-court presence

---

## Key Takeaways

- Durant’s FG% improved from **49.3% (OKC)** to **52.2% (GSW)**, alongside an increase in assisted shot rate.
- Westbrook relied on heavy self-creation, while Curry and Thompson enabled off-ball synergy in GSW.
- GSW’s offensive balance and spacing helped Durant become more efficient with reduced volume.
- The Warriors’ **Win % in playoffs** rose **+11.4 percentage points** with Durant on the roster.
- Durant’s presence drove a measurable increase in **shot pacing and shot density** per minute.

---

## About

This case study showcases how a superstar’s career move can reshape team dynamics, play style, and collective efficiency. Designed as a deep-dive using granular NBA possession data, it reflects real-world sports analytics techniques for player evaluation and strategic insights.

---

## License

This project is intended for academic and personal analysis use. Please attribute if reusing code, charts, or derived insights.
