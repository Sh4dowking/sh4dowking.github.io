---
title: Discord Status Plugin
date: 2025-08-05
---
# WORK IN PROGRESS!

## ⚙️ Configuration
Example `config.yml`:
```yaml
discordToken: "YOUR_BOT_TOKEN"
discordServerID: "YOUR_DISCORD_SERVER_ID"
updatesChannelID: "DISCORD_CHANNEL_ID"
joinMessage: "{player} has joined the Server!"
leaveMessage: "{player} has left the Server!"
```
### Placeholders
{player} -> Use this to indicate the Username of the Player who joined/left the Minecraft Server.

---

## 🖥️ Discord Commands

| Command                    | Description                     | 
|----------------------------|---------------------------------|
| /setjoinmessage `<message>`  | Sets a new join message         | 
| /setleavemessage `<message>` | Sets a new join message         | 
| /getjoinmessage            | Shows the current join message  | 
| /getleavemessage           | Shows the current leave message | 

---
