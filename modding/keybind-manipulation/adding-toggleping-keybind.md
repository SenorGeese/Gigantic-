---
description: Adding some "TogglePing" keybind that is missing from the game
---

# Adding TogglePing keybind

{% hint style="danger" %}
This can destroy your keybinds, see below

<img src="../../.gitbook/assets/brokenkeybinds.png" alt="" data-size="original">
{% endhint %}

{% hint style="success" %}
Remember to create backups of file you modify
{% endhint %}

Path: `Steam\steamapps\common\Mission 202\RxGame\Config`

File: `DefaultInput.ini`

{% embed url="https://cdn.discordapp.com/attachments/567890339541549088/1227785544692666368/image.png?ex=6629ab65&is=66173665&hm=1915791e0b9a61d4d17c5f967aef728033929f9b92f2c5095bff250829bf8b14&" %}
Picture from Gigantic esports Discord server
{% endembed %}

You just have to add the highlighted line to the file above `; Debugging Bindings` (On line 448).

{% hint style="warning" %}
I destroyed lots of my keybinds by changing DefaultInput.ini, likely because I set the keybind to P which already existed. I recommend making a backup. I fixed it by simply Verifying Game Files in Steam.&#x20;
{% endhint %}
