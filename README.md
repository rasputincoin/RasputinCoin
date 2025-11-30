# RasputinCoin XP Bot

This is a community engagement bot for the subreddit **r/rasputincoin**.  
It assigns XP (experience points) to users based on their activity and automatically updates their subreddit flair to reflect their rank.

### ⭐ Features
- Tracks subreddit activity in real time
- Awards XP for posts and comments
- Saves total XP for every user
- Automatically assigns flair based on XP levels
- Fully customizable rank system via `config.json`
- Uses Reddit's API and runs on Python (PRAW)

### 🧮 XP System
- **+5 XP** per post  
- **+1 XP** per comment

### 🌟 Ranks
| Rank | XP Required |
|------|-------------|
| CryptoPeasant | 20 XP |
| CryptoMonk | 150 XP |
| CryptoRoyalty | 800 XP |
| CryptoProphet | 3000 XP |

Flair is updated dynamically, for example:  
`🔮 CryptoMonk (156 XP)`

### 📦 Files
- `rasputin_xp_bot.py` — main bot script  
- `config.json` — rank settings and XP values  
- `xp_data.json` — XP storage file (auto-generated at runtime)

### 🔧 Requirements
- Python 3.x  
- PRAW (`pip install praw`)  
- python-dotenv (`pip install python-dotenv`)  

### 📝 Setup (coming after Reddit API approval)
Once Reddit approves API access, the `client_id` and `client_secret` will be added to a `.env` file.

The bot will then run with:


<!--
**rasputincoin/RasputinCoin** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
