# Music and Typing Study
A comparative study assessing how classical background music versus silence impacts typing speed and accuracy under short and long task conditions.

## Overview
This repository contains the LaTeX source files, data, and analyses for a research project investigating the impact of background music on typing efficiency (words per minute and accuracy). The study compares classical instrumental music (e.g., Mozart’s Requiem) against a no-music control, using short (25-word) and long (100-word) tasks in the typing application MonkeyType.

## Project Organization

```
typing_performance_analysis/
├── README.md
├── .gitignore
├── data/
│   └── raw/
│       └── data.csv
├── reports/
│   └── data.csv
├── src/                  
    └── Statistical Analysis.R

```

## Analysis Outline

### Data Collection
Participants took short (25-word) and long (100-word) MonkeyType tests under two conditions:
- **Music**: Classical instrumental piece (Mozart’s *Requiem in D Minor, K.626: Lacrimosa*).
- **No Music**: Quiet environment.

### Statistical Tests
- **Two-way ANOVA** to assess main effects of music and task length on:
  1. Typing Speed (WPM)
  2. Typing Accuracy
- **Normality Checks** via Q-Q plots.
- **Homogeneity of Variance** check via Levene’s test.
- **Pearson Correlation** for WPM vs. Accuracy.

### Results
- Task length significantly influences typing speed.
- Background music showed minimal or no effect on speed/accuracy.
- Small sample size (n=16) suggests caution in generalizing.

