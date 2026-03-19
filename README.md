# FIFA Football Player Clustering Using K-Means

This repository presents a machine learning analysis using the K-Means algorithm to group football players based on their attributes, such as skill levels, potential, wages, and age.

## Dataset
Source: [Kaggle – FIFA 22 Complete Player Dataset](https://www.kaggle.com/datasets/stefanoleone992/fifa-22-complete-player-dataset)

## Dataset Description
- Comprehensive player data from FIFA 22 with 19,000+ records and 110 variables.
- Key features analyzed: `overall`, `potential`, `wage_eur`, `value_eur`, and `age`.
- Data preprocessing includes handling missing values and feature scaling (min-max normalization).
- Clustering technique: Custom K-Means implementation from scratch.

## Clone Repository
```bash
git clone https://github.com/mragilsa/fifa-football-player-clustering.git
```

## Install Dependencies
```bash
pip install pandas numpy matplotlib seaborn scikit-learn ipython
```

## Run Notebook
```
clustering.ipynb
```

## Conclusion
This analysis demonstrates the effectiveness of the K-Means algorithm in segmenting football players into distinct clusters. By applying Principal Component Analysis (PCA) for visualization, we can observe clear groupings that represent different player profiles (e.g., high-potential youngsters vs. elite veterans). The iterative process, visualized with real-time updates, confirms that players' market value and wages are primary drivers in cluster separation.
