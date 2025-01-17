# Divisons of Wealth: Analyzing Human Perception in Relation to Economic Status

## Introduction
This is a 10-week independent research project on wealth and the perception of friendliness at Dartmouth College. 
The authors of this project are Love Tsai and Angela Zhang. Julia Huebner and Kellen Kinsella were involved in the inital stages.
This project was done for QSS15, a statistics class in R taught by Professor Michael C. Herron in 19F.

## Motivation
At Dartmouth College, 69% of students come from the highest-earning 20% of American households. Dartmouth provides a unique opportunity to analyze the perception of wealth within a community, as socioeconomic status among the student body is much higher than the national average. It’s interesting to investigate how perception of socioeconomic status correlates with perceived character traits, such as friendliness.

## Findings
There is a statistically significant yet minor difference between perception of friendliness for wealthier-appearing peers than their counterparts. Specifically, non-wealthy appearing students are rated more friendly and collaborative than their wealthy counterparts (xbarAcollab = 7.6*, xbarBcollab = 7.06; xbarAfriend = 6.77, xbarBfriend = 6.61). Refer to ResearchPaper.pdf Section IV for more details.

## Tools and Skills Used
- R and RStudio for the research paper and its graphs, charts, contents, etc.
- Qualtrics and Qualtrics Survey Technologies for the creation of the survey
- Statistics Concepts Employed:
   - Chi Squared Tests & Residuals
   - Null Hypotheses
   - Goodness-of-fit Test for Randomization
   - Confidence Intervals

## ProjectProposal.pdf
Our project proposal before our study began. Shows our thinking and motivation for pursuing the topic of choice.

## SurveyVideos Folder
This folder includes the two videos used for our survey.
QSS Vid A is our control, and QSS Vid B is the experiment (wealthier-appearing counterpart video).

## SurveyData Folder
The data from our Qualtrics Surveys in CSV form. Includes the following:
- DataSetA.csv: the uncleaned data from Survey A.
- DataSetB.csv: the uncleaned data from Survey B
- ACleaned.csv: cleaned data from DataSetA.csv used for our R models and significance test calculations.
- BCleaned.csv: cleaned data from DataSetB.csv used for our R models and significance test calculations.
Note: the cleaned data removed erroneous / faulty data entries, including unfinished survey entries.

## ResearchPaper.pdf
The research paper, made with R, is broken up into 4 components:
1. Introduction
2. Design
3. Data Analysis
4. Conclusions: Analysis of Results and Potential Confounds

## Final Notes
For any questions regarding the research, please email zz2921@columbia.edu.
