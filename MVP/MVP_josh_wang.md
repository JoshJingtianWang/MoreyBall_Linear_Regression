# Linear Regression MVP
## Is "MoreyBall" "moneyball"?
##### Josh Wang
##### Feb 13 2022


---
### MVP Overview
**Goal**:
The former general manager of the Houston Rockets, Daryl Morey, was the first GM to apply analytics to basketball. His basketball philosophy (dubbed “Moreyball”) favors three-point field goals and lay-ups over mid-range jumpers. It is evident that “Moreyball” has swept over the league in the past five years with most teams adopting the three pointer-dominant strategy, but it is inconclusive whether “Moreyball” has contributed to team wins. With basketball being one of the biggest sports in the world, it would be important to look at if “Moreyball” is actually “money”.

**Process**:
The primary dataset has been scraped from: https://www.basketball-reference.com/

More possibly will come from: https://www.nba.com/stats/

**Preliminary visualization**:

![Pairplot](MVP_pairplot.png)
Figure 1. Pairplot of select 9 features from the scraped NBA data.


**Preliminary conclusions**:

Looking at the "Year" variable, the basketball strategy seems to have changed over the pass decade. There also seems to be co-linearity among several variables.
