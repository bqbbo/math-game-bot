# Math Game Bot

A Discord bot for a simple math game, written using Discord.py and packaged with Poetry.

This Discord bot comes complete with its own interpreter, supporting basic operations and factorials.

The interpreter was made with help from [CodePulse's *Simple Math Interpreter*](https://www.youtube.com/playlist?list=PLZQftyCk7_Sdu5BFaXB_jLeJ9C78si5_3) series, with some added functionality on my part.

## Contributing/Executing

Install all dependencies using `poetry install` after cloning the repository. You will need to configure your IDE with the virtual environment it generates, or it may not detect the installed dependencies, or execute the run script with `poetry run python run.py` directly.

If you plan to use `run.py`, the `MATH_BOT_TOKEN` environment variable must be set with your bot's token, which can be created and found on the [Discord Developer Portal](https://discord.com/developers/).

**You should assume the bot requires all intents.**

Thank you for contributing!

## Using the Bot

### Method 1

Add [this application](https://discord.com/api/oauth2/authorize?client_id=1204659279936880690&permissions=8&scope=bot) to your Discord server. You may not be able to add it to certain servers depending on the permissions you have.

**The application will not respond to any commands unless it is currently being executed on my hardware.**

### Method 2

Clone the repository, and follow the instructions for contributing. After exporting the token and executing `run.py`, the bot should go online.

Exporting an environment variable using the `export` command only lasts for the duration of the terminal session it was used, meaning the token could be lost. You may want to consider creating a `.env` file to store the token.

## Maintenance

I likely will stop committing new functionality to the bot after it is working, meaning I will not work on any issues or bug fixes.
