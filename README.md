# EXECARD SELFBOT:

# Setup
- Install [Python](https://www.python.org/downloads/release/python-390) with `Add Python to PATH` box

- Download [Source](https://github.com/Jeancys/Execard-Selfbot/archive/main.zip) and extract

- Install modules with `installer.bat`

- Go to the `token` area and paste your [token](https://github.com/Tyrrrz/DiscordChatExporter/wiki/Obtaining-Token-and-Channel-IDs#how-to-get-a-user-token)

- Go to the `password` area and type your password (OPTIONAL) 

- Run selfbot with `launcher.bat`

[![Run on Repl.it](https://repl.it/badge/github/Jeancys/Execard-Selfbot)](https://repl.it/github.com/Jeancys/Execard-Selfbot)


# Q&A
- Q: **`SSL Certificate Error`**
- A: Just install [CRT File](https://crt.sh/?id=2835394). Then run it and install. (This is common and it was a certificate that expired May 30th 2020. But a new one came out so install it.). If you wanna go into further detail then head to [SITE](https://support.sectigo.com/Com_KnowledgeDetailPage?Id=kA03l00000117LT).  
- Q: **`Module Missing`**
- A: Just run `pip install -r requirements.txt` in console. This insures that all modules required for Alucard are installed and up to date!
- Q: **`Windll not found`**
- A: Alucard uses some windows features from modules. Example windll from ctypes. windll is used to add the console title. You can remove the title setters in-order to fix it.
- Q: **`TypeError: __new__() got an unexpected keyword argument 'deny_new'`**
- A: This error occured on an old installation of discord.py to fix simply run :`pip install -U discord.py` this updates discord.py!

# Credits

Credits to Syz#6631 and coats.#4321 for helping make this.
also Thanks to Alucard, Exeter, PH-SB, Lucifer, and TNO selfbots for giving me the Idea to put them together to make a great Selfbot.

## WARNING

Selfbots are against TOS, use at your own risk.
