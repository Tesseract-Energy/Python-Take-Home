# Python-Take-Home

Scenario: We want to create an app that shows how carbon intensive the grid is, as well as how that changes based on the forecasted wind power output.

Goal: Create a data ingestor that collates real-time wind power forecasts and grid carbon intensity within a single database. Rather than trying to get all historical data this task is focused on retrieving only new data.

<br>

Data Sources:

* Day-ahead wind power forecasts from the National Grid - [link](https://data.nationalgrideso.com/demand/day-ahead-wind-forecast/r/day_ahead_wind_forecast)
* Real-time carbon intensity from National Grid/Oxford - [link](https://carbon-intensity.github.io/api-definitions/#carbon-intensity-api-v2-0-0)

<br>

Outputs:

* Python script for ingesting and collating the data
* Database of your choice (e.g. Postgres or SQLite) containing raw data tables and a collated time-series table
* Description of how you would deploy this in production as an MVP (not focusing on scaling, just robustness of this simple pipeline)
* A forked GitHub repository showing your commits - this can be private but please add access for `AyrtonB` once you have completed the task
