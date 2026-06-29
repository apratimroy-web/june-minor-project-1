# june-minor-project-1
# GroupDNA: WhatsApp Chat Analytics 📊

> **"Spotify Wrapped, but for your friend group."**

GroupDNA is a constraint-driven WhatsApp chat analytics tool built to decode friend group dynamics, tracking metrics like messaging frequencies, peak activity periods, word popularity, response latencies, and behavioral archetypes.

This project was built from scratch as part of **The Unlox Academy Industry-Graded Minor Project**.

---

## 🚀 Key Features

* **Feature 1: Robust Chat Parser** — Seamlessly processes multi-line continuations, system alerts, media omissions (`<Media omitted>`), and deleted messages footprints.
* **Feature 2 & 3: Group Statistics** — Computes total message counts per user and pinpoints the group's single absolute busiest day and peak hour.
* **Feature 4: Activity Heatmap Matrix** — Leverages a dense **NumPy 2D matrix** mapping each user's hourly footprint into a customized ASCII shade density grid.
* **Feature 5: Text Mining & Word Cloud** — Filters terminal punctuation and baseline stop words to extract the top 5 most frequently used words.
* **Feature 6: Response Latencies & Silent Streaks** — Tracks operational response time lags between alternating senders and uncovers consecutive daily silent streaks.
* **Feature 7: Quantitative Personality Profiler** — Passes data profiles through a deterministic rule-based matrix to tag members with unique archetypes (e.g., *The Spammer*, *The Night Owl*, *The Storyteller*, *The Drama Queen*, *The Ghost*).
* **Feature 8: Terminal Report UI** — Renders a beautifully aligned, screenshot-ready ASCII dashboard for clean diagnostic visualization.

---

## 🛠️ The Challenge: Built Under Hard Technical Constraints

To demonstrate absolute mastery over baseline Python data structures and low-level algorithms, this entire implementation was engineered under strict production rules:
* 🚫 **NO Pandas** (Data alignment and parsing handled via standard lists, dicts, and tuple sorting mechanisms)
* 🚫 **NO Matplotlib/Seaborn** (Visualizations engineered entirely via text-based ASCII bar graphs and density maps)
* 🚫 **NO Collections Module** (Frequency tracking mapped manually)
* 🚫 **NO Regular Expressions (re)** (All timestamp and string Extractions written with standard indexing loops and state conditions)
* ⚡ **NumPy Matrix Engine** (Utilized multidimensional array allocations for multi-user hourly aggregation grids)

---

## 📂 Project Structure

```text
├── Data Science Data Analytics June Minor Project 1/
│   ├── GroupDNA_Minor_Project_Brief.pdf  # Project specifications and rules
│   └── hostel_bois.txt                   # Synthetic WhatsApp chat dataset
├── GroupDNA_Analytics_Notebook.ipynb    # Monolithic Google Colab Source Code
└── README.md                             # Repository documentation
