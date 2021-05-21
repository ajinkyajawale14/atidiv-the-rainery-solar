# atidiv-the-rainery-solar

This Repo fetch solar data from the-rainery for a geolocation based on latitude	longitude

In This Use case we have taken Pune Location-

Location:- Pune
latitude:- 18.51957
longitude:- 73.85535

1) Historical Load : taking one time dump as a historical data

2) Incremental Load : fetch every day's data and append it to historical data

3) Transformation: data is present in utc timestamp hence need to convert into ist and date format furthermore

PS:- an cron based job like airflow can setup is this etl pipeline to run everyday and append data to historical data
