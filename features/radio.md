---
icon: radio
description: >-
  Tune in and game on! Learn how to set up EasyFortniteStats' radio feature,
  bringing Fortnite's in-game radio straight to your server.
---

# Radio

The radio function allows you to listen to the radio stations from the game, which are usually only available when driving a car.

To start a radio session, simply join a voice channel where the bot also has access to. The `/radio` command makes the bot join and starts playback.

## <img src="../.gitbook/assets/premium.png" alt="" data-size="line"> Premium Features

<details>

<summary>24/7 Radio Playback</summary>

Keep your radio playing continuously, even when all users leave the channel. The bot will also automatically reconnect after restarts to ensure uninterrupted playback.

</details>

<details>

<summary>Radio Volume Control</summary>

Customize the radio volume, with the ability to increase it up to 200%. The default setting is 50% to conserve bandwidth.

</details>

## Permissions and DJ Role

By default, the currently active player is owned by the user who started it. Additionally all users with `Administrator` or `Manage Server` permission can also interact with the player. Furthermore a role named `Fortnite Radio` (name isn't case sensitive) is also able to control the player at any time.

{% hint style="info" %}
If only team members should be able to access the radio, for example, because it runs in 24/7 mode, all users should have their permissions removed for the `/radio slash` command.
{% endhint %}

