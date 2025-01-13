# Easy Peasy Travel Bot

Easy Peasy Travel Bot is a Telegram bot that allows you to quickly find the best hotels around the world.
The bot is developed with the help of Aiogram library and hotels.com API

## Main functionality and commands

The main function of the bot is to search for hotels according to the user's request, but the bot also provides additional functionality:
1. /lowprice - Shows the top of the cheapest hotels in the selected destination
2. /highprice - Shows the top of the most expensive hotels in the selected destination
3. /bestdeal - Shows the top offers by user request (proximity to the center, price)
4. /history - Shows search history for the user
5. /help - Displays help for bot commands.

## Installation Instructions

1. Copy the repository
2. Install dependencies from requirements.txt
3. Create an .env file; specify your bot token and hotels.com API, as well as the database connection in it (see env.template for a sample)
```python
BOT_TOKEN = “Bot token received from @BotFather”
RAPID_API_KEY = “API key from rapidapi.com/apidojo/api/hotels4/”
```
4. Run the main.py file

## Dependencies

- psycopg2-binary (2.9.5)
- python-telegram-bot-calendar (1.0.5)
- aiogram (2.23.1)
- python-dotenv (0.21.0)
- requests (2.28.1)
- peewee (3.15.4)

For a complete list of dependencies, see requirements.txt

## Contacts

**Author:** George Kovalev
**Tg:** @beerhunters
