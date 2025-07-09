# Telegram Phone Bot

A Telegram bot that verifies Brazilian phone numbers using the NumVerify API.

## Features

- Validates phone numbers with country code
- Returns country, location, carrier, and line type

## Usage

1. Set environment variables:
    - `BOT_TOKEN`: Your Telegram bot token
    - `NUMVERIFY_API_KEY`: Your NumVerify API key

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the bot:
    ```bash
    bash start.sh
    ```

4. In Telegram, start a chat and use:
    - `/start` — for instructions
    - `/consulta +5511987654321` — to check a number

## License

MIT