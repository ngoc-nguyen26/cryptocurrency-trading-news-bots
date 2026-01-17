# Social Trading News Crawler Bot

This bot is designed to collect and organizes news related to social trading platforms, financial markets and investment strategies. It monitors multiple online sources and delivers a single, structured stream of relevant updates.

## Features

* **Real-time crawler:** Actively crawls news websites, blogs, forums, and social media platforms such as [Threads](https://www.threads.com/), [Twitter](https://x.com/home)
* **Real-time notify:** Will auto notify into telegram after crawls news.

## Getting Started

- **Clone this repo**:  https://github.com/ngoc-nguyen26/cryptocurrency-trading-news
- Add file config
    - Setup bot telegram and then create new file apprise.yaml and add url telegram ```tgram://{bot_token}/{chat_id}}?format=html&mdv=v2```, more detail you can check [here](https://github.com/caronc/apprise/wiki/Notify_telegram).
    - Create new file config_remote.yaml and fill some fields related to Twitter, Threads.
- Install all dependencies ```pip3 install -r requirements.txt```
- Run code ```python3 -m news_trade```

## Disclaimer

This bot collects publicly available information. The developers **ARE NOT RESPONSIBLE FOR** the accuracy or completeness of the information collected. 

Users should always conduct their own independent research and due diligence before making any investment decisions. The information provided by this bot should not be considered financial advice.

## Contributing


## License (If Applicable)

*(This section would specify the license under which the bot is distributed.)*