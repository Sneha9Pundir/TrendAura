**🌸 TrendAura: Predicting the Rise & Fall of Fashion Aesthetics**

**TrendAura** is a data science project that explores how modern fashion aesthetics like _Coquette_, _Balletcore_, _Old Money_, and _Y2K_ rise and fall in popularity across different platforms, age groups, and seasons.

We collected trend data manually from Google Trends (raw .csv exports), enriched it with additional metadata like platform and age group based on social observation, social media behavior, and aesthetic archetypes, and then used machine learning to analyze and predict what makes fashion aesthetics go viral — and why.

**Key Features**

- **Self-made dataset**: Trends scraped and compiled manually for freshness and relevance.
- **Platform influence analysis**: TikTok, Instagram, Pinterest, etc.
- **Age group mapping**: Based on online cultural patterns and fashion community behaviour.
- **Seasonality detection**: Do aesthetics bloom or fade with time?
- **ML regression model**: Predict trend popularity (search score).
- **Visual storytelling**: Plots, feature importance, aesthetic evolution.

**How Platform & Age Data Was Estimated**

To keep the dataset current and Gen Z-relevant, we assigned platform and age group values **manually** by researching:

- Which platforms each trend is most commonly seen on?
- The target audience and age demographics engaging with the trend.
- Aesthetic communities on TikTok, Pinterest, and Instagram.

Although not sourced from an academic dataset, this approach reflects real-world, social behaviour analysis and mirrors the way trends organically spread in modern digital culture.

**Insights Gained**

- **Age group 16–22** is the most dominant trend-driving demographic.
- **TikTok** and **Instagram** are the most trend-amplifying platforms.
- Aesthetics like _Coquette_ and _Balletcore_ peak in **spring and early summer.**
- Y2K and Grunge show recurring interest spikes (seasonless appeal).
- Trends associated with softness, luxury, and femininity tend to have higher average search scores.

**Dataset Overview**

| **Month** |     |     |     | **Aesthetic** |     | **Trending Keyword** | **Search Score** | **Dominant Color** | **Description** | **Age Group** | **Platform** |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Jan 2023 |     |     |     | Coquette |     | "coquette outfit" | 88  | #f6dbe3 | Pale pink, bows, laces, femininity | 16–22 | TikTok |
| Mar 2024 |     |     |     | Grunge |     | "grunge streetwear" | 71  | #2b2b2b | Dark tones, ripped layers | 18–28 | Instagram |
| May 2023 |     |     |     | Balletcore |     | "ballet flats" | 76  | #f2e8e0 | Delicate, airy, ballet-inspired | 14–21 | Pinterest |

**Model Results**

- **Model Used**: Random Forest Regressor
- **Features**: Aesthetic, Platform, Age Group, Month (as number)
- **Target**: Search Score
- **R² Score**: 0.29

**Top Influential Factors**

1. Platform
2. Month (seasonal effect)
3. Aesthetic

**Tools Used**

- Python (Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn)
- Google Colab
- Google Trends CSV data (manually curated)

**Folder Structure**

TrendAura-Project/

├── TrendingAura01_notebook.ipynb

├── clean_data.csv

├── README.md

**Author**

Made with data, design & interest by **Sneha**✨
