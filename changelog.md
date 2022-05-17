# Changelog

## V3.3.1 - 2022-05-17

This patch comes with mostly under the hood changes implementing recently released Discord features.

{% hint style="warning" %}
Discord extended the Slash Command enforcement until 09/01/2022. Our migration period has been extended until 08/01/2022. This date marks the end of the availability of text commands. (eg.`!fn shop`)
{% endhint %}

### Additions

* Implemented Discords new [Command Permissions System](https://discord.com/blog/slash-commands-permissions-discord-apps-bots) available under `Server Settings -> Integrations -> EasyFortniteStats`
  * `/setup`, `/settings`, `/data` commands are only available for members with Manage Server permissions

### Changes/Improvements

* The stats command's name option now provides a search functionality for Fortnite Player names.
  * This function supports searching for EpicGames, Xbox Live and Playstation Network playernames.
  * EpicGames player IDs are also supported
  * Alternatively, you can enter a name or ID without selecting an option.
* The `/radio` command can now be used without selecting a radio station in the command itself. Instead a dropdown selection is shown. This is especially useful when just resuming a radio session.
* The `/radio` menu always shows a dropdown for switching the radio station, instead going trough 2 steps.
* We fixed a performance lack which should result in better performance and should reduce "Interaction doesn't respond" error messages
* Improved stats image creation speed
* Most commands have been enabled in direct messages
* Selecting a player name and a Discord user at the same time in the `/stats` command now result in an error message for clarification.
* Improved a few messages to make things more clear

### Fixes

* Fixed an issue that caused an endless loading state when retrieving your stats or linking your account
* Premium enabled server wasn't able to use the `/data` server commands.
* Fixing issue problems when interaction with the radio menu while bot is disconnected&#x20;

## V3.3.0 - 2022-02-01

{% hint style="danger" %}
This update introduces a 3 month transition period from normal Text Commands (eg.`!fn shop`) to the new Slash Commands (eg.`/shop`). On 04/01 all text commands will finally be disabled.
{% endhint %}

### Additions

* Added support for [Slash Commands](https://support.discord.com/hc/en-us/articles/1500000368501-Slash-Commands-FAQ). All previously available commands are available as normal commands and slash commands.
  * Some command error messages are now [Ephemeral Messages](https://support.discord.com/hc/en-us/articles/1500000580222-Ephemeral-Messages-FAQ), which will only be shown to the user who invoked the command
  * The `/stats` provides a list of available input types.
  * `/challenges` now provide you a list of available weeks for the optional week argument
  * `/news` now provides the list of modes to select from
  * `/radio` provides you the list of available radio stations
  * Instead of having individual `!fn bplvl` or `!fn wins` commands, the slash command implementation uses `/nick-stats`. This also provides a list of available types.
  * `!fn seasoninfo` command was renamed to `/season` as a slash command
* Added a Context User Command which allows receiving the stats of a specific user. Just right-click a user in your server -> Click ''Apps" -> Select "User Stats"
* Added `/cosmetics` Command which provides details about a specific cosmetic.
  * This command is only available as a slash command
  * Cosmetic Names can be autocompleted
  * Pro mode command option available. This will provide more details often useful for leaks.
* Added an option to `/settings` that allow the bot to prefer the user's language over the server language. Active by default.
* Nick Stats now support Arena Hype using `/nickstats stats-type:Arena Hype points`
* Added game-info argument to `/season` command. This provides general information about the game. \[Slash command only]

### Changes/Improvements

* Improved speed of receiving stats
* When using a text command the bot replies to the user's command.

### Fixes

* Fixed error which blocked creative news setup
* Fixed error which occasionally when pre-selected an input type and switching the stats type which didn't have stats for the desired type yet
* Fixed issue that the bot doesn't respond if selecting an input type which the player never played with
* Fixed an error that was raised when using a quote like character in the stats text command (eg. `"`, `‘`, `《`)
* Fixed error which occurred when setting up automatic updates and providing an invalid channel or role and the bot got no permissions to respond
* Fixed rare issue which caused an error when starting the radio
* Fix rare issue which breaks the auto channel setup

## V3.2.1 - 2021-10-23

### Changes/Improvements

* Switched the verification System: The new verification isn't based anymore on accepting a friend request and providing a 4-digit code. Now you just need to log in with your account on the EpicGames website and need to authorize EasyFortniteStats to verify your account
* Temporarily disabled the challenges command, due to the new challenges format which has been introduced in Season 8.
* Reduced radio quality from 384kb to 128kb for a more stable experience

### Fixes

* Fixed problem which caused that the verification stopped when clicking the checkmark icon in direct messages
* Fixed a problem caused that other users were able to interact with buttons from commands invoked by other users.
* Fixed an error that occurred when using `!fn challenges [week]` with a non-number argument for the week.&#x20;
* Fixed an issue that news wasn't updated properly
* Fixed possible errors which occurred while setting up a bot feature and messages were already deleted
* Fixed a problem which caused that the hype amount displayed where wrong.
* Fixed problem which didn't fully respect pre-seasons and may caused displaying the wrong arena hype value

## V3.2.0 - 2021-09-04

### Additions

* Added support for [Discord's new buttons](https://support.discord.com/hc/en-us/articles/1500012250861-Bots-Buttons). Following features support buttons:
  * Challenges (including seamless switching between weeks)
  * Stats (including seamless switching between input types and stats types eg. Lifetime)
  * News (including seamless switching between Gamemodes eg. BattleRoyale)
  * Radio (more details below)
  * Map (shortcut to open the map in full quality)
  * Drop (generate a new location with just one click)
  * Help (more details below)
  * Confirming (Verification, Data deletion)
  * Settings (General, Shop, Challenges, ServerStatus)
  * Voting (Shortcut to open main Vote page)
* Automated News Updates: News can now get automatically posted into a specific channel like challenges or the item shop. This feature can be set up with `!fn news settings`
* Radio Stable Release: Radio has been now finally been implemented. It's more stable and less buggy. All subcommands have been removed. Only `!fn radio` is needed to open the player which lets you manage the bot with the new buttons.
  * Added 24/7 Playback for **premium users**🔸
  * Due to the extra required resources, volume control is only available to **premium users** 🔸
* Help rework: The help command has been fully reworked and now supports buttons and dropdown menus.
  * Commands are now sorted into categories
  * Categories can be navigated with a dropdown menu
  * A bot news section has been added to the help command
* Settings Rework: Settings have been redesigned with buttons. Also `!fn settings` is now a place to reach all bot settings including Shop, Challenges, etc.
* Stats now let you select an account if there are multiple accounts with the same name
* Added `!fn review` to show off all pages to review the bot.&#x20;
* After setting up automatic updates, initially all data is sent into the channel. (latest shop, current seasons cheat cheats, etc.)

### Changes/Improvements

* The bot doesn't require the "Add Reactions" permission anymore
* The general bot speed has been optimized
* Dates and Times shown by the bot are now based on your timezone
* Countdowns/Relatives Dates/Times now automatically updated

### Fixes

* Fixed that Arena Hype was reset too early for most users&#x20;
* Fixed a few wrong terms and typos
* Nick Stats setup has been fixed
* Fixed mentions in shop updates

## V3.1.0 - 2021-05-21

### Additions

* Competitive Stats: Get just your Arena and Tournament matches including Arena Hype, Division, Earnings, and FortniteTracker.com's Power Ranking (`!fn comp`)

![](<.gitbook/assets/Stats Competitive.png>)

* Seasonal Stats: Only display the stats that you have earned in the current season. (`!fn season`)
* Season Command: View info on the current season and progress (`!fn seasoninfo`)
* Added Trio Stats in Stats image
* Added Privacy Policy: [https://www.easyfnstats.com/privacy](https://www.easyfnstats.com/privacy/)
* Added support for server and user data deletion (`!fn data server delete`, `!fn data user delete`)
* The Bot has been added to [https://discordextremelist.xyz/](https://discordextremelist.xyz/en-US/bots/fortnite)

### Changes

* Reformatted Stats Image

![](<.gitbook/assets/Stats (1).png>)

* Moved FAQ to docs (`!fn faq`)

### Fixes

* Fixed issue that selections work when adding the same reaction in another channel
* Fixed issue that bot lobbies still included
* Fixed verification error message if an account is claimed
* Fixed shop command which doesn't work in rare cases
* Fixed issue that the shop image is sometimes missing
* Fix that BattlePass level progress bar broken on too small progress
* Fix reaction doesn't work on verification start

## V3.0.0 - 2021-03-08

V3 is a complete overhaul of V2. The source code has been 100% re-written and nothing was copied from the old Bot. This causes that all bugs from old versions to get fixed. V3 offers a fresh new feel and look without being unfamiliar.

### Additions

* Account Verification: Verify that you own a specific account and get benefits (`!fn verify`)
* Nick Stats: Show off your BattlePass level or wins in your nickname. More types coming soon! (`!fn bplvl`, `!fn wins`)
* Global Stats: You now can now also get all stats from all different input types combined
* News: The bot now supports BattleRoyale and Creative in-game news (`!news`, `!news creative`)
* Fortnite Radio: Listen to the Fortnite in-game radio channels live in Discord. (`!fn radio`)
* Fortnite Shop now supports multiple languages
* Stats image now show off how often you placed Top 25
* Premium now will be automatically granted and can be en/disabled through a command (`!fn premium`)
* All reaction/text menus have been overhauled. You also can react during reactions are getting added
* `!fn challenge` now takes a `[week]` parameter for quick access eg. `!fn challenges 3` :arrow\_right: Shows the week 3 challenge cheat
* User with `Manage Server permission` can now also modify the bot
* `!fn cluster` command for Cluster overview
* `!fn data` command to receive the data saved by the bot
* Prefix setting for **Premium** users (`!fn settings`)

### Changes

* Changed the Stats calculation.&#x20;
  * More LTM stats and Trio are now included in Stats Calculation
  * Bot Lobby rounds are no more counted
* New Stats image design (`!fn stats`)&#x20;

![New Stats Image Design](.gitbook/assets/Stats.png)

* New Item Shop image design (`!fn shop`)

![New Shop Image Design](.gitbook/assets/2021\_02\_02\_en.png)

* `!fn challenges` now support up to 15 instead of 10 weeks
* `!fn drop` has been overhauled by adding more locations that get automatically updated. Also, the location gets marked on the map.&#x20;
* The Information shown in `!fn info` was updated
* Updated the `!fn event` command with the latest events

### Fixes

* Instability issues have been resolved. Crashes or timeouts should now be rarer.
* No, half or wrong challenge images were shown
* No more "Please finish your last action before you can execute another command." :tada:&#x20;

### Removals

* Score, Average Kills, and Stats won't be displayed anymore, because they were irrelevant or duplicated&#x20;
* Support for getting stats from other members by Name#Tag (This change was made due to Discord limitation and may be changed when Discord add an alternative way)
* Removed Danish and Ukraine due to missing translator and low demand&#x20;
