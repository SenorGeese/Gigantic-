---
description: Modding to use console commands
---

# Modding

You have to decompress it using [https://www.gildor.org/down/47/umodel/decompress.zip](https://www.gildor.org/down/47/umodel/decompress.zip) or here [https://www.gildor.org/downloads](https://www.gildor.org/downloads).&#x20;

Then you should be able to view them using [https://github.com/Dizbdeedee/UE-Explorer/releases/tag/0.0.1](https://github.com/Dizbdeedee/UE-Explorer/releases/tag/0.0.1) or  [https://github.com/Dizbdeedee/UE-Explorer](https://github.com/Dizbdeedee/UE-Explorer) to varying degrees of success.\
\
The decompiler isn't perfect when it comes to gigantic, it fails to deserialize some stuff.

This was just a modification to UEExplorer to get the initial byte offset more-or-less correct but you'd have to make additional tweaks to the program to get it to do that.

And personally that degree of C++, C# and bytecode are beyond me. It's "good enough" to get an idea of a lot of things though

Trying to extrapolate object structures from bytecode and then figuring out how UEExplorer wants me to tell it that, with how little documentation it actually has, seems like too much of a pain.

Not worth it considering the game's actively being developed again, but it's how hosting on the original event build was cracked