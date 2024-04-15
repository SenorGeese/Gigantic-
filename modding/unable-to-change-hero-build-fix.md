---
description: Description and fix to the "Unable to Change Hero/Build" bug.
---

# Unable to Change Hero/Build (Fix)

{% hint style="success" %}
Remember to make backups of the files you modify
{% endhint %}

{% hint style="danger" %}
This changes may break your keybinds if performed incorrectly.

<img src="../.gitbook/assets/brokenkeybinds.png" alt="" data-size="original">\
If you do break your keybinds. Try replacing the file with your backup, or use the Verify Game files option in Steam
{% endhint %}

## Issue: Changing "Skill 4" keybind in-game breaks the ability to "Change Hero/Build"

<figure><img src="../.gitbook/assets/skill4ingame.png" alt=""><figcaption><p>Skill 4 keybind in settings in-game</p></figcaption></figure>

<figure><img src="../.gitbook/assets/brokenchangeherobuild.png" alt=""><figcaption><p>Broken "Change Hero/Build" bug (I set keybind to "B")</p></figcaption></figure>

## Fix: Changing DefaultInput.ini

There is probably another file that is better to edit, until I find that, this works to fix the bug.

Go to path: `~\Steam\steamapps\common\Mission 202\RxGame\Config`

Open `DefaultInput.ini`&#x20;

Go to line 419:

<figure><img src="../.gitbook/assets/beforechanges.png" alt=""><figcaption><p>Line 419 of DefaultInput.ini</p></figcaption></figure>

Make these changes below, changing Line 419 and adding Line 420. This edit includes creating a new line, separating the keybinds, and setting your preferred keybinds.

<figure><img src="../.gitbook/assets/afterchanges.png" alt=""><figcaption><p>The changes in place to fix the bug which is changing</p></figcaption></figure>

In the example above, I set "Change Hero/Build" to `E`, and set "Skill 4" to `B`.

<figure><img src="../.gitbook/assets/finalproduct.png" alt=""><figcaption><p>"Change Hero/Build" is working, and E skill is set to B.</p></figcaption></figure>

## Enjoy your personalized keybinds!

<div align="center">

<figure><img src="../.gitbook/assets/Wingiganticcolor-300px.png" alt="" width="150"><figcaption><p>W Fix</p></figcaption></figure>

</div>

## Leads:&#x20;

{% content-ref url="adding-toggleping-keybind.md" %}
[adding-toggleping-keybind.md](adding-toggleping-keybind.md)
{% endcontent-ref %}

{% content-ref url="broken-hero-build-swapping-by-ardaim.md" %}
[broken-hero-build-swapping-by-ardaim.md](broken-hero-build-swapping-by-ardaim.md)
{% endcontent-ref %}
