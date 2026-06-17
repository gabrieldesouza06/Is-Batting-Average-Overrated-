# Is Batting Average Overrated?

## Overview

This project analyzes whether batting average is still a meaningful indicator of team success in Major League Baseball. Using team-level data from the Lahman Baseball Database (2000–2024, excluding the shortened 2020 season), the study compares traditional and modern offensive statistics to regular season wins.

The goal is to evaluate how well different offensive metrics explain team success and to determine whether batting average remains relevant compared to more advanced statistics.

## Research Question

Is batting average still a useful predictor of team success, or do modern offensive metrics such as OBP, SLG, and OPS provide stronger relationships with wins?

## Data

- **Source:** Lahman Baseball Database  
- **Level:** Team-season data  
- **Time period:** 2000–2024 
- **Observations:** 750 team seasons  

The dataset includes offensive statistics such as:
- Hits (H), At-Bats (AB)
- Doubles (2B), Triples (3B), Home Runs (HR)
- Walks (BB), Strikeouts (SO)
- Sacrifice Flies (SF)
- Wins (W)

## Methods

Several offensive metrics were calculated from raw data:

- Batting Average (AVG)
- On-Base Percentage (OBP)
- Slugging Percentage (SLG)
- On-Base Plus Slugging (OPS)
- Walk Rate (BB/PA)
- Strikeout Rate (SO/PA)
- Isolated Power (ISO)

Pearson correlation coefficients were computed between each offensive statistic and regular season wins to measure the strength of linear relationships.

Additionally, scatterplots were used to visualize trends and identify outliers.

## Key Findings

- Batting average shows a relatively weak correlation with team wins.
- Slugging percentage and on-base percentage show stronger relationships with success.
- OPS has the strongest overall correlation with wins among the metrics tested.

## Conclusion

The results suggest that batting average is a limited indicator of team success compared to more modern metrics. Statistics that account for power hitting and on-base ability provide a clearer connection to winning baseball games. Overall, the findings support the shift in baseball analytics toward more comprehensive offensive measures.

## Author

Gabriel DeSouza
