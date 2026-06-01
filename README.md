# Unofficial DeepSWE Benchmark Interactive Report

This repository hosts a fully interactive, responsive, and self-contained community-driven dashboard for exploring the DeepSWE benchmark dataset.

🌐 **Live Demo:** [https://phly95.github.io/deepswe-interactive-report/](https://phly95.github.io/deepswe-interactive-report/)

---

## ⚡ Lightweight Design & Zero Footprint
Although the raw DeepSWE benchmark trials and datasets consist of **~12 GB of logs and SQLite files**, this frontend dashboard is designed to be **completely self-contained**.

* **Compiled Size:** Less than **300 KB** total!
* **No Database Required:** All computed leaderboard statistics, rankings, language breadth parameters, heatmaps, and tasks are pre-compiled and embedded directly as lightweight JS assets in [index.html](index.html).
* **No Backend Needed:** Fully executable on standard client-side browser environments. Perfect for high-speed delivery over CDNs and GitHub Pages.

---

## 🚀 How to Publish to GitHub Pages (Step-by-Step)

Publishing this repository is completely free, takes less than 2 minutes, and doesn't require any building/compiling:

1. **Create a new GitHub Repository:**
   * Go to [github.new](https://github.new) and create a repository named **`deepswe-interactive-report`**.
2. **Push the contents of this folder (`deploy/`) to your repo:**
   ```bash
   git init
   git add index.html README.md
   git commit -m "Deploy unofficial interactive DeepSWE report"
   git branch -M main
   git remote add origin https://github.com/phly95/deepswe-interactive-report.git
   git push -u origin main
   ```
3. **Enable GitHub Pages:**
   * Open your repository on GitHub.
   * Go to **Settings** $\rightarrow$ **Pages** (under "Code and automation" in the left sidebar).
   * Under **Build and deployment**, select **Deploy from a branch** as the source.
   * Under **Branch**, select **`main`** and **`/ (root)`**, then click **Save**.

Your interactive report will be live at `https://phly95.github.io/deepswe-interactive-report/` in under a minute!

---

## ⚖️ Legal & Disclaimer
This is an **unofficial, independent community-driven report** created for interactive exploration of the DeepSWE trial dataset. This project is not affiliated with, sponsored by, or endorsed by Datacurve or the official DeepSWE benchmark team. Mimo V2.5 was benchmarked independently, and Mimo V2.5 Pro pricing has been adjusted from the official benchmark values to reflect its recent permanent price drop.
