---
description: You suffer desyncs and changes in game physics.
---

# Unlocking FPS

For those want high fps and willing to suffer desyncs:

Go to and Open the file `BaseSystemSettings.ini`

```
steamapps\common\Mission 202\Engine\Config\BaseSystemSettings.ini
```

In that file, CTRL+F `AllowPerFrame`, `AllowPerFrameSleep` and ,`AllowPerFrameYield`, will both be `True`.&#x20;

Change them both to `False`.

Boot up the video game and enjoy unlimited frames (and no more momentum cancels when dodging)

Revert them if you don't like how bad physics desyncs. Highly not recommended for melee characters (you will have a bad time jump attacking or any fast movement)
