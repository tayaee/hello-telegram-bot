# hello telegram bot
You can send messages to the bot running on your computer.

## Install Telegram
* Install Telegram app on your mobile phone

## Create a Telegram bot
* On your Telegram app, talk to `@BotFather`
* Say "/newbot"
* Enter your bot name "[Your Bot Display Name]"
* Enter username "[Your Bot Name]_bot"
* Copy the Telegram Token into your notepad.

## Configure the Telegram Token
* Create a blank file `.env` with the following content
  ```
  TELEGRAM_TOKEN=[the telegram token for your bot]
  ```

## Run the telegram bot
* On your computer, run the bot:
  ```  uv run main.py  ```

## Ask your bot to do something
* On your Telegram app, talk to @[Your Bot Name]_bot
* Your app (main.py) will receive messages.
* Add more fantastic actions to your app. Find `TODO` section.
