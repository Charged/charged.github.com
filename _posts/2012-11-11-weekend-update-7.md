---
layout: post
title: Weekend update 7
---

Again we need to thank Scoot for his continuing amizing work on the Launcher.
Which just now moved to the Charged organization under github. A lot of work
has been put into behind the scene changes to make the Charge game engine a
lot better and nicer to work with.

But what about the fun stuff you say? Well player physics has been added, that
seems to be quite close to how Minecraft Classic works, with the exception of
water/lave physics not being there yet. Also the fog/background is no longer
just a solid blue wall, its a completely nested scene so anything can be put
in it, like mountains off in the distance.

Currently the [help](/help.html) page is a bit lacking, some help would be
greatly appreciated, both for Charged Miners and the Launcher. No fancy html
knowlage is required as its all written in a the super simple markdown format,
see [here](https://raw.github.com/Charged/charged.github.com/master/help.md),
you can just checkout the source for this page
[here](https://github.com/Charged/charged.github.com).


 * Added player physics everything except water/lava should work.
 * Add sky and ocean horizon, instead of the boring blue fog.
 * Silence warnings in logs that wheren't warnings.
 * Add a proper flying mode thats toggleable with the 'Z' button.
 * Add doxygen documentation integration.
 * Massive refactoring of code for more eventual porting to D2.
 * _Fix_: Really really odd other player movement issues, from net code.
 * _Fix_: Deal better with weird UTF-8 chars in paths.
 * _Fix_: Various fixes for refactoring.
 * _Fix_: Better logging and errors for missing OpenGL features.

Just run the launcher and it will update it automatically!
