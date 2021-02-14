---
description: >-
  This article shows you how the setup automatic item shop updates in your
  Discord server
---

# Item Shop

## Setup Item Shop

### Set channel

First, enter the following command:

```text
!fn shop setup
```

The bot first asks for the channel where the shop should appear. You can either enter the channel **name**, channel **mention** \#channel or insert the channel **ID**. Please send a message just including this information.

{% hint style="warning" %}
If you decide for entering the channel's name, you need to check if the channel name is unique in your server.
{% endhint %}

#### Possible Errors

* **Channel not found** **•** The given Channel doesn't exist in your server.
* **Missing permissions** **•** The Bot missing permissions. The bot shows you which ones are missing. If you are inexperienced with Discord check out [this guide](https://support.discord.com/hc/en-us/articles/206029707-How-do-I-set-up-Permissions-) to setup permissions.

### Enable mention Role

Now the bot asks whether a role should be mentioned.   
React with ✅ if you like to set up a role. If not react with ❌.

The setup ends if you do not like to set up a mention role.

### Set Mention Role

The bot now ask for a mention role. You can either enter the role **name**, role **mention** \#channel or insert the role **ID**. Please send a message just including this information.

{% hint style="warning" %}
If you decide for entering the roles name, you need to check if the rolename is unique in your server.
{% endhint %}

#### Possible Errors

* **Role not found** **•** The given Channel doesn't exist in your server.
* **Role mentionable by everyone•** Servers larger than 250 can't use a role which is mentionable by everyone
* **Missing permissions** **•** The Bot missing mention everyone permissions. If you are inexperienced with Discord check out [this guide](https://support.discord.com/hc/en-us/articles/206029707-How-do-I-set-up-Permissions-) to setup permissions.

