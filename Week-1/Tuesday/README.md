# Week 1 - Tuesday: What Is Sports Analytics... Really?

This repository accompanies the first LinkedIn publication in the series leading up to the book **Introduction to Sports Analytics: Theory and Applications**.

The goal of this first project is simple: show what an introductory sports analytics workflow looks like using a real public dataset.

## What this repository contains

- `week1_tuesday_intro_sports_analytics_notebook.ipynb`: a Jupyter notebook that loads a public NBA dataset, creates a few descriptive metrics, and generates beginner-friendly visualizations.
- `week1_tuesday_nba_sample.csv`: a filtered season-level sample used in the notebook.
- `week1_tuesday_team_summary.csv`: a team summary table with basic descriptive statistics.

## Project objective

Sports analytics often sounds intimidating because people immediately think about advanced machine learning, tracking systems, or very complex models.

But most strong sports analytics work starts with something much more practical:

- asking a clear question,
- finding relevant data,
- cleaning and understanding that data,
- calculating useful metrics,
- and turning those numbers into insights.

That is exactly what this repository is meant to demonstrate.

## Dataset source

The notebook uses the public **FiveThirtyEight NBA Elo** dataset:

- Source repository: [FiveThirtyEight data repository](https://github.com/fivethirtyeight/data/tree/master/nba-elo)
- Data file used: [nbaallelo.csv](https://github.com/fivethirtyeight/data/blob/master/nba-elo/nbaallelo.csv)

This dataset contains historical NBA game records and Elo-related variables that make it useful for introductory descriptive analysis.

## What the notebook does

The notebook walks through a beginner-friendly workflow:

1. Load a public sports dataset.
2. Select a small group of interpretable variables.
3. Create simple derived metrics such as:
   - win indicator,
   - point differential,
   - average points scored,
   - average points allowed,
   - win rate.
4. Focus on one season for a cleaner first analysis.
5. Build descriptive visualizations.
6. Extract a few initial performance insights.

## Why this matters

This project is designed for readers, analysts, students, coaches, and sports fans who want to understand how sports analytics begins in practice.

It is not about building the most advanced model on day one.
It is about building the right foundation.

That foundation includes:

- structured thinking,
- statistical curiosity,
- reproducible workflows,
- and clear communication.

## Suggested use cases

You can use this repository to:

- follow along with the LinkedIn post,
- start your own sports analytics GitHub portfolio,
- adapt the workflow to another sport,
- reuse the notebook as a template for future projects,
- or build more advanced models on top of this first descriptive analysis.

## Recommended next steps

After reviewing this notebook, useful next projects could include:

- comparing multiple seasons,
- analyzing trends over time,
- creating team rating comparisons,
- exploring relationships between scoring and winning,
- and moving from descriptive analytics into predictive modeling.

## Running the notebook

A standard Python environment with common data-science libraries is enough.

Suggested packages:

```python
pandas
numpy
matplotlib
seaborn
```

## Author

**Carlos Hinrichsen**  
Sports analytics, data science, machine learning, optimization, and applied analytics content.
