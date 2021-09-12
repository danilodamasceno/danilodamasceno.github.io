<h1> Monitoring employees with covid-19 </h1>

<a href="https://github.com/danilodamasceno/employees-covid-19" target="_blank">Github Project</a>

Project Proposal created for a company to monitor employees about COVID-19.
Two proposals were presented, one with qlik sense, and the other open source with metabase. Only the version with qlik sense was developed.

<h2> Qlik Sense Version </h2>

<center><img src="https://github.com/danilodamasceno/employees-covid-19/blob/main/images/data-flow-qs.PNG?raw=true" width="600"></center>
Data is extracted from spreadsheets and a MySQL database. Data is organized, cleansed and joined in a Qlik Sense script. The data model and business rules are defined in the Qlik Sense script. Qlik QMC is used to schedule data load. Finally, two dashboards were developed to present information.

<h3> Qlik Sense - Dashboard 1 </h3>

<center><img src="https://raw.githubusercontent.com/danilodamasceno/employees-covid-19/main/images/dashboard.PNG?raw=true" width="600"></center>
In this Dashboard we monitor: active, suspicious and recovered cases.

<h3> Qlik Sense - Dashboard 2 </h3>

<center><img src="https://github.com/danilodamasceno/employees-covid-19/blob/main/images/obras-dash-2.PNG?raw=true" width="600"></center>
In this Dashboard we carry out monthly follow-up of active and suspected cases.

<h3> Data Model </h3>

<center><img src="https://github.com/danilodamasceno/employees-covid-19/blob/main/images/qs-model.PNG?raw=true" width="600"></center>

In this project I used the star scheme created by Dr. Ralph Kimball. We use a fact table and three dimension tables. This model has low maintenance and good performance.

<h2> Open Source Version (Metabase) </h2>

<center><img src="https://github.com/danilodamasceno/employees-covid-19/blob/main/images/data-flow-mb.PNG?raw=true" width="600"></center>

The open source proposal was not developed, however it was presented. Data processing would be performed in python scripts, modeling and data storage would be performed in PostgreSQL. The automation of data loading would be done with CRON and Dashboards in the Metabase tool.











