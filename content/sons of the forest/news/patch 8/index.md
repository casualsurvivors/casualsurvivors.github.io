---
title: "Sons of the Forest Patch 8"
description: "Sons of the Forest Patch 8"
summary: "Sons of the Forest releases their seventh major update. Electric fences, new large trap, balance changes and more!"
keywords: [Sons of the Forest Patch 8"]
date: 2023-07-20
draft: false
tags: ["Sons of the Forest", "Patch 8", "Patch Notes", "Game Update", "New Content"]
authors:
  - "mala"
---

{{< lead >}}
Sons of the Forest Patch 8
{{< /lead >}}

Make sure you post any bugs or feedback you have on the [Steam Community Hub](https://steamcommunity.com/app/1326470/discussions/) so that the developers can see them!
Below you can find the information for the first Hotfix for Sons of the Forest.

Patch 8 - Electric fences, new large trap, balance changes and more!

## Features
 - New found footage video added
 - Hokey Pokey trap added
 - Electric fences
 - Freeform electric wire placement added
 - You can now carry and play radios
 - GPS Locators can now be 3d printed and crafted in the inventory
 - Golf cart lights added
 - Golf cart can now seat up to 4 players in multiplayer
 - Added reduced ammo difficulty level option
 - Added returning creepy enemy, will appear after endgame
 - Added new vocal announcements to some bunkers
 - Virginia and Kelvin can now swim if they end up in deep enough water

## Balance
 - There will now be less frequent enemy raids depending on how many regulars or creepies you have killed, this amount will increase over the days unless you kill more enemies
 - Defensive walls can now take 4 times as much damage
 - Reduced health on the special glowing puffies

## Improvements
 - Animal heads can now be shaken when held
 - Angry moose now sometimes kick a nearby player
 - Fixed some bugs that could cause too many or too few enemy search parties on loading or restarting a game
 - Fixed various save/load and syncing issues for endgame boss cutscenes and battles
 - Fixed issue where Ai actors couldn't see a player sitting in a golf cart
 - Improved getting in and out of golf cart animations
 - Kelvin will visually refuse an order that requires trees if none are nearby
 - Turtles can now be electrocuted
 - Fixed turtle eggs not spawning for multiplayer clients
 - Rabbit footsteps sound different in snow now
 - Improved putter hitting golf ball
 - Various asset memory optimizations
 - Various UI, pickup and audio optimizations
 - Blueberry bush berries now deform with bush
 - Ocean patch optimization
 - Various environment layout fixes
 - Basalt rocks added to caves merged collision meshes
 - Moss LOD ranges optimized
 - Optimized LOD2 for cliffs
 - LOD groups optimized
 - Starfish LODs added and group assignment changed
 - Stream LOD ranges optimized
 - Bunker and Cave entrances optimized
 - Small rock pickup optimized
 - Added missing LODs to some legacy rocks
 - LODs setup for KnightV, hang glider, and golf cart
 - LODs setup for Lakes
 - Lake audio emitters optimized
 - Spruce tree meshes optimized
 - Seaweed Dry Cluster LOD2 optimized
 - Optimized Berry meshes
 - Fix for some waterfall particles that were always on
 - World collisions optimized, reduced number of active colliders
 - Rocks and stones now have collision in the log sled
 - Added play visual for action camera
 - Fixed faked GI slipping over surfaces when rotating the camera
 - Improved mask maps for snow and wetness
 - Optimized fallen log LODs
 - Optimized lily pads
 - Moved dead tacti with action camera in bunker entertainment to easier to see position
 - Dead stumps and rock billboards now draw further
 - Added LODs to stick and log storage, log windows, fences
 - Energy drink item now uses a low level of detail when on shelves or a pickup
 - Optimized the in world stick pickup
 - Increased delay before boss cutscene
 - Added countdown timer to back of gold room
 - Setup streaming versions of the beached yachts to optimize memory usage
 - Removed texture streaming on golf cart logo
 - Window shutters are now animated when closing or opening
 - It is now possible to place a beam on the forward end between 2 beams supported by struts
 - Added Idle motion to Golf Cart driver and passenger so they aren’t static
 - Rifle and other weapons no longer behave strangely during player hit react animation
 - New idles for holding trophy heads
 - Knight V now leans with player correctly when viewed in third person multiplayer
 - Improved server browser filtering user experience
 - Added server browser support for search by IP address in the server name search bar
 - Added server browser filters: “not empty”, “public”
 - Added ping to the server browser entries
 - Added filters reset button to server browser
 - Dedicated servers played recently will be refreshed first to improve responsiveness
 - Dedicated servers on which you have a save will now be sorted first in list
 - Improved server browser performance
 - Improved server browser refreshing in bad networking conditions
 - Server browser gamepad navigation fixes
 - Dedicated servers won’t be detected as “game running” anymore by steam launcher, and game can now be started from steam launcher on the same machine as the dedicated server
 - Added non verbose logging mode, which is now the default mode. Verbose logging mode can be forced by using the -verboseLogging command line argument (see dedicated server guide)
 - Dedicated servers will now immediately save before shutdown to avoid data loss
 - Updated dedicated server guide: Dedicated Server Guide

## Fixes
 - Fix for player drinking from a pot when they are holding a valid container to fill up
 - Fixed issue where some items in the grab bag were hard to select due to the raycast blocker overlapping some items
 - Set deer head in the grab bag to not be convex so that it does not overlap the duck head collision
 - Fixed being able to add items to the cooking pot while its cooking clean water
 - Fix for cooking pot lid popping off for clients every time someone drinks or refills from the pot
 - Fixed issue with storage LODs not activating until the player is near them and then moves away
 - If a GPS locator is trying to be added but does not have icon data, initialize default data
 - Turtle shells are now properly dropped when skinned if the players inventory already has a shell
 - Fixed pause menu being accessible during boss cutscene
 - Prevented escape prompt from showing up early during get to the chopper cutscene
 - Fix for Screen Space reflection not turning back on after turning it off/on
 - Fixed sled hit react animation
 - Fixed bug with Crossbow reload and idle animation
 - Fixed some cases of cannibals prematurely dying while burning, and they now won't catch fire from blocked torch hit
 - Fixed player climbing cannibal lookout tower rope not being aligned with rope on some towers
 - Fixed hanging skeletons on large destroyed huts reappearing in air
 - Fixed multiple players being able to pickup the same dead body at same time, which could lead to several issues
 - Fixed some visual issues on Puffies carried by other players
 - Fixed wall not accounted for as a valid support when counting unsupported beams, it now provides the same benefit as having pillars supporting each end of the beam
 - Fixed case where destroying struts was not properly propagating the collapse to its supported beam
 - Fixed cutting pillar into a defensive wall spike not checking if it is supporting a SCREW structure, which would destroy it when applied
 - Fixed selecting terrain conforming outlines breaking placement alignment for non conforming outlines selected afterwards
 - Fixed missing snap point to place full log or stone pillars underneath second story beams
 - Fixed dirt of planter furniture not affected by snow and wetness occlusion
 - Fixed several issues with dismantling beams that could cause issues
 - Moved up last line of Barb note to not overlap thumb
 - Fixed an issue where dedicated server couldn’t be joined after the computer returned from sleep mode
 - Fixed alpha on crosses burn demons note
 - Fixed spreading phlox rendering 2 times

## Audio
 - Added SFX when placing electric wires and solar panels
 - Added frog hop audio event
 - Rifle audio distance tuned
 - Flare audio distance tuned
 - Reduced shrub hit sound level when driving a golf cart
 - Fixed noticeable clifftop surf audio turning on and off abruptly
 - Made cave entrance audio have random start times so they're unlikely to phase

## Source
If you are interested in checking out [the source](https://store.steampowered.com/news/app/1326470/view/3674425063122196245) of the information yourself, we encourage you to do so!
We here at Casual Survivors like to make our own archive of the patch notes to help better sort out the information.

## Conclusion
That's all for this major update, Patch 8 - Electric fences, new large trap, balance changes and more!

Join us on [Discord](https://discord.gg/ZXp93XsKnN) and talk to us! We are humans after all and we love to talk to other gamers such as yourself. 
