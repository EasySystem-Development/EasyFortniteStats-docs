---
description: >-
  Gear up in style! Configure EasyFortniteStats to show Fortnite's latest item
  shop offerings right within your Discord.
icon: cart-shopping
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

Once you have selected a channel, the item shop is set up. It should now appear in the selected channel.

### Set Mention Role

In addition, you can select a role that should always be mentioned when a new item shop appears. This can be selected via the second dropdown menu as follows:

<figure><img src="../.gitbook/assets/DiscordPTB_xEQLsqxT4H.gif" alt=""><figcaption><p>Setting the item shop mention role</p></figcaption></figure>

#### Possible Errors

* **Role mentionable by everyone •** Servers larger than 250 members can't use a role that is mentionable by everyone. This is for security reason to prevent possible abuse. Disable that @everone can mention this role in the server settings.
* **Missing permissions** **•** The Bot missing mention everyone permissions. If you are inexperienced with Discord check out [this guide](https://support.discord.com/hc/en-us/articles/206029707-How-do-I-set-up-Permissions-) to set up permissions.

### :small\_orange\_diamond:Background Image \[Premium only]

You might want to select a custom background image for the item shop. Therefore you first need to upload an image with `/image upload`. If it falls below the maximum image size specified below, you can select it.&#x20;

* Image Format: `.png`, `.jpg` and `jpeg`
* Recommended Image Resolution: The resolution of the image may differ a lot. The bot will automatically resize the image to fit the card, so high resolution images are recommended.
* Max. image size: `5MB`

<figure><img src="../.gitbook/assets/DiscordPTB_fTmFaorU58.gif" alt=""><figcaption><p>Setting a custom Background Image</p></figcaption></figure>

You can also deselect the image from the dropdown menu, which will disable the custom background image.

### :small\_orange\_diamond:Creator Code \[Premium only]&#x20;

As a premium member, the bots Creator Code will be hidden from the Item Shop image. You my also want to provide your own Creator Code. After Clicking the Creator Code Button, a popup will appear where you can enter the Code in a text field.

<figure><img src="../.gitbook/assets/DiscordPTB_361ln6Y1RV.gif" alt=""><figcaption></figcaption></figure>

#### Possible Errors

* **Creator Code not found •** The given creator code either doesn't exist or is not active&#x20;

Once a Creator Code has been set, the popup always show the current code in the text field. You can disable the code by removing the code from the text field and submitting it.

### Enable/Disable Item Shop updates

You can disable or enable Item Shop posts while keeping all settings. Just click the Enable or Disable button

* If the green Disable button is shown, Server Status posts are currently active
* If the red Enable button is shown, Server Status posts are currently disabled

<figure><img src="../.gitbook/assets/DiscordPTB_LtgZ7cnwCf.gif" alt=""><figcaption></figcaption></figure>
