## Requirements 🔌
- Server with Internet access **(VDS or PC)**, as well as with pre-installed **Python 3.10 (or higher)** and **Poetry**.
- A **Minecraft PE/BE** game server running on the **PocketMine-MP 5** core, also with internet access.

## Installation ⚡

#### Plugin Installation 📦
1. Download the archive with plugins for your game version [here](https://github.com/Taskov1ch/TelegramMC/releases).
2. Unpack the archive with plugins and install all the plugins from the archive on your game server.
3. Start and stop the server to create the configs.
4. Configure the plugin configs for your server.

#### Bot Installation 🤖
1. Download the archive with the bot [here](https://github.com/Taskov1ch/TelegramMC/releases).
2. Unpack the archive with the bot and move all the contents to the desired directory on your server.
3. Configure the configs in the **configs** directory for your server.
4. Create a `.env` file and fill it with [this](env_template.md) template, changing the values in advance.

## Correct Launch 🚀

#### Bot 🤖
1. Run the command `poetry install` in the bot directory to install all necessary dependencies *(after this you won’t have to enter this command)*.
3. Run the command `poetry run python loader.py`.

#### Game Server 🔑
Simply start your game server with the plugins installed, and that's it.
