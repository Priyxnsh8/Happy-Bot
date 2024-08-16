# Happy-Bot -
Happy-Bot is a simple Discord bot designed to provide encouragement and inspiration to users. It also includes basic interaction features like responding to messages and fetching inspirational quotes. The bot is hosted using Flask and Replit to keep it running continuously.

# Features -

- Responds to messages with predefined encouraging words when it detects sad or negative language.
- Fetches a random inspirational quote using the `!inspire` command.
- Allows users to add new encouraging messages using the `!new` command.
- Users can delete encouragements with the `!del` command and list all stored encouragements with the `!list` command.
- The bot can be toggled on or off for responding to messages using the `!responding` command.

# Setup-

## Prerequisites-

- Python 3.8+
- Poetry (for dependency management)
- Discord Bot Token (You can obtain one from the [Discord Developer Portal](https://discord.com/developers/applications))

## Commands-
!hello: Greets the user.
!help: Provides information about the bot.
!inspire: Fetches and displays an inspirational quote.
!new [message]: Adds a new encouraging message.
!del [index]: Deletes an encouraging message at the specified index.
!list: Lists all stored encouraging messages.
!responding [true/false]: Toggles the bot's response to sad words.

## Hosting-
The bot uses a simple Flask server to stay alive. This can be particularly useful when hosting on platforms like Replit. The keep_alive.py script is responsible for this.
