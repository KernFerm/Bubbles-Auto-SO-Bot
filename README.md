# Bubbles Auto Shoutout Bot

## What is Bubbles Auto Shoutout Bot?
Bubbles Auto Shoutout Bot is a powerful and automated Twitch bot designed to enhance engagement in your chat by automatically giving shoutouts to streamers who participate in your channel. This bot helps promote other streamers and fosters a supportive Twitch community by recognizing active chatters and encouraging networking.

### Features:
- **Automatic Shoutouts:** No need for manual commands—streamers get an automatic shoutout when they chat.
- **Cooldown System:** Prevents excessive shoutouts by enforcing a 4-hour cooldown per user.
- **Ignore List:** The bot will not shoutout known Twitch bots or the broadcaster.
- **Game Information:** When a user is live, the bot includes their current game in the shoutout.
- **Twitch IRC Connection:** Seamlessly integrates into Twitch chat without the need for additional configuration.

---

## How to Add Bubbles Auto Shoutout Bot to Your Twitch Channel

### Step 1: Request Access
To add the bot to your channel, ping **BubblesAutoSOBot** in the **#bubblesautosobot-help** channel on Discord.

- **Join our Discord server:** [DISCORD INVITE LINK](https://discord.gg/eCGpWUf5aR)
- **Contact:** Ping `@BubblesAutoSOBot` in **#bubblesautosobot-help** with your Twitch username to request the bot to be added.

### Step 2: Authorize the Bot
Once access is granted, follow these steps to authenticate the bot:
1. Start the bot on the host server.
2. The bot will provide an authorization link in the console.
3. Open the link in your browser and log in with your Twitch account.
4. Authorize the bot to join your channel and interact in chat.
5. Once authorized, the bot will automatically join and start functioning.

---

## How the Bot Works
1. When a user chats in your stream, the bot checks:
   - If the user has already received a shoutout in the last 4 hours.
   - If the user is a known bot (from the ignore list).
   - If the user is the broadcaster (the bot does not shout out the channel owner).
2. If all conditions are met, the bot sends a message like:
   ```
   🚀 Hey everyone! Don't miss out on @username's incredible Twitch channel at https://twitch.tv/username! They're a fantastic streamer and a valued member of our community! 🎉
   ```
3. If the user is currently live, the bot includes their viewer count and game:
   ```
   🎉 Check out @username at https://twitch.tv/username! They are live right now with 50 viewers playing Call of Duty! 🔥
   ```

---

## Support & Troubleshooting
If the bot is not working as expected:
- Ensure you have authorized it correctly.
- Check the bot's status in our Discord server.
- Restart your Twitch chat or re-authenticate via the authorization link.
- Reach out for support in **#bubblesautosobot-help** on Discord.

---

## License
Bubbles Auto Shoutout Bot is provided as-is. Use at your own discretion. If you have suggestions or feature requests, let us know via Discord!

Happy Streaming! 🚀
