# mongo-dump

Dump for MongoDB with auto-upload to Google.Drive and cron. Designed for Heroku deployment.

```
ROOT_FOLDER=root folder id
CRON_DATE=* * * * * (default each day)
URL=mongo connection url
CREDS=google service account creds
```

Share the root folder with service account first.

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/wiedymi/mongo-dump)
