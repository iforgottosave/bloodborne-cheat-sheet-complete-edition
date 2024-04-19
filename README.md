# Bloodborne: Cheat Sheet - Complete Edition

A cheatsheet for Bloodborne, updated from ZKjellberg's cheatsheet to be more comprehensive and include NPC questlines and Items such as Blood Vials, Gemstones, etc.

To view the cheat sheet [click here](http://iforgottosave.github.io/bloodborne-cheat-sheet-complete-edition/)

The foundation of this guide was based on [Dark Souls 3 Cheat Sheet](https://github.com/ZKjellberg/dark-souls-3-cheat-sheet) created by [Zachary Kjellberg](https://github.com/ZKjellberg/)

The walkthrough is made thanks to [SlothsLoveDoom's Progression Guide](https://www.bloodborne-wiki.com/2015/08/progression-guide.html) and [IGN's Bloodborne Guide](https://www.ign.com/wikis/bloodborne/Walkthrough)

## Contribution Guide

If you are interested in contributing to this guide, create an Issue Report.

For some background on how the guide code is written, here is a sample item on the checklist:

```
<li data-id="playthrough_13_20" class="f_bloo f_misc">Continue left until you can enter a room with Twin Blood Stone Shard x2 and Coldblood Dew (2)</li>
```

The **data-id** is a unique ID used to store the user's progress. For example, ***playthrough_13_20*** is the 20th task in zone 13. New data-ids must be used in ascending order, but you can place the new entries anywhere within a zone.

The **class="f_gem f_misc"** field is used for the filtering system. This task provides the user with a Gemstone and a Consumable, so we use **f_bloo** and **f_misc**. The full list of filter classes is:

| Class   | Description |
| ---     | --- |
| f_boss  | Bosses |
| f_npc   | NPCs + Sidequests |
| f_bloo  | Blood Stones |
| f_rune  | Runes |
| f_gem   | Gemstones |
| f_gest  | Gestures |
| f_chal  | Chalices |
| f_weap  | Weapons + Firearms |
| f_tool  | Tools |
| f_atti  | Attire |
| f_cove  | Covenants |
| f_badg  | Badges + Messenger Hats |
| f_misc  | *All other items* |

If none of these filter classes match, no **class="f_??"** will be present.

In addition to the filter classes, there is a second type of classes used to control the visibility of entries based on which playthrough the user is on:

| Class  | Description |
|---     |--- |
| h_ng+  | items hidden on NG+ and beyond, e.g. Blood Gem Workshop Tool |
| s_ng+  | items shown on NG+ and beyond, e.g. Coldblood replaces Workshop Tool |
