# Environment Variables Devico

## Bot variables, **_required_**

- `DISCORD_TOKEN=your bot token
- `DISCORD_GUILD = name of your guild / server
- `log_channel = discord.utils.get(guild.channels, name="ur private channel to log") -> edit all this variable channel log name
- `messages = await message.channel.history(limit=number to max save).flatten()

## Local

These instructions are for those who want to run the bot either on their computer or on a server, for this you'll need to
have [install Python 3.6+](https://www.python.org/downloads/).

- Download the [latest release](https://github.com/dafapratama/discord) of the bot and extract it,
  you're looking for `discord-main.zip`.

- Configure Bot
  - Windows Users:
    - Edit the program and enter the appropriate values for all the variables described above [Configuration](configuration.md).
    - Add bot on your private text channel
    - Save and start running 
  - Linux/macOS Users:
    - same like Windows User

