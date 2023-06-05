---
categories: game
title: "PURGED"
permalink: /projects/purged
---

- **Solo Project**
- **Unreal Engine 4** (4.26.2) - **C++ and Unreal Blueprint**
- Project Length: **1 Year** (May 2022 - May 2023)

Explore an abandoned base, now occupied by crazed fanatics attempting to protect something dangerous below the surface. Based on Old-School shooters, find the exit while defeating enemies, finding secret caches, and collecting treasure along the way.


[Gameplay Footage](https://youtu.be/XZTKOEdhpJo)
<iframe width="560" height="315"
	src="https://www.youtube.com/embed/XZTKOEdhpJo">
</iframe>

Programming
-----
- The Player class manages player input, moving around the level, and interacting with objects. A Player has an Inventory structure that stores and manages all the player’s items.
- All Weapon stats are stored and referenced from a Data Table. Each weapon’s stats can be modified including damage, accuracy, fire rate, and the bullets fired per shot.
- The Enemy class uses Behaviour Trees to manage logic regarding patrolling, chasing, and attacking targets. Data Assets store enemy stats and can be modified to create unique enemy types.
- Multiple Data classes help keep track of enemies killed, secrets found, and treasures collected.
- The Player HUD and all game menus are programmed using Widgets. The game’s settings menu utilizes Widget Templates for its buttons.
- A Basic Save system stores custom settings and the Player’s Inventory between levels. Progress since the last completed level can be loaded between game sessions.

Art/Animation
-----
- Created all sprites for enemies, items, icons, and some textures.
- All enemies and weapons were animated by hand or using Unreal Engine’s Timeline.
- Textures from online sources were modified to be used in the game’s world.

Other
-----
- Programming was first created with Blueprint for fast prototyping and iteration, then recreated with C++. Afterwards, a mixture of Blueprint and C++ is used depending on the task.
- Source Control (using GitHub) is used to both manage progress and to revert changes.
- Sound Effects are recorded by myself or taken from online sources. The effects are created or modified using Audacity.

Screenshots
-----
<p>
  <img src="/assets/purged/screenshot6.png" alt="screenshot1-2023" width="49%"/>
  <img src="/assets/purged/screenshot7.png" alt="screenshot2-2023" width="49%"/>
</p>

<p>
  <img src="/assets/purged/screenshot8.png" alt="screenshot3-2023" width="49%"/>
  <img src="/assets/purged/screenshot10.png" alt="screenshot-20234" width="49%"/>
</p>

![screenshot5](/assets/purged/screenshot9.png)
