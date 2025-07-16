
# 🎬 Netflix Global Content Analysis (SQL + EDA + Python)
<img width="3000" height="2003" alt="image" src="https://github.com/user-attachments/assets/c32b5b0d-8a0e-4b80-a548-6be7d0aef59f" />


This project analyzes Netflix's global content dataset to uncover trends in content type, country-wise contributions, genre popularity, and yearly content growth. It combines SQL queries, Python-based EDA, and visual insights to deliver business-level recommendations.


## 🛠️ Tools & Libraries Used
- Python (Pandas, NumPy)
- SQLite (for SQL queries)
- Matplotlib & Seaborn (EDA & Visualization)
- Jupyter Notebook


## 🧹 Data Cleaning
Performed the following steps:
- Handled missing values in `director`, `cast`, `country`, `rating`
- Converted `date_added` to datetime
- Extracted `year_added` and `month_added`
- Split `duration` into numerical value and type
- Normalized `listed_in` column to extract genres


## 🔍 SQL Queries & EDA
Used both SQLite and Pandas to run SQL-style queries and explore:
- Movie vs TV Show count
- Top 10 content-producing countries
- Content release trends over years and months
- Most common genres and ratings
- Duration distribution for movies and TV shows


## 📊 Visualizations
Generated charts using Matplotlib and Seaborn:
- Bar chart: Movies vs TV Shows
- Line chart: Year-wise content additions
- Pie chart: Content type proportion
- Histogram: TV show seasons
- Bar chart: Top genres
- Monthly trend of content addition



## 📌 Key Insights & Recommendations

- 🎬 **Movies Dominate the Platform**  
  Over 70% of Netflix content consists of movies, showing Netflix’s focus on short-form storytelling. However, TV shows have grown steadily since 2018.

- 🌍 **India & US Lead Content Creation**  
  The United States contributes the most content, followed by India, indicating Netflix’s push into regional content and emerging markets.

- 📈 **Peak Content Addition in 2019**  
  The number of titles added peaked in 2019, followed by a decline—likely due to the pandemic and a strategic shift in content curation.

- 🎭 **Drama, Comedy & Documentaries Dominate Genres**  
  Drama remains the most popular genre, followed by international content and documentaries, reflecting a trend toward emotionally rich and globally diverse storytelling.

- 📅 **Holiday Season Push**  
  October and December show the highest content additions—likely aligned with viewer demand during holidays and year-end releases.

- 📏 **TV Shows Are Mostly Limited Series**  
  Most TV Shows have just 1–2 seasons, showing a preference for limited series formats or testing audience reception before long-term investment.

- 🧹 **Metadata Gaps in Director & Cast**  
  Many entries lack director or cast data, which could impact search relevance or personalized recommendations if not handled.

---
