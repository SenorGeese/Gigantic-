---
description: You suffer desyncs and changes in game physics.
---

# Unlocking FPS

{% hint style="info" %}
Some say it's been patched out on the June 7th update.
{% endhint %}

For those want high fps and willing to suffer desyncs:

Go to the below path and Open the file `BaseSystemSettings.ini`

```
Steam\steamapps\common\Mission 202\Engine\Config\BaseSystemSettings.ini
```

In that file, CTRL+F to search for `AllowPerFrame`.

Look for `AllowPerFrameSleep` and `AllowPerFrameYield`, they will both be set to`True`.&#x20;

Change them both to `False`.

Boot up the video game and enjoy unlimited frames (and no more momentum cancels when dodging)

Revert them if you don't like how bad physics desyncs. Highly not recommended for melee characters (you will have a bad time jump attacking or any fast movement)
