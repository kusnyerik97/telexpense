# Telexpense Bot

Telegram bot that allows you to keep track of finances in Google Sheet. Through the bot, you can add records of expenses, income, and transactions between accounts. You can also get the amount of finances available. The bot only works with a specific Google Sheet template (read more in [Quickstart](#quickstart)). It is currently active [@telexpense_bot](https://t.me/telexpense_bot).

This code is not intended to run locally, only for demonstration purposes.

## Features

- Adding expenses and income records
- Adding records of transactions between accounts
- Getting a list of accounts and their balances

## Usage

Detailed instructions can be found in the [wiki](https://github.com/pavelmakis/telexpense/wiki). Here is only a brief summary.

### Quickstart

To use the bot you need to complete registration. If you are already registered, you will see buttons to add expenses and income. If you are not in the database, you will see the /register button. Registration is as follows:

- Copy [Google Sheet template](https://docs.google.com/spreadsheets/d/1lO9oTJu3CudibuQCCqk-s1t3DSuRNRoty4SLY5UvG_w) to your account
- Add bot service account as an editor to your sheet: telexpense-bot@telexpense-bot.iam.gserviceaccount.com
- Start the [@telexpense_bot](https://t.me/telexpense_bot) with command /start
- Tap or type /register
- Paste link to copied Google Sheet from your account to bot chat

## Sponsorship

You can support the author through the [bot](https://t.me/telexpense_bot). To do this, use the command /donate. Donated money is used to pay for hosting and functional development.



