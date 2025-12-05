# CHAD-HATTER Bot

A Telegram bot for the BWIF (BaseWifHat) cryptocurrency community on the Base blockchain.

## Features

- **`/hatcheck`** - Get live stats including price, market cap, holder count, and progress milestones
- **`/raid <tweet_link>`** - Rally community for engagement on specific tweets
- **`/shill`** - Get the daily promotional message
- **Automated Tweet Monitoring** - Automatically posts new tweets from @basewifhat

## Setup

### Prerequisites

- Python 3.8+
- Telegram Bot Token (from [@BotFather](https://t.me/BotFather))
- Twitter/X API Bearer Token
- BaseScan API Key

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/BasedNUKEM/CHAD-HATTER.git
   cd CHAD-HATTER
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Set environment variables:
   ```bash
   export TELEGRAM_TOKEN='your_telegram_bot_token'
   export TWITTER_BEARER_TOKEN='your_twitter_bearer_token'
   export BASESCAN_API_KEY='your_basescan_api_key'
   export TELEGRAM_CHAT_ID='-1001234567890'  # Your group chat ID
   ```

4. Run the bot:
   ```bash
   python chadhatterbot.py
   ```

## Configuration

The following environment variables can be configured:

| Variable | Description | Required |
|----------|-------------|----------|
| `TELEGRAM_TOKEN` | Telegram Bot API token | Yes |
| `TWITTER_BEARER_TOKEN` | Twitter/X API Bearer token | Yes |
| `BASESCAN_API_KEY` | BaseScan API key for holder data | Yes |
| `TELEGRAM_CHAT_ID` | Telegram group chat ID | Yes |

## License

MIT License