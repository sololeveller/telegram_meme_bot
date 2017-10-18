# Telegram Meme Bot
Telegram bot that posts popular memes from different sources.

![A _whole lot_ of memes.](http://i0.kym-cdn.com/photos/images/facebook/000/862/065/0e9.jpg)


# Environment variables
## Global settings
- `BOT_TOKEN` - Telegram bot token
- `REDIS_URL` - Redis instance URL 
- `REDIS_CHANNEL` - Redis channel to post messages to
- `TELEGRAM_CHANNEL` - Telegram channel ID to post memes to 

## Facebook
- `APP_ID` - Facebook application id
- `SECRET_KEY` - secret key for Facebook appication
- `REDIS_URL` - Redis instance URL
- `REDIS_CHANNEL` - Redis channel to post messages to
- `REQUEST_INTERVAL_MIN` - API polling interval
- `START_TIMEOUT_MIN` - Worker start timeout 

## Twitter
- `TWITTER_CONSUMER_KEY` - Twitter consumer key, can be obtained [here](https://apps.twitter.com)
- `TWITTER_CONSUMER_SECRET` - Twitter consumer secret, can be obtained [here](https://apps.twitter.com)
- `TWITTER_ACCESS_TOKEN_KEY` - Twitter access token key, can be obtained [here](https://apps.twitter.com)
- `TWITTER_ACCESS_TOKEN_SECRET` - Twitter access token secret, can be obtained [here](https://apps.twitter.com)
- `REDIS_URL` - Redis instance URL
- `REDIS_CHANNEL` - Redis channel to post messages to
- `REQUEST_INTERVAL_MIN` - API polling interval
- `START_TIMEOUT_MIN` - Worker start timeout

## Reddit

- `REDDIT_AGENT` - Reddit app name&version
- `REDDIT_CLIENT` - Reddit app id
- `REDDIT_SECRET`- Reddit app secret token
- `REDDIT_USER` - Your r/username
- `REDIS_URL` - Redis instance URL 
- `REDIS_CHANNEL` - Redis channel to post messages to
- `REQUEST_INTERVAL_MIN` - API polling interval
- `START_TIMEOUT_MIN` - Worker start timeout 