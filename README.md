# Unofficial DeepSWE Benchmark Interactive Report

An interactive, responsive, and self-contained dashboard for exploring the DeepSWE benchmark dataset — a comprehensive dataset measuring frontier AI coding agents on real-world software engineering tasks.

🌐 **Live Dashboard:** [https://phly95.github.io/deepswe-interactive-report/](https://phly95.github.io/deepswe-interactive-report/)

---

## 📊 About the Dashboard
This dashboard compiles and visualizes **13,424 trial runs** across **19 base models** (27 distinct agent configurations) and **113 tasks** from the DeepSWE benchmark. It provides a highly detailed, interactive lens into AI capability, cost efficiency, and speed.

### Key Sections & Features:
* **Interactive Model Leaderboard**: Rank and filter agents dynamically across multiple dimensions (overall pass rates, speed, cost per successful fix, value scores).
* **Dual Token Efficiency Tracks**: 
  * **Input Token Efficiency**: Analysis of context window usage and prompt compression.
  * **Output Token Efficiency**: Analysis of reasoning verbosity and tool-call efficiency (fewer output tokens represent direct reasoning and lower costs).
* **Language Breadth & Heatmaps**: Compare success rates color-coded across Python, TypeScript, Go, Rust, and JavaScript tasks.
* **Divisive Task Index**: Identify the top 10 most "divisive" tasks in the benchmark — tasks with the highest performance spread between models, indicating where frontier capabilities diverge.
* **Detailed Model Profiles**: Deep-dives into individual configurations, highlighting specific strengths, weaknesses, best/worst tasks, and real-world execution implications.

---

## 🔍 Data Disclosures
To ensure absolute mathematical honesty and transparent analysis, the following custom adjustments have been compiled into this dataset:
* **Independent Benchmarking**: Mimo V2.5 was benchmarked independently, and its trials are integrated into the full leaderboard.
* **Pricing Tweaks**: Mimo V2.5 Pro pricing has been adjusted from the official DeepSWE benchmark values to reflect its recent permanent price drop, showing its current cost-efficiency accurately.

---

## ⚖️ Legal & Disclaimer
This is an **unofficial, independent community-driven report** created for interactive exploration of the DeepSWE trial dataset. This project is not officially affiliated with, sponsored by, or endorsed by Datacurve or the official DeepSWE benchmark team.
