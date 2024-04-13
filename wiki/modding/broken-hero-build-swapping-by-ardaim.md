---
description: >-
  Researching and finding a workaround for the broken hero/build swapping
  keybind bug.
---

# Broken Hero/Build Swapping by Ardaim

The keybinds file is in `C:\Users\Username\Documents\My Games\Gigantic\RxGame\Config\RxInput.ini`&#x20;

{% hint style="info" %}
&#x20;There is also other config files found in `Steam\steamapps\common\Mission 202\Engine\Config` and `Steam\steamapps\common\Mission 202\RxGame\Config`
{% endhint %}

and the line responsible for the bug is `Bindings=(Name="E",Command="GBA_Skill4 | GBA_ChangeHero",Control=False,Shift=False,Alt=False,bIgnoreCtrl=False,bIgnoreShift=False,bIgnoreAlt=False)`&#x20;

if you try to rebind it in any way it gets deleted and substituted with a line without the `GBA_ChangeHero` part. There is no solution for this. If you try to change it manually, make a new line with only ChangeHero, etc, every time you open the settings in game it gets deleted. Even setting the file to read only doesn't work. The file doesn't change but you still get key empty in game.&#x20;

The only solution for this is to use autohotkey and make a new script with something like this in it

{% embed url="https://cdn.discordapp.com/attachments/1210050267689648148/1227985541723852943/Screenshot_2024-04-11_160648.jpg?ex=662a65a8&is=6617f0a8&hm=0a6215e30877a90bb9c3ffc8063a2d1410326bbb35083106c0c85b1876bba5fc&" %}

in my example if i press E on my kb the game thinks is B. So you go in settings, bind forward, press it and you will see it's now bound to B. But you phisycally press E

For my fourth skill i like to use Z, with the second line when i press it on the kb the game thinks it's E. You can replace Z in the script with wathever you like but you CANNOT rebind E in game otherwise the bug will trigger.

You have to run this script as administrator everytime you launch the game otherwise it doesn't work

You can edit the script with any text editor

The only downside is you will always have skill 4 on E in the game ui

Don't forget to close the script when you are done with the game. Right click and close on the green H icon in the tray

Source: [https://discord.com/channels/230415910991691776/1210050267689648148/1227983243186536572](https://discord.com/channels/230415910991691776/1210050267689648148/1227983243186536572)
