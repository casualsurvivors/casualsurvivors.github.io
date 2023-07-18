---
title: "Sons of the Forest Patch 7"
description: "Sons of the Forest Patch 7"
summary: "Sons of the Forest releases their seventh major update. Rifle, head trophies, drivable carts, dedicated servers, frogs and more!"
keywords: [Sons of the Forest Patch 7"]
date: 2023-06-23
draft: false
tags: ["Sons of the Forest", "Patch 7", "Patch Notes", "Game Update", "New Content"]
authors:
  - "mala"
---

{{< lead >}}
Sons of the Forest Patch 7
{{< /lead >}}

Make sure you post any bugs or feedback you have on the [Steam Community Hub](https://steamcommunity.com/app/1326470/discussions/) so that the developers can see them!
Below you can find the information for the first Hotfix for Sons of the Forest.

Patch 7 - Rifle, head trophies, drivable carts, dedicated servers, frogs and more!

## Features
 - New end boss battle and cutscene
 - Dedicated servers [STEAM GUIDE HERE](https://steamcommunity.com/sharedfiles/filedetails/?id=2992700419&CasualSurvivors.com)
 - Drivable golf carts
 - Rifle
 - Decorative frogs
 - Animal head trophies
 - Stone doorways, struts, windows and pillar detached placement
 - New stone holder structure
 - Window shutters
 - Updated environment on East side of the map with more streams, waterfalls, lakes, ponds, cannibal villages, rope bridges and more
 - Some new story note pickups added
 - Dirty/clean water system added

## Improvements
 - Stones now apply damage to things when thrown
 - You can now attach stones or any length of log to ziplines rather than just full logs
 - A held relocated structure is now thrown if the player opens their inventory
 - Added new cat food visual
 - Wall shelves can now store cooking pots
 - Kelvin can now finish building stone fireplaces
 - Improved look of burning sticks material
 - Improved look of boiling water
 - Improved performance of trees in winter
 - Improved stone/rock text localization
 - Cannibal winter clothes now burn when the bodies are burned
 - "Collected" and "added to backpack" text when picking up items is now localized
 - Added LOD support so that items in storage holders will disable when far away
 - Fixed issue with armor pieces on shelves having expensive scaled mesh colliders
 - Adjusted some duck landing spots on water that were over land
 - Repairing floors no longer re-orders its planks
 - Disassembling a Custom Effigy now takes the limb you are targeting instead of the last limb added
 - It should now be easier to place furniture in crowded areas
 - Improved player on fire visuals
 - Added an idle variation to ducks and increased their drinking and eating rate when on lakes
 - Added new stone building tutorials to book
 - Added some small cannibal camps to cave D
 - Light bulbs can now be used from the grab bag and can be added to shelves
 - Player can no longer perform interactions when aiming their weapon
 - Player can no longer open their inventory right at the same time that they trigger a hatch or security door interaction
 - Fish on spears will now fall off when the spear is put away or thrown
 - Set armor racks to only allow a single user to interact with them at a time
 - Added some hot springs to some mountain areas
 - Dismemberment blood splat optimized
 - Visual fixes for cave entrances : shimmering density, seeing through entrance from distance
 - Improved lava impact visual
 - Setup stone beam & pillar electric wire elements
 - Pillar detached placement now works with any combination of log quarters or stones

## Balance
 - Drinking dirty water will now cause a small amount of health damage, boil water or collect in rain collector for clean water
 - Added custom game setting to allow players to toggle the pausing of the world sim when in inventory
 - Pausing in inventory now defaults to false in hard survival
 - Demon boss reduced health and damage it delivers. Some attacks have longer cooldown and increased it’s damage against structures
 - Added additional ammo and health pickups to corridor before gold room
 - Added rifle ammo chance to ammo cases
 - Doubled strength of stone structures
 - Gold Armor now reduces incoming non-demonic damage by 30%

## Fixes
 - Fixed Knight V’s and gliders vanishing in some save games
 - Improved and fixed most cases of artifacts caused by having too many built lights
 - Improved weather occlusion and added a quality option that can be turned up if needed to fix issues of occlusion visually breaking
 - Fix demon boss in overworld rescaling during some attack animations
 - Fix for idle heavy male cannibal audio being audible from far away
 - Removed deprecated option to place wire on standing stick
 - Fixed pillars placed at the corner of two connected stone beams shifting if a stone is removed from one of those beams
 - Fixed incomplete stone beams allowing removal of sibling beams supporting a pillar
 - Fixed dismantling first stone from a complete stone beam not cleaning up links to supported structures until the last stone was removed
 - Fixed stone fake pillars remaining on when disassembling a grounded stone Beam in a specific order
 - Fixed stones allowed to be added to quarter log pillars
 - Fixed using a repair tool on a second story leaning beam causing it to clip into the pillar its leaning against in a specific context
 - Tweaked stone beam visual so lightbulb fits under it
 - Fixed placing a strut underneath a tarp causing the tarp to collapse
 - Fixed dismantling and replacing ramps resulting in broken weather occlusion for those tiles until game was reloaded
 - Improved weather occlusion inside of the beached yachts
 - Fixed being able to remove a pillar supporting a strutted beam if there was a linked beam with a strut on the other end
 - Fixed cut pillar calculations sometimes preventing cutting a half log high pillar into a quarter log high pillar
 - Fixed invalid linking issue when adding a pillar bellow a beam that connects a pillar to a wall
 - Fixed various small building issues with struts and beams
 - Fixed being allowed to cut pillars that are supporting furniture
 - Skinned animals now have head removed
 - Fix player sometimes stuck sliding on ground while in knocked down state
 - Fix "Take Item" Kelvin order causing player to try to equip previous item before opening grab bag
 - Fixed placing a beam between two pillars with a full wall underneath not linking that beam with those pillars properly, which resulted in a beam impossible to dismantle while it has sibling beams linked to it
 - Fixed half log spawned when cutting window sometimes staying stuck in the wall
 - Fixed second stick placement failing when building a fire in a stone fireplace
 - Fixed error spam when placing a leaning beam on beams supported by a wall in some context which would prevent the beam placement
 - Fixed stone fireplaces getting destroyed too easily
 - Fixed struts broken off of a structure not spawning a pickup
 - Fixed picking up a held item while holding multiple stones causing player to only drop one stone pick up
 - Fixed error spam on multiplayer client side any time a trigger touched a log pickup
 - Fixed placing door not orienting it as the inside towards the player consistently
 - Fixed stone structures not affected visually by snow and wetness occlusion volumes
 - Fixed Defensive Wall Gate handles changing orientation when repaired
 - Fixed cooking pots not always having the correct stew after save load
 - Fixed adding the the first item to a storage holder being difficult in some cases
 - Fixed issues with the cooking pot loosing its recipe in certain situations
 - Fixed issue in multiplayer where the cooking pots current volume on the fire was not being updated when another player takes liquid from it
 - Fixed pots with stew turning into water when moved from one fire to another
 - Fix for erroring when trying to pickup any item that is a volume container but does not have a recipe
 - Fix for empty cooking pots getting destroyed when a campfire burns out completely
 - Fixed issue where dumping out the flask or cooking pot would also dump out the other if the other had been equipped before going into the inventory
 - Fixed issue with shelves where some spots on shelves would not save properly
 - Fixed standing fire UI interaction positioned too high
 - Fix for getting into a broken state if the player tries to open the guide book when in inventory
 - Fixed issue with multiplayer clients not being able to send objects on ziplines in both directions
 - Fixed Kelvin sometimes able to get pickups far out of reach
 - Fixed ducks sometimes getting interrupted while going to lake
 - Fixed some activation and render distance inconsistencies on enemies and animals
 - Fixed bug where it was possible to skin animals or creepies through collision
 - In peaceful mode, villages will no longer have a chance to get covered in creepy spittle
 - Chair inside bunker food will no longer show up in the inventory view
 - Fix for having to look away from the zipline for its interaction UI to update
 - Filling a held pot with stew that’s on the fire will now look like the correct stew
 - Fix for opening inventory when the waiting for sleep interaction is active getting player into a bad state
 - Fix for being able to eat from pot and light fire at the same time when loading into a game that had a cooked pot on an unlit fire
 - Amount of stew remaining in a pot on a fire is now synced across multiplayer clients
 - Fix for sometimes getting into a bad state with held items when equipping previously held item at the same time as performing another action like eating
 - Fix for ziplines not getting destroyed when attached to trees that are not LOD 0 or other destructible world objects that are not trees
 - Fixed missing visuals for one of the mushroom pickups
 - Fix for boiling audio continuing to play if the fire that an active cooking pot is sitting on is destroyed
 - Fixed cooking not always taking the satisfied recipe that has the most ingredients
 - Fixed sporadic collision on laptops after they have been broken

## Audio
 - Added all the missing mouseover and pickup events (Action Camera, seeds, lightbulb heads)
 - Updated distances on flare audio attenuation and tuned levels
 - Impact sound effects are now also triggered when they hit other pickups so that a pile of pickups would make sound


## Source
If you are interested in checking out [the source](https://store.steampowered.com/news/app/1326470/view/3689059134033383639) of the information yourself, we encourage you to do so!
We here at Casual Survivors like to make our own archive of the patch notes to help better sort out the information.

## Conclusion
That's all for this major update, Patch - Rifle, head trophies, drivable carts, dedicated servers, frogs and more!

Join us on [Discord](https://discord.gg/ZXp93XsKnN) and talk to us! We are humans after all and we love to talk to other gamers such as yourself. 
