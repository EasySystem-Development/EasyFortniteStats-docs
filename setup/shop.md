---
description: >-
  This article shows you how the setup automatic item shop updates in your
  Discord server
---

# Item Shop

## 🔸Premium features

* **Priority Updates** - Receive the item shop image in your server up to 15 minutes faster
* **Custom Background Image** - Use a custom image as background image for the item shop
* **No Advertising** - Remove the ad for voting and the bots Creator Code
* **Custom Support A Creator Code** - Set a custom creator code that is always displayed

## Setup Item Shop updates

If you are using the bot for the first time or you have reset the settings, you have to set up the Item Shop function for the first time.

First, enter the following command:

```
/setup shop
```

Now you need to **select** at least one **channel** where the Item Shop will be broadcast daily. Optionally, you can select a role that should always be mentioned.

### Set Channel

You can set a channel by selecting it from the dropdown menu:

<figure><img src="../.gitbook/assets/DiscordPTB_qiZtyuVlEg.gif" alt=""><figcaption><p>Setting the item shop channel</p></figcaption></figure>

#### Possible Errors

* **Missing permissions** **•** The Bot missing permissions. The bot shows you which ones are missing. If you are inexperienced with Discord check out [this guide](https://support.discord.com/hc/en-us/articles/206029707-How-do-I-set-up-Permissions-) to set up permissions.
* **Too Many Webhooks** **•** The selected channel got too many webhooks. You need to delete at least one in the channel settings.

Once you have selected a channel, the item store is set up. It should now appear in the selected channel.

### Set Mention Role

In addition, you can select a role that should always be mentioned when a new item shop appears. This can be selected via the second dropdown menu as follows:

<figure><img src="../.gitbook/assets/DiscordPTB_xEQLsqxT4H.gif" alt=""><figcaption><p>Setting the item shop mention role</p></figcaption></figure>

#### Possible Errors

* **Role mentionable by everyone •** Servers larger than 250 members can't use a role that is mentionable by everyone. This is for security reason to prevent possible abuse. Disable that @everone can mention this role in the server settings.
* **Missing permissions** **•** The Bot missing mention everyone permissions. If you are inexperienced with Discord check out [this guide](https://support.discord.com/hc/en-us/articles/206029707-How-do-I-set-up-Permissions-) to set up permissions.

### :small\_orange\_diamond:Background Image \[Premium only]

The bot asks for a background. You need to upload a file wich fulfill the following criteria:

* Image Format: `.png`, `.jpg` and `jpeg`
* Recommended Image Resolution: `1896x1321` - `1896x14666`
* Max. image size: `5MB`

&#x20;Send a message just including the image.

![](../.gitbook/assets/CEYmUTmZC0.gif)

#### Possible Errors

* **Invalid Image Format •** Your provided image has is no valid image format
* **Image too large •** The image size is larger than the given limit

### :small\_orange\_diamond:Creator Code \[Premium only]&#x20;

The bot asks for a creator code. The code has to be valid and enabled.

![](../.gitbook/assets/nvsvmrhFLs.gif)

#### Possible Errors

* **Creator Code not found •** The given creator code either doesn't exist or is not active&#x20;

## Enable/Disable Item Shop updates

If you already set up the Item Shop updates you can toggle the function by clicking the first Enable or Disable button.

![](../.gitbook/assets/09jJYsBX3a.gif)

## Reset Settings

You can reset the following settings:

* Mention Role
* Background
* Creator Code

You first need to select the setting and press the red Reset button.

You can also reset all settings when you press the button in the settings selection.
