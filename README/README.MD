# 🏀 **NBA Stats Web Scraper & Player Clustering Analysis**

# 📌 **Project Overview**

This project analyzes NBA player statistics over three seasons (2021-2024) using Python. Our goal was to identify performance trends and categorize players into meaningful groups using machine learning techniques. We sourced data from Kaggle and applied clustering methods to classify players into offensive superstars, balanced role players, and defensive specialists.

# 👥 **Team Members**:

Irfan Rathore

Mahmoud Alkayat

Md Rapu

Mithil Patel

Husain Attarwala

# 📊 **Data Sources**

We utilized three datasets from Kaggle, each containing NBA player statistics for the following seasons:

- 2021-2022 NBA Season

- 2022-2023 NBA Season

- 2023-2024 NBA Season

Each dataset includes comprehensive player statistics such as:

- Player Information: Name, Team, Age, Position

- Performance Metrics: Games Played, Games Started, Minutes Per Game

- Scoring & Efficiency: Field Goals (FG), Attempts (FGA), Points Per Game (PTS)

- Other Stats: Rebounds (TRB), Assists (AST), Blocks (BLK), Steals (STL)

🛠 Technologies Used

- Programming Language: Python

- Data Processing & Analysis: pandas, numpy

- Visualization: matplotlib, seaborn, plotly

- Machine Learning: scikit-learn (for K-Means clustering & PCA)

- Notebook Environment: Google Colab / Jupyter Notebook

# 🚀 **Project Workflow**

# 1️⃣ Data Extraction & Cleaning

Downloaded datasets from Kaggle and loaded them into Google Colab.

Cleaned missing values and formatted the data for analysis.

# 2️⃣ Statistical Analysis

Explored player performance trends across three seasons.

Visualized key metrics (PTS, AST, TRB, STL, BLK) using histograms, box plots, and pair plots.

# 3️⃣ K-Means Clustering

Applied Elbow Method to determine the optimal number of clusters.

Chose 3 clusters for K-Means clustering:

- Cluster 0: Offensive Superstars (high PTS, FG%)

- Cluster 1: Balanced Role Players (moderate in all metrics)

- Cluster 2: Defensive Specialists (high TRB, STL, BLK, low PTS)

Assigned players to clusters based on their performance metrics.

# 4️⃣ Principal Component Analysis (PCA)

Reduced dimensionality for better visualization.

Displayed clusters in a 2D PCA plot to show separation.

# 5️⃣ Insights & Real-World Applications

- Team Building: Coaches can strategize based on player clusters.

- Scouting & Recruiting: Identifying ideal players for trades and drafts.

- Performance Trends: Understanding how different player types evolve over seasons.

# 📀 Key Findings

- Cluster 0 (Offensive Superstars): Players consistently score the highest points but contribute less defensively.

- Cluster 1 (Role Players): Balanced performers who make steady contributions in both offensive and defensive metrics.

- Cluster 2 (Defensive Specialists): Players who excel in rebounds, steals, and blocks but have lower scoring outputs.

- Clustering results help in player comparisons, team composition, and game strategy planning.

# 📈 Visualizations

- Elbow Method Plot: Determines the optimal K for clustering.

- Pair Plots: Shows feature relationships and cluster separations.

- PCA Scatter Plot: Displays clusters in a reduced-dimensional space.

- Seasonal Performance Trends: Line charts showcasing metric variations across three NBA seasons.

# 🏁 Conclusion

This project demonstrates the power of data-driven analysis in sports. By applying machine learning techniques like K-Means clustering, we uncovered valuable insights into NBA player performance. These insights can aid team management, player scouting, and advanced sports analytics.

# 🔥 Future Enhancements

Expand the dataset to include advanced NBA metrics (PER, Usage Rate, Win Shares).

Implement hierarchical clustering for a deeper player segmentation.

Build an interactive dashboard for real-time data exploration.

# 💻 How to Run the Project

Clone this repository:

git clone https://github.com/Nba-Statistical-Analysis/NBA-Statistical-Analysis.git
cd NBA-Statistical-Analysis

# Install dependencies:

pip install pandas numpy matplotlib seaborn scikit-learn

# Run the Jupyter Notebook:

jupyter notebook NBA_STAT_ANALYSIS.ipynb

View the clustering results and visualizations.

## 📄 Project Presentation

For an overview of our findings, check out our final project presentation

💎 Contact

For any inquiries or collaboration opportunities, feel free to reach out to Irfan Rathore at [irfanarathore@gmail.com].