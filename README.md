# Ollama Discord Demo

This is a quick demo to show you how to use Ollama to have LLMs of your own running via Discord!

## Installation

- Download Ollama - https://ollama.com/blog/llama3
- Run the LLMs you wish to using Ollama.
    - For using llama3.2:
        - Run ./modelfiles/run.bat for Windows users.
        - Run the individual modelfiles using Ollama.
- Use the package manager [pip](https://pip.pypa.io/en/stable/) to install any dependencies using the requirements.txt
  file (pip install -r requirements.txt)
- Go to the Discord Developer Portal to create an app [here.](https://discordpy.readthedocs.io/en/stable/discord.html)
  - Get the Discord token for the bot
  - Add it to a server
- Put your Discord token in the discord_bot_token property
- Run main.py

## Usage

- You can either DM your App or mention it on a server (@) to ask it any question you have.
- There is a sample $hello command as well; you can implement any custom commands you wish :)