<h1 align="center"><b>тнє Userbot</b></h1>

<p align="center"><img src="https://files.catbox.moe/ppms0p.jpg" alt="The UserBot"></p>

<h2 align="center">🚀 Telegram Bot on Steroids!</h3>

<h3 align="center">
    Packed with the latest commands, limitless features, etc. </br>
    Unleash the ultimate power of customization and automation like never before!
</h3>

---

![GitHub forks](https://img.shields.io/github/forks/Gokukhan1/Gokuuserbot?style=social)
![GitHub Repo stars](https://img.shields.io/github/stars/Gokukhan1/Gokuuserbot?style=social)

![Maintenance](https://img.shields.io/badge/Maintained%3F-Yes-white?&style=social&logo=hugo)
![GitHub license](https://img.shields.io/github/license/Gokukhan1/Gokuuserbot?&style=social&logo=github)

![Python](https://img.shields.io/badge/Python-v3.10-white?style=social&logo=python)
[![Documentation](https://img.shields.io/badge/Documentations-docs.hellbot.tech-white?&style=social&logo=gitbook)](https://Gokukhan1.gitbook.io/)

[![Telegram Group](https://img.shields.io/badge/Telegram-Group-white?&style=social&logo=telegram)](https://t.me/lolpagalokigc)
[![Telegram Channel](https://img.shields.io/badge/Telegram-Channel-white?&style=social&logo=telegram)](https://t.me/mlohvdryj)

---

## Deploying userBot on Heroku

Follow these 4 straightforward steps to deploy HellBot on Heroku:

1. **Fork & Star this Repo:**
    > Begin by [forking](https://github.com/Gokukhan1/Gokuuserbot/fork) and [starring](https://github.com/Gokukhan1/Gokuuserbot/) this repository on GitHub.

2. **Heroku Account Login:**
   > Ensure you are logged into your [Heroku account](https://dashboard.heroku.com) before proceeding.

3. **Click "Deploy to Heroku":**
   > Find the "Deploy to Heroku" button below, and click it, but make sure you are deploying from your fork.

4. **Fill Required Variables:**
   > On the deployment page, you'll find necessary variables to be filled out.

That's it! You've successfully deployed HellBot on Heroku. Now scale dynos and start the bot!

<p align="center">
    <a href="http://dashboard.heroku.com/new?template=https://github.com/Gokukhan1/Gokuuserbot"><img src="https://img.shields.io/badge/GokuuserBot-Deploy%20To%20Heroku-black?style=for-the-badge&logo=heroku"/></a>
</p>

---

## Deploying userBot on Linux

Hellbot can be deployed on any Linux VPS and terminal.

1. **Update Packages:**   
    ```bash
    sudo apt update && sudo apt upgrade -y
   ```

2. **Install required packages:**
    ```bash
    sudo apt install --no-install-recommends -y python3 python3-dev python3-pip python3-virtualenv git mediainfo nano ffmpeg unzip tmux
    ```
   
3. **Clone Github repository:**
   ```bash
   git clone https://github.com/The-HellBot/Plugins HellBot && cd HellBot
   ```

4. **Edit Config Variables:**
   ```bash
   cp example.env .env && vi .env
   ```
   > Now press 'i' on your keyboard to start editing the .env file.
   
   > Now fill all the env mentioned in the file.
   
   > To save the file press 'Esc' button and write ':wq' using your keyboard and press 'Enter'

5. **Install Requirements:**
    > Create an virtualenv and source it.
    ```bash
    python3 -m virtualenv venv && source venv/bin/activate
    ```
    > Now install requirements but make sure you're in (venv)
    ```bash
    pip3 install -U -r requirements.txt
    ```

6. **Start the Bot:**
    > Start a sub-terminal using tmux
    ```bash
    tmux new-session -s hellbot
    ```
    > Now start the bot
    ```bash
    ./start.sh
    ```
    > Not press 'Ctrl + B' then 'D' to detatch from tmux and let your bot run in background.

That's it! You've successfully deployed HellBot on a Linux VPS in 6 easy steps.

---

## Config Variables

- **API_HASH** : _Get this value from [my.telegram.org](https://my.telegram.org)_

- **API_ID** : _Get this value from [my.telegram.org](https://my.telegram.org)_

- **BOT_TOKEN** : _Get this value from [@Botfather](https://telegram.dog/BotFather)_

- **DATABASE_URL** : _Get this value from [mongo.db](https://account.mongodb.com/account/login)_

- **LOGGER_ID** : _A group/channel id to use as a logger chat._

- **OWNER_ID** : _The owner of bot. Only single userid is supported._

> More config details coming soon with updated documentations

---

## Disclaimer

- Our team disclaims responsibility for any consequences to your Telegram account.
If issues arise due to misuse or conflicts, accountability rests with the user.
The bot serves for recreational purposes and aims to streamline group/profile management.
User-caused account issues are beyond our purview.

- While forking the repository is permitted, we won't support edited plugins or modifications.
Responsibility for further updates lies with individual forkers. 

- This service does not provide individualized support.
Should you require assistance, kindly engage with our support group for community-based guidance.

> Thank you for choosing our bot and for your understanding and adherence.

~ Team planet sadala  ❤️

---

# License

<p align="center">
    <img src="https://www.gnu.org/graphics/gplv3-or-later.png" alt="Gokuuserbot License">
</p>

<h4 align="center">
    Copyright (C) 2024 <a href="https://github.com/Gokukhan1">The-HellBot</a>
</h4>

Project [UserBot](https://github.com/Gokukhan1/Gokuuserbot) is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.
This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU General Public License for more details.
You should have received a copy of the GNU General Public License
along with this program. If not, see <https://www.gnu.org/licenses/>.

</br>

<h2 align="center">
    Made with ❤️ by <a href="https://github.com/Gokukhan1">Goku</a>
</h2>

---
