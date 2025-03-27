# Music and Mental Health

This project explores how individuals perceive the effects of music on their mental health — particularly anxiety — using a cleaned survey dataset. The goal is to identify whether there’s a correlation between music perception and reported anxiety levels.

## Techniques
- **EDA**: Summary statistics, histograms, value counts
- **Data Cleaning**: Filled missing values (NaNs)
- **Data Joining**: Combined music effect and mental health scores using index-based join
- **Aggregation**: Grouped by `Music effects` to calculate mean scores
- **Visualization**:  Bar plots comparing anxiety, depression, insomnia, and OCD by music effect

## Findings
- Most participants across all conditions (Anxiety, Depression, Insomnia, OCD) reported that music "Improves" their mental state.
- This suggests a strong self-reported belief in the therapeutic value of music on mental health.
- The perception of music's effect is consistently positive, which may be linked to its role as a common coping tool.

## Files
music_mental_health.ipynb — main Jupyter notebook with analysis and visuals
mxmh_survey_results.csv — source dataset

[Kaggle Dataset — Music & Mental Health Survey Results](https://www.kaggle.com/datasets/catherinerasgaitis/mxmh-survey-results)

