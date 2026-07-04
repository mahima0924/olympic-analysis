# 🏅 Olympics Data Analysis

An interactive web app that analyzes 120 years of Olympic history — from Athens 1896 to Rio 2016 — built with Python and Streamlit.

## 🔗 Live Demo
[View the app](https://olympic-analysis-9nnqeumrjryoh6k5rxcxkw.streamlit.app/)

## Features

- **Medal Tally** — Filter medal counts by year and/or country
- **Overall Analysis** — Top-level stats (editions, hosts, sports, events, nations, athletes) with trend charts over time and a sport-vs-year heatmap
- **Country-wise Analysis** — Medal tally trends and top-performing sports/athletes for any selected country
- **Athlete-wise Analysis** — Age distribution of medalists, sport-wise age trends, height vs weight comparison, and men vs women participation over the years

## Tech Stack

- **Python** — Pandas, NumPy for data processing
- **Streamlit** — Web app framework
- **Plotly** — Interactive charts
- **Matplotlib & Seaborn** — Heatmaps and static visualizations

## Dataset

Based on the [120 Years of Olympic History](https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results) dataset from Kaggle.

## Run Locally

```bash
git clone https://github.com/mahima0924/olympic-analysis.git
cd olympic-analysis
pip install -r requirements.txt
streamlit run app.py
```

## Author

Built by [Mahima Chouksey](https://github.com/mahima0924)
