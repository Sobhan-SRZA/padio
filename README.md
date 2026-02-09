# Padio - The Ultimate Discord Radio Bot 📻🎧

Welcome to **Padio**! Padio is an advanced radio bot for Discord voice channels that lets you enjoy a wide range of trending online radio stations with high-quality, seamless performance. Whether you're gaming, working, or relaxing, Padio brings your favorite tunes directly to your voice channels.

---

## Key Features ✨

- **Seamless Performance** – High-quality, lag-free audio.
- **Wide Variety of Radio Stations** – Popular and trending stations included.
- **Multilingual Support** – English, فارسی, Türkçe, 中文, 日本語.
- **Customizable Command Prefix** – Define your own prefix.
- **User-Friendly Control Panel** – Manage radio playback within Discord.
- **Effortless Station Switching** – Change between stations quickly.
- **24/7 AFK Mode** – Keep Padio active in a designated voice channel.
- **Robust Database Support** – All settings saved securely.
- **Clean & Developer-Friendly Code** – Easy to modify and extend.

---

## Getting Started 🚀

1. **Invite Padio** to your server via the invite link.  
2. **Run Setup Commands**:
   - `/setup panel` → Creates a control panel in a text channel.
   - `/setup prefix` → Sets a custom command prefix.
   - `/setup language` → Chooses your bot language.
3. **Enable 24/7 Mode** with `/afk [channel | id]`.
4. **Control Playback** with `/play`, `/pause`, `/resume`, `/stop`, `/volume`.

Type `/help` after inviting Padio to see a full list of commands.

---

## Setup Guide 🛠

### Panel Setup

- `/setup panel`  
  Creates a control panel in a specific text channel. Saves the channel and message IDs to the database.

### Prefix Setup

- `/setup prefix [your_prefix]`  
  Customize the command prefix for your server. Saved in the database for consistency.

### Language Setup

- `/setup language [language_code]`  
  Available languages: English, فارسی, Türkçe, 中文, 日本語.  
  The choice is saved per server.

### AFK Mode

- `/afk [channel | id]`  
  Keeps Padio active in the voice channel 24/7. The bot will remember the last played station.

---

## Commands Overview 🎵

### Admin Commands

| Command           | Description                               |
| ----------------- | ----------------------------------------- |
| `/setup panel`    | Creates control panel for radio playback. |
| `/setup prefix`   | Sets custom command prefix.               |
| `/setup language` | Sets bot language.                        |

### Music Commands

| Command                | Description                                 |
| ---------------------- | ------------------------------------------- |
| `/play [station]`      | Start streaming your chosen radio station.  |
| `/pause`               | Pause playback temporarily.                 |
| `/resume`              | Resume paused playback.                     |
| `/stop`                | Stop playback and leave the channel.        |
| `/volume [1-200]`      | Set or view the current volume.             |
| `/afk [channel \| id]` | Enable 24/7 playback in the chosen channel. |

### Misc Commands

| Command             | Description                            |
| ------------------- | -------------------------------------- |
| `/about`            | Shows Padio info and features.         |
| `/help`             | Lists all available commands.          |
| `/invite`           | Invite Padio to another server.        |
| `/ping`             | Check bot latency.                     |
| `/report [message]` | Report bugs or issues to the dev team. |

### Owner / Developer Commands

| Command         | Description                         |
| --------------- | ----------------------------------- |
| `p!setactivity` | Change bot activity temporarily.    |
| `p!guilds [id]` | List servers where Padio is active. |

---

## Data & Privacy 🔒

Padio collects minimal data **only for server management**:

- **Panel IDs** – Text channel & message IDs.
- **Custom Prefix & Language** – Saved per server.
- **AFK Mode & Last Station** – Voice channel ID and station saved.
- **Usage Statistics** – Commands used for improving service.

All data is stored securely and used only to manage settings and enhance your experience.

**Privacy Policy:** [Read Here](/docs/privacy-policy)

---

## Terms of Service 📜

- Only admins can run setup commands.  
- AFK mode keeps the bot active 24/7 in designated channels.  
- Users must provide accurate info; misuse may lead to bot removal.  
- Bot is provided “as-is” with no guarantees of uptime.  

**Full Terms:** [Read Here](/terms-of-service)

---

## Contact & Support 💬

**Developer:** [Sobhan-SRZA](https://github.com/Sobhan-SRZA)  
**Support Server:** [Join Here](https://discord.gg/AfkuXgCKAQ)  

<div align="center">
  <a href="https://t.me/d_opa_mine"><img src="https://raw.githubusercontent.com/Sobhan-SRZA/Sobhan-SRZA/refs/heads/main/images/telegram-ch.svg" height="30" /></a>
  <a href="https://www.instagram.com/mr.sinre"><img src="https://raw.githubusercontent.com/Sobhan-SRZA/Sobhan-SRZA/refs/heads/main/images/instagram.svg" height="30" /></a>
  <a href="https://www.youtube.com/@mr_sinre"><img src="https://raw.githubusercontent.com/Sobhan-SRZA/Sobhan-SRZA/refs/heads/main/images/youtube.svg" height="30" /></a>
  <a href="https://github.com/Sobhan-SRZA"><img src="https://raw.githubusercontent.com/Sobhan-SRZA/Sobhan-SRZA/refs/heads/main/images/github.svg" height="30" /></a>
</div>
