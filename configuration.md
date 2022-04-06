# Environment Variables Devico

The main motivation for creating this project was to allow Discord Guild owners to host their own servers 
and makes it easy to collect discord digital evidence . In order to be able to do that, 
there are prerequisites that must be followed.

# Pre-Requisites

- Create a [Discord Application](https://discord.com/developers/applications).
- Create New application
- Create a [Bot](https://discord.com/developers/applications/961105613172117515/bot)

  - You'll need to have  the **App Bot Token** to configure the bot. if you already made it just ignore it.

## Bot variables, **_required_**

- `DISCORD_TOKEN=your bot token / app bot token
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

