---
description: Snippets of info for modding keybinds.
---

# Snippets

{% hint style="success" %}
Remember to make backups of the files you change.
{% endhint %}

From this random I found out if you want to assign commands to your mouse side buttons you should use `ThumbMouseButton` (back mouse button?) or `ThumbMouseButton2`(front mouse button?) . Source: [https://michaeljcole.github.io/wiki.unrealengine.com/List\_of\_Key/Gamepad\_Input\_Names/#Mouse](https://michaeljcole.github.io/wiki.unrealengine.com/List\_of\_Key/Gamepad\_Input\_Names/#Mouse)

To disable cooldowns in Practice Arena I add the line `.Bindings=(Name="M",Command="DisableCooldowns")` to `DefaultInput.ini` in `\RxGame\Config\`. You can do the same with Focus using this `.Bindings=(Name="N",Command="AddFocus 250")`.

Dodge is `GBA_DodgeModifier`.
