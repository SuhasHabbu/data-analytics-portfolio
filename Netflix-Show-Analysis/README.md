# 🎬 Netflix Content Analysis Dashboard

An interactive data analysis dashboard built on Google Sheets, analyzing 8,800+ Netflix titles across movies and TV shows from 2015 to 2021.

---

## 🎯 Project Objective

To analyze Netflix's global content library and extract meaningful insights about content distribution, growth trends, country-wise production, and audience ratings — presented through an interactive, visually compelling dashboard.

---

## 📁 Dataset

- **Source:** [Kaggle — Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **Size:** 8,807 titles
- **Columns:** 12 (show_id, type, title, director, cast, country, date_added, release_year, rating, duration, listed_in, description)
- **Time Period:** 2008 – 2021

---

## 🔍 Key Insights

| Insight | Finding |
|---|---|
| 🎬 Content split | 69.6% Movies vs 30.4% TV Shows |
| 🌍 Top country | United States leads with 2,818 titles |
| 🇮🇳 India's position | Strong 2nd place with 972 titles |
| 📈 Peak growth year | 2019 — highest content additions (2,016 titles) |
| 🔞 Most common rating | TV-MA with 3,207 titles |
| 📉 Post-2020 decline | Content additions dropped after 2020 |

---

## 📈 Dashboard Features

- **4 Interactive Charts** — Donut, Bar, Line, and Column charts
- **KPI Cards** — Total Titles, Movies, TV Shows, Countries at a glance
- **Slicer Filter** — Filter entire dashboard by content type (Movie / TV Show)
- **Sparkline Trend** — Inline mini chart showing content growth over years
- **Netflix-themed Design** — Dark background with red (#E50914) accent colors

---

## 🛠️ Tools & Skills Used

| Tool / Skill | Purpose |
|---|---|
| Google Sheets | Primary tool for analysis and dashboard |
| COUNTIF | Counting content by type, country, rating, year |
| COUNTUNIQUE | Finding number of unique countries |
| Sparklines | Inline trend visualization |
| Pivot-style analysis | Manual aggregation using formulas |
| Slicers | Interactive dashboard filtering |
| Conditional Formatting | Visual data highlighting |
| Chart Editor | Custom styled charts with Netflix theme |

---


## 💡 What I Learned

- Cleaning and structuring raw CSV data in Google Sheets
- Using COUNTIF with wildcard `*` to search within text strings
- Building a multi-chart interactive dashboard from scratch
- Designing a professional dark-themed dashboard layout
- Deriving business insights from raw entertainment data
- Using sparklines for compact inline data visualization

---

## 🔮 Future Improvements

- Add genre-wise breakdown using listed_in column
- Include director and cast frequency analysis
- Connect to live data using Google Sheets IMPORTDATA
- Migrate to Power BI for advanced interactivity and DAX measures

---

