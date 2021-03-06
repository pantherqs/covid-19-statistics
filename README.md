
## Introduction
A web app uses react, material ui, echarts, and js scraper to collect and represent statistics of coronavirus in the world.
- New Hosting on AWS S3: http://covid-19-statistics.s3-website-us-west-2.amazonaws.com/
- Original Hosting on heroku: http://covid-19-statistics.herokuapp.com/

Note: 
- The hosting on AWS S3 is auto-deployed(epidemic data updates every 8 hours) by github Actions workflow script;
- The hosting on Heroku is auto-deployed(epidemic data updates every hour) by github Actions workflow script;
- The heroku site may not be accessible because it's sleeping when it's idle, just give a second visit after 2-3 minutes and it will be awaken.

## Collected Data Source (Auto-update every hour)
- https://lab.isaaclin.cn/nCoV/en
- https://en.wikipedia.org/wiki/2020_coronavirus_outbreak_in_Canada
- https://www.canada.ca/en/public-health/services/diseases/2019-novel-coronavirus-infection.html

## Screenshots
![Global Statistics](./screenshots/2.WorldStatistics.png#pic_center=960x500)
![Canada Statistics](./screenshots/3.CanadaStatistics.png#pic_center=960x500)
![China Statistics](./screenshots/1.ChinaStatistics.png#pic_center=960x500)
![News Feeds](./screenshots/4.NewsFeeds.png#pic_center=960x500)

