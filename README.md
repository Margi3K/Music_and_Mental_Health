# Music and Mental Health

## Project Overview
This project explores how individuals perceive the effects of music on their mental health, particularly anxiety, using a cleaned survey dataset. The goal is to identify whether there's a relationship between how people experience music and their reported levels of anxiety.

## Techniques
- **EDA**: Summary statistics, histograms, value counts
- **Data Cleaning**: Filled missing values (NaNs)
- **Data Joining**: Combined music effect and mental health scores using index-based join
- **Aggregation**: Grouped by `Music effects` to calculate mean scores
- **Visualization**:  Bar plots comparing anxiety, depression, insomnia, and OCD by music effect

## Findings
- The majority of participants across all conditions (anxiety, depression, insomnia, and OCD) reported that music "improves" their mental state.
- This points to a strong self-reported belief in the therapeutic value of music for mental well-being.
- Overall, music is consistently perceived in a positive light, suggesting it plays a key role as a coping mechanism for many individuals.

## Files
- music_mental_health.ipynb — main Jupyter notebook with analysis and visuals
- mxmh_survey_results.csv — source dataset

[Kaggle Dataset — Music & Mental Health Survey Results](https://www.kaggle.com/datasets/catherinerasgaitis/mxmh-survey-results)
