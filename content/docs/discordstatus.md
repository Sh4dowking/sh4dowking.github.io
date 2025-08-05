---
title: Discord Status Plugin
date: 2025-08-05
---

# ℹ️ Introduction

Welcome to the **Discord Status Plugin** documentation! This guide will help you set up and customize your plugin for the best Discord experience.

---

## ⚙️ Quick Configuration

Add the following to your `config.yml` to get started:

```yaml
discordToken: "YOUR_BOT_TOKEN"
discordServerID: "YOUR_DISCORD_SERVER_ID"
updatesChannelID: "DISCORD_CHANNEL_ID"
joinMessage: "{player} has joined the Server!"
leaveMessage: "{player} has left the Server!"
```

> 💡 **Tip:** Use `{player}` as a placeholder for the player's username in your messages!

---

## 🖥️ Available Discord Commands

Easily manage your server notifications with these slash commands:

| Command | Description |
|---------|-------------|
| `/setjoinmessage <message>` | Set a new join message. Use `{player}` to show the player's username. |
| `/setleavemessage <message>` | Set a new leave message. Use `{player}` to show the player's username. |
| `/getjoinmessage` | Display the current join message. |
| `/getleavemessage` | Display the current leave message. |
| `/togglejoinmessage <true/false>` | Enable or disable join notifications on Discord. |
| `/toggleleavemessage <true/false>` | Enable or disable leave notifications on Discord. |

---
