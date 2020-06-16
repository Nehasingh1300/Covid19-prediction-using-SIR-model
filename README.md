# Visualization and Prediction of Covid19 cases in India

![](/images/giphy.gif)


We all are well aware of the fact that COVID-19 is affecting us to a great extent, so we have done this project, where we use COVID-19’s dataset for visualizing the impact of COVID in India and also predicting the cases for next 10 days.

So we are running a scheduled python script in zepl which receives the semi-structured data from a website then loads data to SNOWFLAKE and executes DDL and DML commands on the data for retrieving the data we need for prediction. We have sent this predicted data to Snowflake, but snowflake data is in tabular form, so we have used Power BI for visualization.

![Workflow](/static/assets/img/snow.png)

### Link of our work

**Website** : [Covid19 cases in India](https://lakshika1064.github.io/Covid19-prediction-using-SIR-model/)
#### Zepl Notebook : [Covid19](https://app.zepl.com/viewer/notebooks/bm90ZTovL3BhcmloYXJsYWtzaGlrYUBnbWFpbC5jb20vNTYwZjkxYTg2ZTk4NGFkZjhiY2Y3YzIwYTViZmIxYzQvbm90ZS5qc29u)
#### Power Bi Dashboard : [Zeplv3](https://app.powerbi.com/groups/me/reports/a1f5d962-d94e-4c18-9529-b15f5f36565b/ReportSection)

# License 

MIT
