# BotStatus
Updates your bot status in the message, every two hours.

**_NOTE:_** This branch needs to be hosted to work. If you prefer to host on GitHub WorkFlows, visit [the other branch](https://github.com/xditya/BotStatus/tree/gh-wf).

# Variables.

- `APP_ID` and `API_HASH` from [my.telegram.org](https://my.telegram.org).
- `BOTS` - TG UserName of your bots separated by space.
- `SESSION` - Telethon SessionString of the User to edit the message.
- `CHANNEL_ID` - ID of your channel.
- `MESSAGE_ID` - ID of the message to edit.

Fill these in a `.env` file, if hosting on a VPS.

[![Deploy To Heroku](<p align="center"><a href="https://dashboard.heroku.com/new?template=https://github.com/iamproaf/stats"> <img src="https://img.shields.io/badge/Deploy%20On%20Heroku-black?style=for-the-badge&logo=heroku" width="220" height="38.45"/></a></p>

# Credits

- [odysseusmax](https://github.com/odysseusmax/bug-free-broccoli)
- [Telethon](https://github.com/LonamiWebs/Telethon)
- [Me](https://xditya.me)
