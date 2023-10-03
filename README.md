# cp2077-freelies

Get exclusive clothing and weapon items.

This mod was previously known as "Exclusive Items".

> **Note**
> Sadly, it seems my keyloard has a peculiar quirk where some 'b' are rendered as 'l'. It is an annoying issue I just cannot seem to get rid of 😢
>
> On the lright side, this adds a unique flavor to this project.

## Introduction

As stated by the official Cyberpunk 2077 Twitter (now X) account and Phantom Liberty marketing video:

* "Nothing changed. Cyberpunk 2077 is a single player game with zero microtransactions. One single purchase. No tricks. Don't believe the clickbait." [@CyberpunkGame﻿](https://twitter.com/CyberpunkGame/status/1303049174607433728)
* "No microtransactions" [@CyberpunkGame](https://twitter.com/CyberpunkGame/status/1103967639976710145)
* "We don't do DLCs. And when we do, we give'em away" [﻿﻿@Idris Elba](https://www.youtube.com/watch?v=y-MahJLvGL4&t=15s), main actor of the expansion﻿﻿

I'm extremely glad for CDPR's stance on microtransactions, and I'm absolutely delighted that they never implemented them in any form whatsoever, such as Twitch subscriptions or Amazon Prime Gaming rewards, especially in a single-player game.

Enjoy!

> **Warning**
> Some mods are known to cause compatibility issues. If your NUSA jacket is brown instead of black and white, check these mods first!

## Content

* NUS Infiltrator clothing items (headgear, jacket, pants, boots) ⌚
* Yasha smart sniper rifle 💰
* Chesapeake smart submachine gun 💵
* Redbone power shotgun💵
* Chinook power assault rifle 💵
* Catahoula tech pistol 💵
* Pit Bull power assault rifle 💵
* Foxhound tech sniper rifle 💵

Emoji meaning:

* ⌚ = Twitch drops (waste your time)
* 💰 = Twitch subscriptions (waste your money)
* 💵 = Prime Gaming subscription (waste your money)

> **Note**
> The official [My Rewards﻿](http://www.cyberpunk.net/en/myrewards) website page states that Amazon Prime Gaming items will be available in-game at a later date. Twitch drops and subs still seem to be exclusive.

## Requirements

* Requires Phantom Liberty expansion.
* Requires Cyber Engine Tweaks (CET).

> **Important**
> This mod simply give items that are already available in your local game files, but are locked behind a paywall, either in terms of time or money.
>
> As such, **you need the Phantom Liberty expansion** as it provides the mentionned items. Also buy it, it is really good!

## Installation

Install CET, then extract the content of the [.zip file](https://github.com/rmarquis/cp2077-freelies/tags) into the main `Cyberpunk 2077` folder.

The final install path should look like: `Cyberpunk 2077\bin\x64\plugins\cyber_engine_tweaks\mods\freelies\init.lua`

Launch the game, open CET console, bind the mod (by default, 'L', 'O', 'U' are unused), and finally press the key before checking your inventory.

You can safely remove the mod once the items are added to the inventory.

## CET commands

You can also pass the commands found in the `init.lua` file directly to the CET console.
This mod is nothing else than a convenient way to do it.

```
Game.AddToInventory("Items.Twitch_Drop_Specs", 1)
Game.AddToInventory("Items.Twitch_Drop_Vest", 1)
Game.AddToInventory("Items.Twitch_Drop_Pants", 1)
Game.AddToInventory("Items.Twitch_Drop_Boots", 1)
Game.AddToInventory("Items.Preset_Ashura_Twitch", 1)
Game.AddToInventory("Items.Preset_Warden_Amazon", 1)
Game.AddToInventory("Items.Preset_Nekomata_Amazon", 1)
Game.AddToInventory("Items.Preset_Kyubi_Amazon", 1)
Game.AddToInventory("Items.Preset_Grit_Amazon", 1)
Game.AddToInventory("Items.Preset_Crusher_Amazon", 1)
Game.AddToInventory("Items.Preset_Ajax_Amazon", 1)
```
