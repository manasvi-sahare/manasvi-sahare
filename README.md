# Hi there, I'm Manasvi Sahare 👋

**Mathematics & Computing @ IIIT Raichur**

*I build data-driven tools that extract insights, detect patterns, and automate decisions.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/manasvi-sahare-aab3a2336)
[![Email](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:manasvisahare25@gmail.com)
[![GitHub followers](https://img.shields.io/github/followers/manasvi-sahare?style=for-the-badge&logo=github)](https://github.com/manasvi-sahare)

---

## About Me

I'm a Mathematics and Computing student passionate about turning raw data into actionable insights. My work lives at the intersection of **data engineering**, **machine learning**, and **intelligent web applications** — I enjoy building systems that make sense of messy, real-world data.

- 🔭 Currently working on: **Explainable & calibrated ML for healthcare risk prediction**
- 🌟 Contributed a merged fix to **matplotlib**, backported to its stable release branch
- 🧮 Background in: Mathematical modeling and algorithmic thinking
- 🌱 Exploring: statistical rigor in ML (significance testing, subgroup fairness), NLP, and full-stack data apps
- 🤝 Open to: Collaborations on data/ML projects and open-source contributions
- ⚡ Fun fact: my first open-source PR review comment came from a matplotlib core maintainer

---

## 🛠️ Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

**Machine Learning & Data Science**

![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-0C7DA5?style=flat-square)
![LightGBM](https://img.shields.io/badge/LightGBM-2E8B57?style=flat-square)
![SHAP](https://img.shields.io/badge/SHAP-8A2BE2?style=flat-square)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

**Frameworks & Libraries**

![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=flat-square&logo=chart.js&logoColor=white)

**Tools & Platforms**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white)

---

## 🚀 Featured Projects

### 🩺 [Explainable & Calibrated ML for Diabetes Risk Prediction](https://github.com/manasvi-sahare/diabetes-prediction)
> Rigorously validated ML pipeline for diabetes risk classification, with statistical significance testing and a subgroup fairness audit most published work in this space skips.

| Metric | Result |
|---|---|
| Dataset | 253,680 real patient records (CDC/BRFSS) |
| Best model (raw) | LightGBM, ROC-AUC 0.8254 (statistically significant edge over RF/XGBoost, bootstrap 95% CI) |
| Calibration improvement | Brier Score cut **43%** (0.171 → 0.098) via Platt/isotonic scaling, with no loss in ranking ability |
| Explainability | SHAP values reproduced identically across independent runs (global + per-patient) |
| Fairness finding | Found and quantified real calibration gaps by Age (AUC 0.837 vs. 0.770) and Income |
| Engineering fix | Diagnosed and fixed a 441MB → 9.2MB model bloat bug via regularization |

Built with: `Python` `scikit-learn` `XGBoost` `LightGBM` `SHAP` `Jupyter`

---

### More Projects

[![Text Insight Studio](https://github-readme-stats.vercel.app/api/pin/?username=manasvi-sahare&repo=text-insight-studio&theme=tokyonight&hide_border=true)](https://github.com/manasvi-sahare/text-insight-studio)
[![Suzume Spotify Mood Analyzer](https://github-readme-stats.vercel.app/api/pin/?username=manasvi-sahare&repo=suzume-spotify-mood-analyzer&theme=tokyonight&hide_border=true)](https://github.com/manasvi-sahare/suzume-spotify-mood-analyzer)

[![Student Performance Risk Analyzer](https://github-readme-stats.vercel.app/api/pin/?username=manasvi-sahare&repo=student-performance-analyzer&theme=tokyonight&hide_border=true)](https://github.com/manasvi-sahare/student-performance-analyzer)
[![Context-Aware AI Chatbot](https://github-readme-stats.vercel.app/api/pin/?username=manasvi-sahare&repo=context-aware-ai&theme=tokyonight&hide_border=true)](https://github.com/manasvi-sahare/context-aware-ai)

| Project | What It Does |
|---|---|
| [Text Insight Studio](https://github.com/manasvi-sahare/text-insight-studio) | Automatically profiles any uploaded CSV — detects column types, generates charts and word clouds, and produces natural-language summaries with no manual configuration |
| [Suzume – Spotify Mood Analyzer](https://github.com/manasvi-sahare/suzume-spotify-mood-analyzer) | Detects a song's emotional mood in real time by combining live Spotify metadata with Genius lyrics sentiment analysis |
| [Student Performance Risk Analyzer](https://github.com/manasvi-sahare/student-performance-analyzer) | Flags at-risk students using a fully interpretable, weighted-indicator scoring model — no black-box ML |
| [Context-Aware AI Chatbot](https://github.com/manasvi-sahare/context-aware-ai) | Maintains full conversational memory across multi-turn sessions via a lightweight Python + JS architecture |

---

## 🌍 Open Source Contributions

**5 merged pull requests** across open-source projects, including a fix merged into **matplotlib** — one of the most widely-used Python libraries in the world.

| Project | Contribution | Outcome |
|---|---|---|
| **[matplotlib](https://github.com/matplotlib/matplotlib)** (23.1k ⭐) | [#31420 — Fixed a broken freetype dependency URL](https://github.com/matplotlib/matplotlib/pull/31420) | Merged by a core maintainer; **backported to the stable v3.10.x branch** and shipped in milestone v3.10.9 |
| **[TermUI](https://github.com/Karanjot786/TermUI)** | [#632 — Test suite for LogView, StatusIndicator, and Definition widgets](https://github.com/Karanjot786/TermUI/pull/632) | Merged, rated **"quality: exceptional"** by the maintainer (GSSoC 2026) |
| **[UltimateHealth](https://github.com/SB2318/UltimateHealth)** | [#1117 — Reusable glassmorphic Modal component](https://github.com/SB2318/UltimateHealth/pull/1117) | Merged — full ARIA support, focus trap, keyboard + backdrop close handling (GSSoC 2026) |
| **[statsmodels](https://github.com/statsmodels/statsmodels)** | #9766 | Merged |
| **[Themix GUI](https://github.com/themix-project/themix-gui)** (2.3k ⭐) | [#562 — "Matcha Dark Sea" GTK color theme preset](https://github.com/themix-project/themix-gui/pull/562) | Merged |

All contributions followed the standard open-source workflow: fork → feature branch → PR → maintainer review → merge.

---

## 📊 GitHub Stats

[![](https://github-readme-stats.vercel.app/api?username=manasvi-sahare&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)](https://github.com/manasvi-sahare)
[![](https://github-readme-stats.vercel.app/api/top-langs/?username=manasvi-sahare&layout=compact&theme=tokyonight&hide_border=true)](https://github.com/manasvi-sahare)

[![GitHub Streak](https://streak-stats.demolab.com/?user=manasvi-sahare&theme=tokyonight&hide_border=true)](https://git.io/streak-stats)

---

## 📬 Let's Connect

I'm always open to interesting conversations about data, ML, and building things. Feel free to reach out!

- 📧 **Email:** manasvisahare25@gmail.com
- 💼 **LinkedIn:** [manasvi-sahare](https://www.linkedin.com/in/manasvi-sahare-aab3a2336)

*"Data is the new oil — but insight is the refined fuel."*
