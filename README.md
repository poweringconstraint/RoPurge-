## 🚫 RoPurge
> Guardian against inappropriate avatars in Roblox games

RoPurge is a server script for Roblox games who want to keep their games safe, clean, and family friendly. 
It automatically detects and removes players with inappropriate, explicit, or harmful avatars.

> 🛠️ RoPurge Features

✅ Auto kick players with inappropriate avatar items

✅ Customizable the banlist

✅ Discord webhook support, get notified in your server channel whenever a player is detected and kicked for inappropriate content.

✅ User friendly configuration

> 🔍 How It Works
RoPurge scans player avatars on join. If a match is found in the banned word list, the player is removed from the server, and a log is sent to your designated Discord webhook. 

Severity thresholds can be adjusted.


> 📦 Installation
- Copy the RoPurge script and paste it into ServerScriptService.

- In Discord, go to Server Settings → Integrations → Webhooks → Copy URL.

- Paste the webhook URL into the designated place in the script.

- Enable HTTP Requests in Game Settings

Publish and run your game, RoPurge handles the rest.
