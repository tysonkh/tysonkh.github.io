---
layout: page
title: Beatdown and Twin Curse ReCursed
permalink: /projects/beatdown-and-recursed
---

In 2020, I started a project to update two existing games: [High School Hero][hsh] and [Twin Curse][tc]. The main goal was to update the game and address issues with the games that weren't fixed when they were available, using experience working on other games. 

Beatdown (High School Hero update)
-----
Beatdown is the name of the updated version of High School Hero. The main change was to the combat system. The new version of combat is more traditional, but characters' abilities were done through minigames that made attacks stronger the more successful the minigame outcome was.

The visuals were updated for some elements of the game. All enemy sprites were updated, several world sprites were improved, and the user interface was overhauled to look more similar to other RPG menus. The level design and general game progression wasn't altered from the original release, however. While the general story wasn't altered, some dialogue and pacing was changed.

Internally, the source code was refactored or redone. The main feature was a database-like structure to manage data for characters, enemies, and items. Various scripts help manage damage calculations, minigames, and status effects. Numerous game managers help hold important data for the current session, as well as manage combat systems like turn order.

<p>
  <img src="/assets/beatdown/screenshot2.png" alt="screenshot2" width="49%"/>
  <img src="/assets/beatdown/screenshot3.png" alt="screenshot3" width="49%"/>
</p>
<p>
  <img src="/assets/beatdown/screenshot4.png" alt="screenshot4" width="49%"/>
  <img src="/assets/beatdown/screenshot5.png" alt="screenshot5" width="49%"/>
</p>

Twin Curse (The ReCursed Cut)
-----
In comparison to Beatdown, Twin Curse received a smaller update. The visuals were larged unchanged sprite-wise, as the main focus was on rebalancing the game to “flow” better, namely balancing bosses to make fights not last as long, and allowing players to quickly go through levels if they manage to find the hidden power ups.

Because the visuals haven't changed at all, the screenshots from this version were used for the original [Twin Curse page][tc].

[hsh]: /projects/high-school-hero
[tc]: /projects/twin-curse
