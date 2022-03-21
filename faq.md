# FAQ

## General

### Why are the normal text commands no longer available?

On May 1, bots can no longer read all message content. This means that the bot no longer knows whether and which command was executed. This provides more privacy, but forces the messenger developers to switch to slash commands at the same time. Read more [here](https://support-dev.discord.com/hc/en-us/articles/4404772028055-Message-Content-Privileged-Intent-for-Verified-Bots).

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

## Stats

### &#x20;**My account was not found. What can I do?**

&#x20;Normally all accounts should be found. First, check if you might have a typo in your name. Also, if you are an Xbox or PlayStation 4 player, you may need to upgrade your Fortnite account on [https://epicgames.com/](https://epicgames.com) to a full EpicGames account.

### &#x20;My stats are wrong. How can this be?

The bot retrieves the stats directly from EpicGames, so they can't be wrong. There might be a typo in your EpicGames, PlayStation Network, or Xbox Live account name, or a wrong account got selected. Also, it isn't possible to compare the stats with other sources, because the bot displays them differently.

### &#x20;My stats are not up to date. What is the reason?

EpicGames don't update the stats immediately after each match. You have to wait a bit until they update. Sometimes it may take up to multiple hours.

### &#x20;Why does it say "Playtime since Season 7"?

EpicGames introduced the feature to track playtime in Season 7. That's why it's only been tracked since Season 7 (even though you played earlier).

### Why is my Arena Hype not displayed?

Due to a limitation of EpicGames we are only able to display the Arena Hype of players who are either in the top 10.000 hype leaderboard or having a player name without a space character.

### What is the Power Ranking?

The Power Ranking, created by [Fortnite Tracker](https://fortnitetracker.com), ranks the best players in the competitive field of Fortnite Battle Royale. The ranking is updated automatically every 24 hours and players move up based on their results in tournaments. Each tournament has a certain Tier, which is based on the competitive value of the tournament, the number of players, the format, and the prize pool. More Information [here](https://fortnitetracker.com/article/921/announcement-power-rankings-now-live).

### My Hype, Divison, Earnings, or Power Ranking isn't up to date. How can this be?

These values depend on FortniteTracker.com. It may take multiple hours to update your competitive data.&#x20;



## NickStats

### What happens when I change my name?

You can change your name at any time. You shouldn't write anything behind the stats value.

### How often is my stats value updated?

The stats value gets updated every 2 hours (1 hour for premium servers) by the bot. Other delays are caused by EpicGames.

### How do the wins get calculated?

All wins from all rounds where teams are not larger than 4 members are counted. (Excluding rounds with bots)
