---
title: "Sons of the Forest Patch 4"
description: "Sons of the Forest Patch 4"
summary: "Sons of the Forest releases their fourth major update. Action cam, A.I. improvements, bug fixes, GPS changes and lots more!"
keywords: [Sons of the Forest Patch 4"]
date: 2023-04-20
draft: false
tags: ["Sons of the Forest", "Patch 4", "Patch Notes", "Game Update", "New Content"]
authors:
  - "mala"
---

{{< lead >}}
Sons of the Forest Patch 3
{{< /lead >}}

Make sure you post any bugs or feedback you have on the [Steam Community Hub](https://steamcommunity.com/app/1326470/discussions/) so that the developers can see them!
Below you can find the information for the first Hotfix for Sons of the Forest.

Patch 4 - Action cam, A.I. improvements, bug fixes, GPS changes and lots more!

## Features
 - Added new ‘Action Cam’ item and first found footage tape
 - Added new point of interest discovery laptops
 - Added ability to name save games
 - Added kick and ban popup messages when kicked or banned from a game

## Improvements
 - Kelvin can now carry 2 logs at a time!
 - Brighter night vision goggles
 - Added snow impact effects to snow crash cutscene
 - Longer Timmy fighting demon boss intro animation
 - High sentiment Virginia should now visit player more often
 - Added more spots in villages for cannibals to stand watch or sit around
 - Muddies are now more likely to flee when scared
 - Cannibals now sometimes look at each other when not fighting
 - Cannibals have new animation variations for running and lunging attacks making them more evasive in combat
 - Cannibal creepy and leaf armor will now be visually broken and knocked off when hit
 - Female cannibals will sometimes drink blood from village troughs or from dead animals, cheer for other family members and occasionally dance to radio music
 - Male cannibal will now sometimes bash dead bodies of enemies
 - Skinned small animals now will have skinned visuals. Specifically the rabbit, squirrel, eagle, duck, seagull, land turtle
 - Low health Deer and Moose will sometimes lay down and rest
 - Add a wetness amount per character that increases when submerged in water or cleaning in water, and reduces over time when not
 - Dead bodies now get washed (blood/dirt) in water
 - Increased Deer bleeding and increased damage caused by hitting front body
 - Bird flight speed increased by a small percentage
 - Torn silver jacket added to end mutant
 - Added some ducks on the golf course
 - Added north arrow guide to mini map
 - Ballistic impact effects from other players will now be visible in multiplayer
 - Armor is now dropped if the player does not have available space for it if it's cycled off being worn
 - Grenades and bombs will now play a water explosion effect when thrown in water
 - Dead cultists clothing is now bloody
 - Added more flower wreaths on some dead cultists
 - Added new binder prop to security rooms
 - Improved some of the lighting in bunker residential
 - Improved armor rack LOD
 - Added binoculars, night vision goggles, wire and lightbulbs to quick select slots
 - 3D Printer readouts should update more accurately now
 - Fallen Log E scaled down to 65% size
 - Some fixes for open edges on cliff above golf course
 - New lake added to golf course
 - Kelvin can now finish building shelves
 - Setup LOD’s for logs in storage holders
 - GPS map updated to include all current ponds and lakes
 - Removed location pins from opening cutscene laptop screen

## Fixes
 - ‘I Dream of Sushi’ achievement is once again achievable
 - Fix for players game hanging when switching from empty slingshot to another ranged weapon that has swappable ammo
 - Player should no longer get into a bad state if they are spamming a weapon hotkey while opening a door with a keycard
 - Animal Hide and tech mesh will now be greyed out on the grab bag when interacting with an armor rack
 - Removed rebinding for back action
 - Fixed lone life jacket floating in sky
 - Fixed issue where option menu could be opened at the end of loading screen
 - Fixed some missing player disconnected notifications
 - Fix for not being able to drink from deep bodies of water
 - Crafted spears no longer fall through cave floors
 - When a storage structure is destroyed and stored pickups are spawned, it is now spread over multiple frames to ease the performance overhead and create less frame stutter
 - Fixed issue where the left side UI notifications would stop showing up after the player has died
 - Trying to equip your left hand item light is now blocked when the player is in another action
 - Fix for collider not being enabled on dynamic pickups sometimes
 - Fix for pause menu continuing to add force to players on ziplines
 - Fixed some initialization issues causing DLSS to not be enabled by default / after reset settings
 - Added harsh slope limitation to block riding knight V up steep slopes
 - Added localization credit names and fixed font for fallback characters
 - Fix for player crouching while riding Knight V
 - Fixed being able to dismember dead cannibal without destroying armor on the limb first
 - Fixed big hut destruction sometimes leaving a floating corpse and standing walls with no collision
 - Fix for the quick select bag getting stuck in the players hands or getting stuck in a bad state if it is triggered at the exact same time as the player begins swimming
 - Fixed Kelvin carry radio position
 - Fix for clients in multiplayer sometimes seeing muddy cannibal hit reacts have standing glitch frames
 - Fixed muddy cannibal leaf piles sometimes not showing for multiplayer clients
 - Fixed multiplayer clients not seeing Kelvin carried arrows properly
 - Fixed multiplayer clients sometimes doing first note long animation on first interact with Kelvin
 - Fixed a case where clients could see and interact with a "ghost" Kelvin not at his real position
 - Some fixes for Virginia washing in waterfall, and will now occur at more waterfalls around the map
 - Virginias GPS will now retain the assigned icon when given to her
 - Fix for Virginia or Kelvin sometimes getting stuck in sitting animation
 - Fix thrown small rocks falling through ground when bouncing
 - Fixed silenced pistol shot being heard as regular shot by other players
 - Fixed case of player getting stuck in skinning action
 - Shovel attack will now slow down when low stamina
 - Fixed wrong ceiling panel in bunker entertainment
 - Fixed destroying defensive wall log with spike not using the right model for the spawned pickup, also solved the scaling issue
 - Fixed cutting defensive wall spike not working in some cases
 - Fixed scaling of destroyed rock reinforcement pickups
 - Fixed destroyed defensive wall spikes of quarter Logs not working properly
 - Destroying ramps a solar panel is on now spawns a pickup
 - Placed solar panels now have collision
 - Fixed a specific case where connecting Electric Wires would not work
 - Fixed bug causing incorrect count of light bulbs and solar panels received on pickup
 - Fixed case that allowed placing a Beam connecting two structures from unaligned grids, resulting in a degenerate stretched or compressed Beam
 - Fixed Lookout tower placement being blocked if there is a Defensive Wall underneath the overlook
 - Fixed One sided apex blocking placing Pillars on top of Ramps
 - Removed switch mode UI prompt that didn't do anything when placing a Defensive Wall Gate
 - Fixed an issue that would result in multiplayer clients unable to build anything or receive construction updates from the host
 - Fixed case where snow & wetness occlusion as well as solar panel initialization didn't work for tree structures
 - Fixed case where removing an electric wire didn't work properly and could prevent the underlying power grid system from splitting in two and behaving as expected
 - Fixed case where a leaning beam snap point would be invalid (arrow in red) when it should be allowed
 - Fixed issue when loading a save that could prevent other features such as placing ramps from functioning properly
 - Fixed a case where a free pillar in middle of a grounded beam grid would cause degenerate leaning beam placements
 - Fixed destroying solar panel support not cascading to the solar panel
 - Fixed issue where drinking while holding multiple log planks could result in broken animation state
 - Fixed case where non log items spawned by construction system would fall through the ground
 - Fixed destroyed log pickups ending up with oversized collision
 - Fixed destroyed non log element pickups not matching physics with the visual in some cases
 - Fixed structure collapse applying delay between elements even if it doesn't spawn a pickup, resulting in weird behavior when destroying the fire wood stack for example
 - Fixed some issues with Beams leaned down slopes from Walls, which were incorrectly displaying the lift preview prompt and placing awkwardly
 - Fixed issue causing some missing Beam snap points after removing a pillar supporting a beam that is also supported by a Wall
 - Fixed multiplayer issue where players enter a broken state if killed while starting to climb a rope
 - Fixed multiplayer issue where placing a stick or rock path would wrongly show up for remote players while placing it, which could lead to game breaking issues
 - Fixed multiplayer issue with physics doors that could prevent clients from locking it if it was stuck open on host side
 - Fixed players able to remove chairs and benches from under seated AI or remote players
 - Fixed destroyed defensive walls built with non-full Logs reverting to unsharpened state
 - Fixed element collapse order for apex & one-sided apex, ensuring top elements break before lower ones
 - Fixed one-sided apex behaving oddly when hit with a repair tool
 - Fixed issue preventing placing a Beam from a Pillar to the top of a Leaning Beam if there is another Beam linked
 - Fixed case where Leaning Beams were not being repaired properly
 - Fixed issue with Beams supported by a low Ramp that would prevent removal of the Beam and add a degenerate Pillar placement
 - Fixed multiplayer issue where players could dismantle a Log from a Wall and add a Wall Beam simultaneously, resulting in a floating Beam

## Audio
 - Fixed some sounds in multiplayer having a very low precision location
 - Fixed other players hearing double impact sounds from shovel and repair tool
 - Cannibal armor now has impact audio when hit
 - Pistol no longer doubles up on its reload audio
 - Tuned terrain and motor levels of Knight V
 - Fixed fade time on gunshots in opening crash sequence
 - Added gunshots to the Demon Boss sequence
 - Demon Boss attack audio and hurt audio for intro and added new music sting audio
 - Tuned waterfalls large and small, and water spots

## Source
If you are interested in checking out [the source](https://store.steampowered.com/news/app/1326470/view/3707067917836253973) of the information yourself, we encourage you to do so!
We here at Casual Survivors like to make our own archive of the patch notes to help better sort out the information.

## Conclusion
That's all for this major update, Patch 4 - Action cam, A.I. improvements, bug fixes, GPS changes and lots more! You can expect the next update on May 11th around 1:30pm PST. Keep in mind that's just an estimate and not an exact time based on previous patches.

Join us on [Discord](https://discord.gg/ZXp93XsKnN) and talk to us! We are humans after all and we love to talk to other gamers such as yourself. 
