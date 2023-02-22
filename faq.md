# FAQ

## General

### Why are the normal text commands no longer available?

On August 31, bots can no longer read all message content. This means that the bot no longer knows whether and which command was executed. This provides more privacy, but forces the messenger developers to switch to slash commands at the same time. Read more [here](https://support-dev.discord.com/hc/en-us/articles/4404772028055-Message-Content-Privileged-Intent-for-Verified-Bots).

### How do slash commands work?

You only need to type `/` in the chat window, which opens a menu with all available commands, sorted by bot. You just need to select the command of your choice. Read more [here](https://support.discord.com/hc/en-us/articles/1500000368501-Slash-Commands-FAQ) about slash commands.

![How to execute the /help command.](.gitbook/assets/2x6C3RQ.gif)

### I can't see a slash command, how can I change that?

#### No Permissions

Users may not be able to use slash commands in this channel. For this, the users who should be able to use the commands must get the **Use Application Commands** permissions.&#x20;

#### Slash Commands disabled

It may be that when the bot was invited, it was not given all the requested permissions. This blocks them from creating Slash Commands. A server administrator must then [re-invite the bot](setup/invite.md).

### The bot doesn't respond, what can I do?

In most cases, this issue is caused by the wrong permission setup. The Bot requires 'View Channel' permissions in the channel you like to use the bot. If you are inexperienced you might grant Administrator permissions.

In rare cases, it might be caused by a bot restart or outage. If you checked the permissions and the bot doesn't answer for more than 10min feel free to contact us on [our support server](https://easyfnstats.com/discord).

### How can I disable certain commands?

Discord recently introduced the [Command Permissions System](https://discord.com/blog/slash-commands-permissions-discord-apps-bots). This allows you to allow or deny specific **Slash Commands** to certain roles, users or channels. To get started go to "Server Settings" -> "Integrations" -> "EasyFortniteStats" and modify the given settings.

![](.gitbook/assets/NVIDIA\_Share\_ZvSuTTiHDu.gif)

## Stats

### &#x20;**My account was not found. What can I do?**

&#x20;Normally all accounts should be found. First, check if you might have a typo in your name. Also, if you are an Xbox or PlayStation 4 player, you may need to upgrade your Fortnite account on [https://epicgames.com/](https://epicgames.com/) to a full EpicGames account.

### &#x20;My stats are wrong. How can this be?

The bot retrieves the stats directly from EpicGames, so they can't be wrong. There might be a typo in your EpicGames, PlayStation Network, or Xbox Live account name, or a wrong account got selected. Also, it isn't possible to compare the stats with other sources, because the bot displays them differently.

### &#x20;My stats are not up to date. What is the reason?

EpicGames don't update the stats immediately after each match. You have to wait a bit until they update. Sometimes it may take up to multiple hours.

### &#x20;Why does it say "Playtime since Season 7"?

EpicGames introduced the feature to track playtime in Season 7. That's why it's only been tracked since Season 7 (even though you played earlier).

### Why is my Arena Hype not displayed?

Due to a limitation of EpicGames we are only able to display the Arena Hype of players who are either in the top 10.000 hype leaderboard or having a player name without a space character.

### What is the Power Ranking?

The Power Ranking, created by [Fortnite Tracker](https://fortnitetracker.com/), ranks the best players in the competitive field of Fortnite Battle Royale. The ranking is updated automatically every 24 hours and players move up based on their results in tournaments. Each tournament has a certain Tier, which is based on the competitive value of the tournament, the number of players, the format, and the prize pool. More Information [here](https://fortnitetracker.com/article/921/announcement-power-rankings-now-live).

### My Hype, Divison, Earnings, or Power Ranking isn't up to date. How can this be?

These values depend on FortniteTracker.com. It may take multiple hours to update your competitive data.&#x20;

## NickStats

### What happens when I change my name?

You can change your name at any time. You shouldn't write anything behind the stats value.

### How often is my stats value updated?

The stats value gets updated every 2 hours (1 hour for premium servers) by the bot. Other delays are caused by EpicGames.

### How do the wins get calculated?

All wins from all rounds where teams are not larger than 4 members are counted. (Excluding rounds with bots)

## Account System \[`/account`]

### How does this system work?

With this feature, you can log into your Fortnite account via the bot. This allows you to manage them trough Discord.&#x20;

Like any other bot with such a function, this one then gets full access to the Fortnite account. This is the only way to provide such features. As a result, you have to trust our bot. In the following section we explain why you can trust us.

### Can I trust EasyFortniteStats?

We would say that EasyFortniteStats is one of the most trustworthy bots for the following reasons:

* EasyFortniteStats has been around since 2018 and has not made any mistakes that would allow unauthorized people to access such data. We have always prioritized our morals throughout these years to provide the best possible experience for our users.
* We take security seriously. Our server is secured according to the latest security standards. Additionally sensitive data is encrypted with military grade encryption
* The owner (Luc1412#1412) is working with EpicGames to maintain the Discords bots in the official Fortnite Germany Discord
* We have decided against possibly higher profits and have included a verification that should restrain account trading with the bot.
* We inform the users about possible risks and security measures.

### Can I get banned for using it?

There are no known cases in recent years where players have been banned for using such a feature. In very rare cases accounts were deactivated, but these can be reactivated via support. We have also taken measures to prevent this completely.&#x20;

Bans may occur at the most when exploiting bugs with the help of the bot. However, we actively choose not to make such exploits available

### What does \[BETA] mean for this feature?

This feature is currently still in a beta testing phase, although it is available in the normal bot. Currently, we have only been able to test and optimized the feature based on a small number of accounts so far. We can't guarantee that it will work with every account at the moment, so we're making it publicly available for anyone interested so we can improve the bot. However, these errors can only restrict the function of the bot, but cannot cause any damage to your account.
