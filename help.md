---
layout: default
title: Help
---
### Support

If something broke, scroll down to the [Common issues](#troubleshooting)
first, as the most common issues are listed there.

The most common issues, along with tips and tricks, are addressed in this
page, but you can always contact the ones responsible for Charged Miners
in the [IRC][IRCWiki] channel [#charged-miners][] on [Esper][]. You can
also report bugs and add feature requests [here][Wiki].

### Installation

Charged miners is easily installed, you only need to download the launcher,
which is done through the big [Download][] button on the
website. Charged miners needs a texture pack, but it can get that from the
minecraft on your computer. If it says it cannot find one, go to
[minecraft.net][MCPlay] and play minecraft classic,
this gives charged-miners all it needs.

### Play

#### Launcher

The launcher provides many options to connect, the most basic of which is
"Sign In", entering a username and password gives you a serverlist from which
you can pick the one you want. If you were handed an url to join you can paste
that in the obvious field to join the server immediately.

Useful is the "Resume" tab when you play on the same server a lot, this tab
usually directly lets you rejoin a server, without needing to look through a
list of any sort, and keeps working when minecraft.net is down.

The "Direct" tab uses an url scheme that bypasses minecraft's login servers,
and thus still can be used to join any server when minecraft.net is down.

"Options" and "Tools" let you do some black magic, there is, for example, a
"failsafe" checkbox in "Options", this will use a simpler graphics path,
lowering graphics quality but preventing crashes on some AMD cards.
There's also an "Upload Log" in the "Tools" tab which contains a secret chant
that, when preformed by initiates, shows them exactly what went wrong.

#### Charged-Miners

Charged-miners plays very much like minecraft does. You can place and destroy
blocks through clicks of the mousepointer, select blocks with middle-click,
walk around, chat, and so forth.

But it also lets you do more, you can freely place special blocks like water
and lava, you can fly around and go five times as fast. There's even an option
that makes you fly through blocks like a ghost, while still retaining
visibility.

##### Keys

The following keys are usable:

 * left click - remove block
 * right click - place block
 * middle click - pick block
 * scroll - scroll through from hotbar
 * `w` `a` `s` `d` - movement
 * `spacebar` `q` - Jump or fly up
 * `e` - fly down
 * `b` - pick block
 * `t` - chat
 * `/` - chat with '`/`' prefixed
 * `z` - start or stop flying
 * `x` - enable or disable noclip
 * `shift` - run
 * `1`..`9` - pick block from hotbar
 * `o` - screenshot
 * `esc` - Open or close the menu
 * `F3` - Show fps and others
 * `F2` - Hide UI

### Configuration

Most of the configuration is done through the in-game esc-menu, or in the
launcher. When you're in a server, pressing `ESC` brings up a menu where
various game aspects can be changed, pressing `ESC` again or clicking "Close"
closes the menu. ("Quit" closes Charged-miners alltogether!) If you prefer,
many of these options can also be changed through the custom `/client` command.

#### Lag

If you suffer from low framerates, there's a couple of things you can do. The
biggest causes of a low framerate are the shadows and anti-aliasing (`aa`), it
may also help to decrease the render distance, but Charged-miners usually
handles far rendering much better than minecraft.net's client.

#### Texture "Packs"

Charged Miners support both Modern and Classic terrain.png’s. Normally it will
use the texture from the installed Minecraft version on the system. You can
overwrite this by placing a terrain.png in the texture folder, this folder can
be found via clicking the "Open data directory" button in the "Tools" tab of
the launcher, or the "Open textures & screenshots" button in the esc-menu of
the game itself.

The file should be called `terrain.png` for a Modern Minecraft terrain.png and
`terrain.classic.png` for a Classic Minecraft texture. This is important or
things will look very odd.

You can also replace the backgrund in the menu. It looks for two files
`background.png` is centered on a black background in the middle of the screen.
While `background.tiled.png` is tiled over the screen.

### Troubleshooting

#### Minecraft.net down

If Minecraft.net is down, neither login nor the server list will work properly.
Luckily the "Resume" and "Direct" tab will continue working, as they don't
need you to log in.

#### The game crashes when loading at 90%

This seems to be common on older AMD cards, try updating your driver or enable
"failsafe" from the launcher's "Options" tab.

#### Your porblem not listed here?

If nothing here helps, get your help [directly from us](#support)!


[Download]: https://github.com/downloads/Charged/Miners/ChargedMiners.exe "Download launcher here"
[#charged-miners]: irc://irc.esper.net/charged-miners "Stay a while"
[IRCWiki]: http://en.wikipedia.org/wiki/Irc "IRC on wikipedia"
[Wiki]: http://wiki.vg/ChargedMinersClassic "Wiki"
[MCPlay]: http://minecraft.net/classic/play "Play classic"
