\# Top 14 Rugby Performance Analysis



\## Objective

Identify which collective performance metrics best explain team rankings in the Top 14 (2025-2026 season).



\## Data

\- Source: rugbydata.fr

\- Dataset: collective statistics for 14 teams (points, tries, penalties, set-piece efficiency)



\## Methodology

1\. Data cleaning and restructuring (pandas)

2\. Linear regression to identify key performance drivers (scikit-learn)

3\. Correlation heatmap to detect multicollinearity between variables (seaborn)



\## Key Findings

\- Defensive metrics (tries conceded) are the strongest predictor of final ranking

\- Funny remark that the better your shooter is, the higher your probabilty of being at the Bottom of the classement is.

\- Set-piece efficiency (lineouts, scrums) matters more than scoring volume

\- Multicollinearity between points and tries variables affects coefficient interpretation



\## Tools

Python — pandas, matplotlib, seaborn, scikit-learn

