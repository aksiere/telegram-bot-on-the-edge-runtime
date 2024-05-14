# stack
* [grammy](https://grammy.dev/) as a tg-bot framework
* [neon](https://neon.tech/) as a serverless database
* [cloudflare workers](https://developers.cloudflare.com/workers/) as a hosting (with endpoints and crons in one place!)

# deploy?
`npm run deploy`

# wrangler.toml
don't forget to change `[vars]` and `[triggers]` timers

# setWebhook
`https://api.telegram.org/bot<BOT_TOKEN>/setWebhook?url=<WEBHOOK_URL>&secret_token=<BOT_SECRET_TOKEN>`