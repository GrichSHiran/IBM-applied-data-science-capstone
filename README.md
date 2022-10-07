# First-stage Landing Outcome Predictive Model

Project files for developing classification models to predict SpaceX's first-stage booster landing outcomes as the capstone project for IBM data science specialization certification.

[Click here](https://github.com/GrichSHiran/IBM-applied-data-science-capstone/blob/main/Final%20Presentation.pdf) for the full PDF presentation

## Context
SpaceY, a new fictional player in the aerospace industry, is speculating whether it is viable for them to compete with SpaceX reusable rockets. SpaceX advertises Falcon 9 rocket launches on its website with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is because SpaceX can reuse the first stage. Therefore if we can determine if the first stage will land, we can determine the cost of a launch as well as the conditions of a successful launch. This information will be the thing that gives SpaceY the edge it needs to compete with SpaceX.

## Main Objective
The project seeks to identify the key characteristics of a successful landing and uncover the relationships among independent variables and how they affect the landing outcome.

## Methodology
- Data Collection via SpaceX API and Webscraping from HTML tables using BeautifulSoup
- Exploratory Data Analysis (EDA) with Visualization and SQL Queries
- Interactive Map with Folium
- Dashboards with Plotly Dash
- Predictive Analysis with Classification Models

## Result Summary
- Landing success rate improves over time
- Launch site with the highest success rate is KSC LC-39A
- Orbits with the highest success rate are ES-LS1, GEO, HEO, SSO
- All 4 classifiers yield the same accuracy score on test data (83.33%) with decision tree classifier scoring the highest on train data (88.92%)

