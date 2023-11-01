# Twitch Bot - User Guide

The Twitch Bot is a powerful tool that enables your Discord server to provide real-time notifications when your favorite Twitch streamers go live. This guide will walk you through the steps to use the bot effectively.

Invite the bot to your server - [INVITE](https://discord.com/api/oauth2/authorize?client_id=1003423081123033108&redirect_uri=https%3A%2F%2Ftwitchlive.13thomasbot.repl.co%2Fauth%2Fcallback&response_type=code&scope=identify%20guilds)

## Table of Contents

1. [Adding Streamers to Your Watchlist](#adding-streamers-to-your-watchlist)
2. [Removing Streamers from Your Watchlist](#removing-streamers-from-your-watchlist)
3. [Listing Streamers on Your Watchlist](#listing-streamers-on-your-watchlist)
4. [Changing the Command Prefix](#changing-the-command-prefix)
5. [Setting the Notification Channel](#setting-the-notification-channel)
6. [Checking if a Streamer is Live](#checking-if-a-streamer-is-live)
7. [Getting an Invite Link to Your Server](#getting-an-invite-link-to-your-server)

### 1. Adding Streamers to Your Watchlist

You can add your favorite Twitch streamers to the bot's watchlist so that you'll be notified when they go live. To add a streamer, use the following command:

```
!add [streamer name]
```

Replace `[streamer name]` with the Twitch username of the streamer you want to add. For example:

```
!add xQc
```

The bot will confirm the addition of the streamer to your watchlist.

### 2. Removing Streamers from Your Watchlist

If you want to remove a streamer from your watchlist, you can do so using the following command:

```
!remove [streamer name]
```

Replace `[streamer name]` with the Twitch username of the streamer you want to remove. For example:

```
!remove xQc
```

The bot will confirm the removal of the streamer from your watchlist.

### 3. Listing Streamers on Your Watchlist

To view the list of streamers on your watchlist, you can use the following command:

```
!list
```

The bot will provide you with a list of the streamers you're currently tracking.

### 4. Changing the Command Prefix

By default, the bot responds to commands that start with `!`. If you want to change the command prefix, use the following command:

```
!prefix [new prefix]
```

Replace `[new prefix]` with the new prefix you want to set. For example, if you want to change the prefix to `t!`, you can use:

```
!prefix t!
```

The bot will acknowledge the change, and you can now use the new prefix for commands.

### 5. Setting the Notification Channel

You can configure a specific channel on your Discord server where the bot will post live notifications. To set the notification channel, use the following command:

```
!setchannel [channel ID]
```

Replace `[channel ID]` with the ID of the channel where you want to receive notifications. For example:

```
!setchannel 123456789012345678
```

The bot will confirm the channel setting, and you will receive live notifications in the specified channel.

### 6. Checking if a Streamer is Live

You can manually check if a specific streamer is currently live on Twitch using the following command:

```
!checkstreamer [streamer name]
```

Replace `[streamer name]` with the Twitch username of the streamer you want to check. For example:

```
!checkstreamer xQc
```

The bot will promptly inform you whether the streamer is currently live or not.

### 7. Getting an Invite Link to Your Server

To generate an invite link to your Discord server that others can use to join, use the following command:

```
!getinvitelink
```

The bot will provide you with a link that you can share with friends, allowing them to join your server.

That's it! You're now ready to use the Twitch Bot to stay updated with your favorite Twitch streamers. If you encounter any issues or have questions, feel free to seek support in the [Discord server](https://discord.gg/pNGm9DHcuG).

Enjoy your Twitch streaming experience with real-time notifications!
