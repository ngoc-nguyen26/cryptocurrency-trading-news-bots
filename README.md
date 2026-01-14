# Cryptocurrency Trading News Monitor

Monitors Threads profiles for new posts and sends notifications via Apprise (Discord, Slack, Telegram, etc.).

## Quick Start

1. Install: `pip install twikit playwright parsel jmespath nested-lookup apprise schedule pyyaml && playwright install chromium`
2. Configure: Copy `config/*.cfg` to `config/*.yaml` and fill in settings
3. Run: `python -m news_trade`

## Config

- `config/config_remote.yaml`: Threads usernames to monitor and SLA time window
- `config/apprise.yaml`: Notification channel URLs (Discord, Telegram, etc.)

