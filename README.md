# telegram_meme_bot
A telegram bot that posts popular memes from different sources


# Environment variables
## Global settings

- `BOT_TOKEN` - telegram bot token
- `REDIS_URL` - redis url for caching memos
- `REDIS_CHANNEL` - redis channel for read memos
- `TELEGRAM_CHANNEL` - ID of telegram channel where bot is located

## Facebook

- `APP_Id` - Facebook application id
- `SECRET_KEY` - secret key for facebook appication.
- `REDIS_URL` - url for cache data and publish memos
- `REDIS_CHANNEL` - redis channel for publish memos
- `START_TIMEOUT_MIN` - timeout for starting application
- `REQUEST_INTERVAL_MIN` - interval for request new memos