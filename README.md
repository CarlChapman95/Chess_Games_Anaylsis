# Chess Games Analysis

## Project Overview
This project analyzes a dataset of over 20,000 chess games. It demonstrates data cleaning & exploratory analysis using Python, Pandas, & matplot.

---

## Dataset
- **File:** `games.csv`
- **Source:** [Online chess game records](https://www.kaggle.com/datasets/datasnaek/chess)
- **Size:** ~20,000 games
- **Key columns:**
  - `white_rating`, `black_rating`
  - `rated`
  - `turns`
  - `winner`, `victory_status`
  - `opening_name`

---

## Tools & Libraries
- Python
- pandas
- matplotlib
- Jupyter Notebook

---

## Notes for the Analysis

### Skill Level Classification
Players were categorized based on rating
- **Beginner:** rating < 1000
- **Intermediate:** 1000 < rating < 2000
- **Advanced:** rating > 2000

Skill level columns were made for both **White** & **Black** players.

---

### Game Length Analysis
- Game length was analyzed using **number of turns**
- Graphs & Charts were made to analyze

---

### Openings Analysis
- Grouped by skill level and viewed the most popular openings
- Found that higher skill levels show more opening variety
- Found in the lower skill levels there are only a few openings that are used.

---

### Charts & Graphs
This notebook includes:
- **Histograms** showing distribuition of length of game in turns
- **Bar Charts** comparing
    - Skill Level
    - Rated vs Non-Rated games
    - Most popular openings by Skill Level
- **Scatter Plots** showing the relationship of ratings & number of turns
- **Boxplot** comparing game length across skill levels

---

## Files
- 'Chess.ipynb' - Main Jupyter Notebook
- 'games.csv' - The Dataset
- 'README.md' - Project's about

---

## Key Takeaways
- Higher-rated players tend to play longer, more complex games
- Certain openings are strongly associated with player skill
- Casual (non-rated) games are more common than rated games
 