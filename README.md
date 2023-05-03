﻿# VLRNewsBot - simple bot for Valorant lineups
 
## Structure

* `main.py`: bot's codebase
* `Dockerfile`: the file to build the bot image.
* `docker-compose.yml`: used to start the bot.
* `requirements.txt`: used to specify your dependencies.

## How to deploy the bot

1. Clone or fork this repo.
2. Go to project's directory in your CMD
3. Run `docker build -t bot .`
4. Run `docker-compose up -d` and wait for the build to finish.

That's it. Enjoy your dockerized bot. 🚀
