---
title: "Sons of the Forest Patch 5"
description: "Sons of the Forest Patch 5"
summary: "Sons of the Forest releases their fifth major update. Log sleds, Re-growing trees, Advanced cooking and lots more!"
keywords: [Sons of the Forest Patch 5"]
date: 2023-05-11
draft: false
tags: ["Sons of the Forest", "Patch 5", "Patch Notes", "Game Update", "New Content"]
authors:
  - "mala"
---

{{< lead >}}
Sons of the Forest Patch 3
{{< /lead >}}

Make sure you post any bugs or feedback you have on the [Steam Community Hub](https://steamcommunity.com/app/1326470/discussions/) so that the developers can see them!
Below you can find the information for the first Hotfix for Sons of the Forest.

Patch 5 - Log sleds, Re-growing trees, Advanced cooking and lots more!

## Features
 - Buildable basic and advanced log sled
 - Tree regrowth (setting is on by default) with a 10% chance to randomly regrow when you sleep
 - Findable cooking pots and new advanced cooking system
 - Can now add tarps to log structures
 - 2 new found footage clips added
 - Beached sail boats location added
 - 79 new ponds and 34 new lakes added to map
 - You can now play the guitar
 - Added Timmy mutated arm to demon battle scene
 - New wearable clothing item added
 - New Kelvin commands added to reset traps, fill log sleds and fill drying racks with fish

## Improvements
 - Days Survived now shows the correct readout if the player died during the final interactive cutscene by jumping into the propeller blades
 - Cannibals in villages will now sometimes engage in a test of strength fight with another cannibal
 - Cannibal fear is now affected by group size, single cannibals will have more fear, large cannibal groups will have less
 - Shotgun rail is now on side of gun instead of top to avoid blocking vision
 - Turtles will now only lay eggs on sand
 - Muddies will sometimes get bored with the player and run away if not angry
 - Added Timmy mutant arm visuals to demon boss cutscene
 - Lowered priority for female cannibals stealing logs
 - Eagles may now steal dead fish
 - Throwing dead bodies on spring traps now sends them flying into air
 - Moldy food and dead flowers added to banquet hall
 - Timmy will now block the exit to hell cave until after you have defeated the boss demon
 - Timmy’s jacket will now be ripped after demon boss battle scene
 - GPS Map updated with latest lakes and rivers
 - Dead small birds now float in water
 - Fix for duplicating logs in storage triggers
 - Knight V improved sheen on pickup
 - Enforced max server name length
 - Lobby list performance improved in preparation for an upcoming feature
 - Improved support for loading into large multiplayer saves and help with structures vanishing
 - Rotated the shotgun in the weapon case in inventory so that the mods are visible now that they are on the side
 - Added localized display names for Points of Interest notifications
 - Player no longer makes a drinking sound when refilling a container with liquid
 - 3D Printer will once again update the resin volume readout when the printer is refilled
 - If an item instance module fails to deserialize on load, it will no longer stop the rest the of the players inventory from loading
 - Renamed bunker locations to be clearer when discovered
 - Improved docks draw distance
 - Added more tree moss/vines in areas of map
 - Improved bunker food lighting
 - Bunker luxury details added; More decorative items, vases, and more dead bodies
 - Added cooking pot pickup to tech apartment in bunker residential
 - Looking around now updates the target cut position when aiming at a log with an axe equipped (before it was only calculated when first targeted)
 - It is no longer possible to cut off holes in floors supporting furniture or windows from a wall that is supporting wall structures
 - Kelvin will now choose another tree to chop if a tree structure is placed on it
 - Kelvin's order will complete with the thumbs up if there are no more Arrows/Bolts, Berries, or Radios to retrieve and drop
 - Kelvin will now have berries in his hand when eating them. On fishing will have fish on initial grab
 - Added fail-safe protection against enemies falling through world and not deactivating
 - Multiplayer clients will now see the proper GPS locator type on Virginia instead of default icon
 - Current wetness on characters now replicates to multiplayer clients
 - The chainsaw revved state will now be heard and seen by other players and rev will stop when knocked down
 - Fixed small birds flying under the water surface when flying over deep lakes
 - Fixed a fish bunching up issue

## Fixes
 - Can no longer drink lava
 - Fixed under lava visuals
 - Fixed snow and wetness occlusion volumes used in specific world locations not initializing properly
 - Fixed a visual arm pop on player that appeared sometimes when landing from a fall or jump
 - Fixed Twins not always turning towards player before taunting
 - Fixed fingers stuck in standing idle after burning death
 - Fixed projectile impact FX for flesh and hard surfaces not replicating to other players in multiplayer
 - Fixed player sometimes being able to interact with other triggers when notepad was open, which could get player into stuck state
 - Fixed cannibals not staying snapped to tree edge while shimmying around the tree
 - Fixed bug where cannibals could take dismember damage while blocking
 - Fixed muddy cannibal getting angry at player if hit by a rock thrown by another muddy
 - Fixed some cases of cannibals getting blocked by collision at or above head
 - Fixed muddies having standing collision instead of hunched over
 - Fixed eating dead squirrels not increasing character fullness stat
 - Fixed some cases of far snaps for Sitting and Jumping on Rock
 - Fixed the cave shark sometimes being killed by creepies
 - Fixed multiplayer client thrown logs not breaking foliage when far away from server player
 - Fixed multiplayer client-thrown logs not causing a hit reaction on enemies
 - Fixed multiplayer clients not seeing burning effects when dead puffies are thrown onto a fire
 - Fixed multiplayer clients unable to put cannibals into the injured limb state and fixed some animation blending and smoothness issues in the injured state
 - Fixed Kelvin radios deactivating when moved far from original location, and fixed carry positioning visuals for multiplayer clients
 - Kelvin will no longer pickup broken radios
 - Fixed Kelvin when moved far away from tree target unable to find another tree to clear automatically
 - Kelvin Finish Structure command; Fixed some issues with counting logs needed. If he's holding unused items they will now be dropped on ground
 - Fixed a case where Kelvin stood carrying a single log instead of placing it then cutting a tree
 - Fixed Kelvin getting stuck if the holder he was filling was removed or destroyed. Now he will drop the item and complete the order
 - Fixed Kelvin trying and failing to fill item holders that are far above the ground
 - Fixed case where a leaning beam could link a free pillar with a structure on an incompatible placement grid
 - Fixed context allowing to place a beam with same support on both ends that isn't an Apex or a Wall
 - Fixed detached pillar placement creating degenerate pillar if it fails to find supporting ground, now properly prevents placement if there is no ground bellow (could happen when placing off a cliff for example)
 - Fixed one case where quickly sharpening stick posts causes the cut animation to fail for subsequent cuts
 - Fixed player getting stuck in carry log animation by rapidly placing and taking a log from the log holder
 - Fixed cutting quarters off dynamic logs sometimes hard to target
 - Fixed Repair Tool hitbox active while it is equipped
 - Fixed some wrong settings for quarter log LODs (rendering performance improvement)
 - Fixed Defensive Walls and DW Gates unable to be damaged by player melee hits
 - Fixed leaned beams sometimes accepting pillars on top of the bottom end before planks are added
 - Fixed cutting Defensive Wall spikes moving player too close which made subsequence cuts harder to aim
 - Fixed some localized entries in the configuration menus not showing properly on Windows machines set to Turkish display language
 - Cut down trees with axe tutorial should now only trigger the first time
 - Battery indicator on the NVGs should no longer disappear after performing certain actions
 - Fixed flickering/distortion that could appear for some players in late game saves
 - Increased reflection probe atlas to 4096x2048 (should fix issues where reflection probes could break/show wrong probes)
 - Burning Puffies should now look correct/not distort
 - Fix for 3D Printer not showing the correct initial amount of resin
 - 3D Printed Sled can no longer be placed on the crafting mat

## Audio
 - Improved player audio for other players in multiplayer
 - Added some Timmy voice acting to Gold Room cutscene
 - Made chainsaw transition to cutting sound faster
 - Reduced fade time on intro helicopter crash music
 - Made first look guitar sting 3d
 - Added beeps to opening helicopter crash
 - Improved demon boss audio
 - Set some various small objects in bunkers/morgue to have surfaces tagged for impact sounds and get melee impact physics
 - Added ragdoll impact sounds to deer and baby

## Source
If you are interested in checking out [the source](https://store.steampowered.com/news/app/1326470/view/5615470163364373632) of the information yourself, we encourage you to do so!
We here at Casual Survivors like to make our own archive of the patch notes to help better sort out the information.

## Conclusion
That's all for this major update, Patch - Log sleds, Re-growing trees, Advanced cooking and lots more!

Join us on [Discord](https://discord.gg/ZXp93XsKnN) and talk to us! We are humans after all and we love to talk to other gamers such as yourself. 
