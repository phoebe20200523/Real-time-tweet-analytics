# Real-time-tweet-analytics
Real-time tweet analytics toolkit installed in Google Cloud
![alt text](https://github.com/phoebe20200523/Real-time-tweet-analytics/blob/main/demo.png)
1. Built a microservice architecture for real-time analytics of movie-related tweets, which has analyzed more than
`200k` tweets cumulatively.
2. Utilized tweet streamer and loader services based on `nodejs` for listening to real-time Twitter filtered stream API,
ingested tweets to `Google PubSub` topic, and pulled the tweets to `BigQuery` database.
3. Deployed the streamer and loader services to `GCP AppEngine` and configured a CRON job based on `GCP
Scheduler` for polling the tweets and triggering the loader service.
4. Visualized the trend with a `GCP Looker Studio` dashboard which connects the BigQuery via a SQL query.

![alt text](https://github.com/phoebe20200523/Real-time-tweet-analytics/blob/main/designs.png)

