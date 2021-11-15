---
description: This page list all command and their functions.
---

# Commands

{% hint style="warning" %}
When using the commands don't include `<>` or `[]` brackets.
{% endhint %}

`< >` **• **Required Argument\
`[ ]` **• **Optional Argument

The command list can be accessed with `!fn help`.  Users with Manage Server or Administrator Permissions can also use `!fn help #channelname` which sends the help into a specific channel.

## Stats

| Command                        | Description                                                 |            Example           |
| ------------------------------ | ----------------------------------------------------------- | :--------------------------: |
| `!fn`                          | Retrieve the stats of the account you linked.               |              `-`             |
| `!fn <DiscordUser¹>`           | Retrieve the stats of a Discord user.                       |        `!fn @Luc1412`        |
| `!fn <PlayerName>`             | Retrieve the stats of an EpicGames account.                 |          `!fn Ninja`         |
| `!fn competitive <PlayerName>` | Retrieve the competitive stats of an EpicGames account.     |   `!fn competitive Luc1412`  |
| `!fn season <PlayerName>`      | Retrieve the seasonal stats of an EpicGames account.        |     `!fn season Luc1412`     |
| `!fn link [PlayerName]`        | Link your Discord account to your EpicGames account.        | `!fn link`, `!fn link Ninja` |
| `!fn unlink`                   | Remove the linking from your Discord and EpicGames account. |              `-`             |
| `!fn verify`                   | Verify your EpicGames Account.                              |              `-`             |
| `!fn seasoninfo`               | Display the progress of the current season.                 |              `-`             |
| `!fn stats settings`           | Manage stats settings.                                      |              `-`             |

## Nick Stats

| Command           | Description                                                                                | Example |
| ----------------- | ------------------------------------------------------------------------------------------ | :-----: |
| `!fn bplvl`       | Enable/Disable the **Battle Pass level** in your nickname.                                 |   `-`   |
| `!fn bplvl setup` | Enable/disable players on your server to set their **BattlePass level** in their nickname. |   `-`   |
| `!fn wins`        | Enable/Disable the **Wins** in your nickname.                                              |   `-`   |
| `!fn wins setup`  | Enable/disable players on your server to set their **Wins** in their nickname.             |   `-`   |

## Shop

| Command             | Description                             | Example |
| ------------------- | --------------------------------------- | :-----: |
| `!fn shop`          | Display the current Fortnite item shop. |   `-`   |
| `!fn shop setup`    | Setup automatically item shop updates.  |   `-`   |
| `!fn shop settings` | Manage item shop settings.              |   `-`   |

## Challenges

| Command                   | Description                                     |                Example               |
| ------------------------- | ----------------------------------------------- | :----------------------------------: |
| `!fn challenges [week]`   | Display the solutions to the weekly challenges. | `!fn challenges`, `!fn challenges 5` |
| `!fn challenges setup`    | Setup automatically challenges updates.         |                  `-`                 |
| `!fn challenges settings` | Manage challenge settings.                      |                  `-`                 |

## News

| Command             | Description                                         | Example |
| ------------------- | --------------------------------------------------- | :-----: |
| `!fn news`          | Display the current **Battle Royale** in-game news. |   `-`   |
| `!fn news creative` | Display the current **Creative** in-game news.      |   `-`   |

## Server Status

| Command               | Description                                 | Example |
| --------------------- | ------------------------------------------- | :-----: |
| `!fn status`          | Display the current Fortnite server status. |   `-`   |
| `!fn status setup`    | Setup automatically server status updates.  |   `-`   |
| `!fn status settings` | Manage server status settings.              |   `-`   |

## Map

| Command    | Description                        | Example |
| ---------- | ---------------------------------- | :-----: |
| `!fn map`  | Display the current Fortnite map.  |   `-`   |
| `!fn drop` | Display a random location to drop. |   `-`   |

## Radio

| Command     | Description                                         | Example |
| ----------- | --------------------------------------------------- | :-----: |
| `!fn radio` | Open the radio player and start the radio playback. |   `-`   |

## Misc

| Command     | Description                                     | Example |
| ----------- | ----------------------------------------------- | :-----: |
| `!fn event` | Display all in-game events with video playback. |   `-`   |

## Vote

| Command    | Description                                      | Example |
| ---------- | ------------------------------------------------ | :-----: |
| `!fn vote` | Display vote instructions and check vote status. |   `-`   |

## Premium

| Command               | Description                                                | Example |
| --------------------- | ---------------------------------------------------------- | :-----: |
| `!fn premium`         | Display Premium Info and Instructions on how to subscribe. |   `-`   |
| `!fn premium enable`  | Activate Premium on the server where you run the command.  |   `-`   |
| `!fn premium disable` | Disable Premium on the server where you run the command.   |   `-`   |

## Info

| Command       | Description                                                  | Example |
| ------------- | ------------------------------------------------------------ | :-----: |
| `!fn info`    | Display general information and stats about this bot.        |   `-`   |
| `!fn cluster` | Display information about the bot's clusters.                |   `-`   |
| `!fn invite`  | Display the invite link of the bot.                          |   `-`   |
| `!fn data`    | Receive data saved by the bot from your server/user account. |   `-`   |

## Settings

| Command        | Description          | Example |
| -------------- | -------------------- | :-----: |
| `!fn settings` | Manage bot settings. |   `-`   |

¹ DiscordUser could be a @Mention or a Name#Tag
