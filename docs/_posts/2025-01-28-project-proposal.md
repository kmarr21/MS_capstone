---
layout: post
title: "Project Proposal"
date: 2025-01-26 13:00:00
---

## Project Proposal

For this project, I plan to develop a tennis forecasting platform that predicts pre-match odds using ATP/WTA data and extensive datasets collated by Jeff Sackman as part of TennisAbtract and the Match Charting Project[^1][^2][^3], which provide point-by-point and playstyle data. My goal is to use ensemble methods (e.g., Bayesian models as traditionally used in sports forecasting, combined with a GNN where the nodes represent players) to help predict match and tournament outcomes (pre-match; I do not plan to incorporate live scoring and changing of odds unless I have time). 

By analyzing player playstyles—such as frequency of slices, topspin, chips, approach shots, and serve patterns—and mapping point construction types, my goal is that the platform will uncover the strategies that work best against specific players. Additionally, it will identify each player's 'favorite' point constructions and vulnerabilities, enabling dynamic, matchup-specific insights. I also plan to incorporate surface preferences, historical head-to-head results, and any tournament context. 

### Sources
[^1]: [TennisAbstract](https://www.tennisabstract.com/)  
[^2]: [Match Charting Project](https://www.tennisabstract.com/charting/meta.html)  
[^3]: [Jeff Sackmann's GitHub Repository](https://github.com/JeffSackmann/tennis_MatchChartingProject)
