---
categories: game
permalink: /projects/knights-meadow
logo: /assets/knights-meadow/title-long.png
---
<p>
  <img src="/assets/knights-meadow/title-long.png" alt="logo"/>
</p>

- **Solo Project**
- **Unreal Engine 4** (4.26.2) - **C++ and Unreal Blueprint**
- Project Length: **~5 Months** (September 2023 - February 2024)

A small action-adventure game inspired by King’s Field.

Explore to collect loot and weapons. Use those weapons to become stronger against the monsters that roam the land. Venture into the Dungeon to defeat the rampaging beast that has made it its home.

<iframe frameborder="0" src="https://itch.io/embed/2508413?bg_color=979797&amp;fg_color=222222&amp;link_color=dbd707&amp;border_color=5a82a9" width="552" height="167"><a href="https://noonereadsthis.itch.io/knights-meadow">Knight's Meadow: The Solemn Village by noonereadsthis</a></iframe>

Programming
-----
- Uses the Gameplay Ability System to manage stats, damage, and status effects as well as player abilities.
- Inventory Component manages the player's inventory. The Inventory Widget lists the player's inventory with item previews and item details.
- Widget Stack Component manages widgets into a stack, allowing players to navigate in and out of game menus easily.
- A Device system that allows certain interactable objects to be turned on or off.
- AI use a mix of Behaviour Trees as well as a simple steering behaviour to navigate around areas.

Art/Animation
-----
- Many models and textures were taken from online sources, and modified with Blender, Paint.net, and Krita when needed (sources are in the game's credits).
- Added simple animations with Unreal Engine's sequencer.
- Created the Status Effect icons.

Other
-----
- Almost all of the programming was done in Blueprint. C++ was added to include GAS.
- Source Control (using GitHub) is used to both manage progress and to revert changes.
- Multiple data tables manage the Items used in the game.
- Enemy Data Assets hold the enemy's stats and abilities (ex. if they can shoot projectiles).

Screenshots
-----
<p>
  <img src="/assets/knights-meadow/kffp_screenshot0.png" alt="screenshot1" width="49%"/>
  <img src="/assets/knights-meadow/kffp-screenshot1.png" alt="screenshot2" width="49%"/>
</p>

<p>
  <img src="/assets/knights-meadow/kffp-screenshot2.png" alt="screenshot3" width="49%"/>
  <img src="/assets/knights-meadow/kffp-screenshot4.png" alt="screenshot4" width="49%"/>
</p>