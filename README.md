# Farewell

Open sourced game demo: https://www.roblox.com/games/15483397137/Game-Demo-Uncopylocked

**Why I am no longer a part of the USAR community:**

I was removed for being inactive and not implementing fixes, uniform or permission changes, features, and full-set systems in a timely fashion.
I had a 40/60 split with the group owner. The issue was that the group owner had almost zero participation in anything to do with the community. I'll split it into the development perspective and the group management perspective.

Development: Every 6 months or so Zanance (the group owner) would come around and get a sudden spurt of interest in the group again (usually due to a lack of activity on another project startup of his) and come up with some project to lead the group in a new direction. Group chats would be made. 
Game place would be created and worked on for a few days to max two weeks. Zan would typically announce or advertise this project in the discord and set unrealistic release dates before any actual work had even begun. Usually, a few Q&A
sessions would also be hosted for the community to ask questions about what would go into the game and the things they would get to see. Almost all of these promises were never fulfilled. Zan as the group owner, was typically the project lead for these types of things
and would thus be in charge of making sure tasks were being completed in a timely fashion from all components of acquired talent. For the first few days, he would be very responsive and then the development group chat would die down, excitement would wear off, task blockers
would start showing up (usually not being able to find a person to completely make a game's UI), and thus he would lose interest in the project and then so would everyone else.

Group: On the group side of things, Zan fell into the pattern of only interjecting in anything going on if there was a significant issue that required intervention. If somebody in the upper leadership echelon of the group became inactive or wasn't fulfilling their tasks timely all he had to do was pick
from one of the lower ranks, promote them, and then go back to whatever other project he had started or to an inactive off-site state. Usually, as long as there was somebody in the 1st-in-command leadership position under Zan, they'd handle that for him anyway. Zan would very rarely say anything
in the army staff group chat. He wouldn't respond to pings until much later usually either or simply not at all. Along with his development 6-month cycle pattern, it would also occur in the group aspect and he would randomly make sweeping changes to channel structures, delete channels with a lot of history,
rename things, change role colors, etc. This was to get a "fresh start" for the group usually and his way of getting involved.

This gave me, from the development side of things, free reign to do whatever I wanted to do. When no one is pushing you from a leadership perspective to make or do anything you can kind of just make whatever you want whenever you want to. I was here from mid 2019 to the start of 2020. Took a year break. Came back january of 2021 to november of 2023. I took a few commission based payments in 2019 and for the year of 2021. I didn't take a percentage of the group until january of 2022 to november of 2023. Put yourself in my shoes. A group owner is responsible for group leadership management, talent acquisition, marketing, participation at least to a slight degree in the upkeep of ongoing activity in the group, development management in the scrum/agile process, & vision of both game direction & community direction at minimum. Although that sentence is long it is an extremely minimal amount of work and something you can do across multiple projects and groups especially when everything is self-sufficient. When that 'owner' is not there at all for any of those things and is simply sucking up a majority share how incentivized would you be exactly to make or do anything, especially when they are also typically unresponsive to you and may take days to respond to simple things such as simple rank structure changes, bind changes, group description changes, etc. The very reason the holder account was made was so that army staff could make changes and Zan no longer had to because it would take him too long and he would forget. My removal for my lack of being fast enough to implement uniform/permission changes or features when the owner who is taking 60% of the revenue stream was unable to do something he could typically do in 10 seconds from the app on his phone is ironic and laughable.

All that being said, Zan is an honest and fun guy but has yet to prove himself as a capable project leader or group owner. The success chance of anything he works on will always be inhibited until he figures out how to focus, take risks, and stay with a project for the long haul.

### **Goodbye gift to the community:**

As a parting gift to the modern military community, I've released an open-sourced version of game demo which is a knit-based game that developers in the modern military community and the platform as a whole can learn from.
This game contains systems like
- Fully built out Cmdr admin system
- Helicopters
- Character Editor
- Interaction System
- Hosting/Group Ranking System
- Prison/Handcuffs
- Leaderstats for varying and customizable tracking metrics
- Radio/chat system, multiple channels, locked frequencies
- Player manager for spawning, teams, loadouts, tags, platform, etc
- Skydiving and parachuting systems
- Animation and hat control systems
- Lots of different menu interfaces
- Fully loaded data system with an intricate ban system and keybind adaptability
- & lots more, the full version of game demo has over 100k lines of code

Game: https://www.roblox.com/games/15483397137/Game-Demo-Uncopylocked

Knit docs: https://sleitnick.github.io/Knit/
Cmdr docs: https://eryn.io/Cmdr/guide/Setup.html

Adios
- Kronos

# USAR Engine Changelog
These updates are posted into a package within a development place and then posted to all games USAR actively uses. The files are configured so that some things will be disabled in a given place but enabled in others which allows us to post a singular code base to multiple games at the same time. These logs will show what is being changed and the date the update went through as well as patch notes or hotfixes that went along with that given update.

## Game Versions
`Game Demo - v0.5.4`
`Fort Jackson - v0.5.4`
`Parade Grounds - v0.5.3`
`Rosegarden Hall - v0.5.3`
`Delta Archipelago - v0.5.3`

## Changelog

```md
# engine v0.5.4-alpha [11/21/23]
--------------------------
+ Added events panel
+ Added track command to kronos admin

* Changed MPC baton permission from BSOP+ to OG-2+
* Changed M110 firerate: 0.02 > 0.35

* Fixed issue with mobile not being able to deploy parachutes
```

```md
# engine v0.5.3-alpha [11/17/23]
--------------------------
+ Added MPC help request functionality to radio
+ Added 1CAV stuff
+ Added baton for MPC
+ Added spawn protection to MPC spawns

- Removed front gates
```

```md
# engine v0.5.2-alpha [9/24/23]
--------------------------
+ Added PavLocks to classrooms
+ Added 10 second freeze time to people that run into locked pavs
+ Added BCT team to enlisted raiding system
```

```md
# engine v0.5.1-alpha [8/11/23]
--------------------------
+ Added bus system
+ Added equipment modification interface for skydiving & flare control while diving
+ Added prioritizezd key control schema visualization in various player modes

* Changed arrest animation
* Changed hosting panel to be minimizable and draggable
* Changed BCT to log even if no recruits remain as long as the BCT was longer than 10 minutes

* Fixed issue where you could detain yourself
* Fixed issue where you could go to menu if you did it right before being detained
* Fixed issue where you'd still have a gun animation if you were teleported into BCT
* Fixed issue with leaderstats where switching too fast wouldn't remove old data
* Fixed window/slider dragging/resizing issues (i.e. notes) on mobile screens
* Fixed issue with civilian recruits not being able to wear uniforms in BCT
* Fixed issue where completing BCT wouldn't give you a BCT badge
* Fixed a large amount of other bugs with the BCT system (thank you for the reports!)
```

```md
# engine v0.5.0-alpha [8/5/23]
--------------------------
+ Added BCT system (E1's will also now be automatically promoted & civs can partake in BCTs)
+ Added TRADOC status logging connection to USAR (update/15min)
+ Added server uptime on main menu
+ Added quality of life changes to kronos admin PM's
+ Added log integration into kronos admin logs for hosting/pavs/mpc handler
+ Added new notification type
+ Added 2 faces

* Changed/upgraded a few of the gun models and their sounds
* Changed guns to be able to kill E1's not in BCT
* Changed E1's to be godded while in BCT
* Changed cinematic mode to disable on UI based interactions
* Changed/updated Army Affairs, NCOs, & other admin perms
* Changed locked pavs to allow owner to walk in/out

* Fixed issue where you could hold guns while doing pull ups
* Fixed issue where you could still see prompts with pull up bars
* Fixed issue where people could respawn themselves if detained
* Fixed/updated badges
* Fixed security issues with MPC updating a player's clearance
* Fixed security issue where a player could update their appearance from anywhere
* Fixed auth issue with helicopters where they wouldn't despawn properly
* Fixed issue with pullups bars where you could stay in the up position after exitting
* Fixed issue with cinematic mode where dying wouldn't allow you to respawn
* Fixed issue where tools wouldn't disappear in cinematic mode
* Fixed issue where auth check wasn't being ran on all interaction types
```

```md
# engine v0.4.1-alpha [5/29/23]
--------------------------
+ Added PavLock system
+ Added more shirts

* Changed starting an obby with an interaction to automatically starting when you enter obby
* Changed leaderboards to retain KOs/WOs upon rejoining a server to stop intentionally resetting kills

* Fixed issue where players didn't have permission to run private server commands even though they had the correct admin level
* Fixed issue where `Hard` obby had the wrong finishing checkpoint and thus wouldn't update leaderstats
* Fixed issue where the three basic t-shirts would default to the white t-shirt
* Fixed issue where people resetting while in prison would give them access to weapons again
* Fixed issue where falling into the void would bug the character
* Attempted fix on `Kills` global leaderstat resetting
* Attempted fix on pull up interaction breaking
```

```md
# engine v0.4.0-alpha [5/27/23]
--------------------------
+ Added pull up interaction
+ Added indicator on leaderboard icons when a player is off duty
+ Added obby system
+ Added ranked leaderboards that tracks global/server stats
+ Added new cards when selecting a player on the leaderboard
+ Added 3 second reset timer that stops when you start to move
+ Added picture mode button
+ Added icon tip text to buttons on the top of the screen
+ Added no-raider zones to roofs & BCT area
+ Added red beam of light to raiders on kill streaks that becomes more opaque with more kills
+ Added RRAU to skydiving perms
+ Added 'Moderator' permission to private server owners - [Access key: backslash]
+ Added numbers to each pav
+ Added support for AFA, CIMT, CAC, & RRC divisions
+ Added various shirts/pants courtesy of urmom + a few clothing permission changes

* Changed notepad feature to create new separate notepads [1st one opened is the saveable one]
* Changed gate on airfield
* Changed skydiving & flying/spawning perms to anyone on private servers
* Changed radio to maintain its current state instead of reopening every time you respawn
* Changed a lot of permissions with admin commands depending on whether or not you are in a PS

* Fixed issue where if a user dies while being led then MPC can no longer detain and when the user leaves the game they'd get auto arrested
* Fixed issue where time remaining on a sentence would reset when you left
* Fixed issue where user wouldn't get auto-arrested when leaving while detained
* Fixed issue where player wouldn't be fully undetained if they died while detained
* Fixed issue where you couldn't buy rank passes
* Fixed return to base from plane issue
* Fixed issue with seats not being in planes
* Fixed issue where jumping out of a seat with a static parachute would remove it
```

```md
# engine v0.3.2-alpha [2/14/23]
--------------------------
+ Added ability to go off-duty for personnel in commands
+ Added notes feature [saves/1500 char limit]
+ Added system message notification in the radio to all MPC/HQ+ personnel when an arrest is made and when someone posts bail (system knows the channel and freq youre on)
+ Added enlisted raiding capture where enlisted raiders with 5+ personnel kills will be switched to the raiding team
+ Added new female hairstyle & added new hair color (grey) [@Belly]
+ Added assault pack [@Belly]

* Updated E2 rank pass to new system and automated E5/E7 passes as well
* Changed radio system to automatically connect personnel in commands to the lowest frequency out of their commands locked frequencies on Ch1
* Fixed civilians being able to skydive while in VIP mode
* Fixed civilians being able to buy guns from the weapon crate while in VIP mode
* Fixed RichText abuse in radio by sanitizing input
* Fixed icon angle of different editor items for a clearer view
```

```md
# engine v0.3.1-alpha [8/19/22]
--------------------------
+ Added chatbar highlight when you select it

* Fixed issue where pasting text with multiple lines wouldn't send message properly
* Fixed text cursor visibility on chat
* Fixed guns not replicating sounds
* Fixed issue where leaving while detained wouldn't be logged in criminal database
* Fixed highlight issue with selecting characters
* Fixed MPC being able to lead multiple people at once
```

```md
# engine v0.3.0-alpha [8/9/22]
--------------------------
+ Added radio system & radio system gamepass
+ Added new prison system & bail out system
+ Added new cuff system
+ Added new criminal database interaction
+ Added player-to-player interactions
+ Added new tradoc whiteboard system interaction
+ Added skip bct pass
+ Added binds for CCTV [Q,E] & [A,D]
+ Added binds for base hat controls [V + HJ]
+ Added hats, 2 hair, 1 face
+ Added snake minigame
+ Added wall around BCT area

* Changed skydiving back to specific groups, >>> 82nd, 101st, ASOC, O9+ as well as those with gamepass, (Free on VIP servers)
* Changed auth levels, mpc > 4, tradoc > 3

* Fixed issue where being seated stopped you from interacting with CCTV
* Fixed issue where you couldn't look around when right clicking on the leaderboard
* Fixed issue where weapons crate would give you a baton as one of the random choices
* Fixed issue with profile data failing to load
* Fixed issue where unauthed people hopping into empty helis wouldn't allow them to despawn properly
* Fixed issue where VIP's wouldn't respawn after resetting
* Fixed multiple issues with doors not replicating properly
```

```md
# engine v0.2.0-alpha [6/7/22]
--------------------------
+ Added mobile sprinting & updated mobile shiftlock icon to new icons
+ Added security camera CCTV interaction
+ Added perk interaction for raider entrance, civilian skydiving, gun roll crates, & VIP gamepass
+ Added equip parachute interaction for static & regular parachutes
+ Added new static line parachute variant that requires a connected line to deploy
+ Added C-17 (replaces the C-160) & made all exits/lights/seats functional
+ Added AH-64 Apache & AH-6 Little Bird attack variants
+ Added physical interactable NPCs
+ Added dialogue system that supports node based communication and internal functions
+ Added cutscenes & music into loading sequence and bindable to play/start
+ Added main menu
+ Added a death screen that prompts you to respawn or return to menu
+ Added disclaimer for customs in the character editor (customs can only be uploaded by QMC)
+ Added skin color picker in select QuickApply interactions
+ Added new leaderboard
+ Added animations for sitting in vehicles
+ Added animation radial menu
+ Added hat functionality radial menu
+ Added new mpc building (replaces)
+ Added new HQ building (replaces)
+ Added new tradoc barracks (replaces)
+ Added new civilian entrance with rehauled buildings & new restaurant
+ Added hair (4 styles, 4 colors)
+ Added 3 faces, 4 vests, 5 civ shirts, 4 hats, & piT ViPErS

* Rewrote skydiving/parachuting mechanics & mobile control implementation across a variety of interfaces and control systems
* Changed front gate to add an additional building for VIP bypass lane
* Changed OCPs to OCPs with 'US Army' on the nametape & updated OCPs within store
* Changed heli permissions to wings & bstaff+ within 101st, NS & bstaff+ within SOAR
* Changed helicopters to be completely collidable to mitigate flipping
* Changed/updated PCs texturing and rank tab(@Belly)
* Changed/updated a few OCPs & added CID OCPs
* Fixed issue where skin color would flicker between the default and your actual skin tone when updating character
* Fixed issue where cached custom shirt requests wouldn't update to client
* Fixed issue where players meeting multiple asset auth requirements would get the same item more than once
* Fixed issue where helicopters wouldn't despawn (possible)
* Fixed issue where you could open the spawn vehicle UI when you were in a helicopter
* Fixed issue where camera would break if you were in a passenger seat of a helicopter
* Fixed issue where if you were sitting and you spawned a helicopter the pilot sequence wouldn't initialize properly
* Fixed issue where mobile shiftlock would dissapear after death and never reappear
* Fixed issue where players were able to get into the airfield thru a variety of methods
* Fixed issue where people that would leave a division would be wearing items they don't have access to anymore
* Fixed issue where people could still rotate their character after they died or ragdolled
* Fixed issue where tools and UI mobile controls elements would be on screen during load-time
* Fixed issue where an inventory would have multiple of the same tool if the user also owned the gamepass version
* Fixed issue where you could interact with things while dead
* Fixed a few issues with the prison system (not sure if the prison bug still occurs, at the very least the timer won't reset to an hour anymore)
* Fixed arrest logs (discord blocked traffic from roblox awhile back)
```

```md
# engine v0.1.3-prealpha [2/26/22]
--------------------------
+ Added 8 hats, 2 torso pieces, 1 accessory
+ Added customs integration into character editor
+ Added temporary female hair next to some editors as it was highly requested as hair is not ready for the editor yet
+ Added a name indicator for pilots on the side of helicopters to ensure players are held accountable for intentionally crashing
+ Added game server location indicator
+ Added mobile shiftlock
+ Added security office in prep of the next update

* Fixed issue with HTTP requests holding the load screen
* Fixed issue with couches not having seating
* Enabled platform icons on the backend and fixed location on tag in a offset/scale conversion next to name (icon is very transparent)
* Modified player allocation so that division CSMs are now HQ and HQ members are also identifiable by division
* Airfield doors auth changed to level 3, added support for changing specific subdivisions auth levels
* Slightly buffed SCAR-H
```

```md
# engine v0.1.2-prealpha [12/28/21]
--------------------------
+ Added regions for ambience toggling, room indicator, & weather toggling
+ Added lighting to obbies
+ Added CTRG team & adjusted QMC team back into the USAR team
+ Added walls around gate to prevent civilians from entering and restructured gates/entry
+ Added 'safety' to guns for mobile camera rotating reasons(button on mobile, X on PC)
+ Added seat interaction to all in-game seats
+ Added 'Quick Apply' clothing interaction that changes your entire wardrobe when you click update (primarily for BCT)
+ Added door interaction to all doors in MPC HQ & office building
+ Added whitelist functionality to players trying to pilot a helicopter instead of only spawning at the interaction point
+ Added ability to click on a character to select them to see their divisional rank if they have one

* Re-enabled cuffs
* Separated ASOC & SOAR spawns (ASOC will no longer spawn in the airfield)
* Various hats adjusted and recentered on head
* Fixed authorization issues on all doors and adjusted all of them to their appropriate levels
* Fixed players in helicopter not dieing on crash
* Moved raider spawn closer to the gate & fixed raiders not respawning properly
* Fixed not being able to sprint with a gun out
* Fixed players being able to glitch out of prison & added check to ensure exploiters can't teleport out
* Fixed players being able to sprint out of cuffs
* Fixed mag removal security issue
* Fixed issue where players wearing vests couldn't be shot in the torso
* Fixed issue where exitting an interactable menu your backpack wouldn't become visible again
* Fixed issue where people couldn't kill if you if you stood in a bush
* Fixed non-MPC players being able to wear MPC vest & other item permissions
* Fixed issue where players would be given the same weapon more than once if they owned the gamepass counterpart for it
* Fixed baton input so players on PC can actually swing the tool, mobile input method updated as well
* Fixed UI scaling issues with the cuffs as well as players being able to jump out of them
* Fixed security issue with helicopters
* Fixed issue where holding the sprint key and standing still would still deplete stamina
* Fixed issue with guns where sprinting once wouldn't allow you to crouch
* Fixed issue with prison system where upon rejoining you wouldn't spawn inside of cell / remaining time would be messed up
* Fixed issue with cuffs where having another prompt show up would undetain a player
* Fixed issue with the silent patch that allowed the user to sprint forever
* Fixed issue where arresting someone that is seated would teleport the seat to the prison

- Disabled forcefield on spawn
- Disabled bird ambient sound
- Disabled custom footsteps
- Disabled !rejoin command because data can't unload fast enough causing client to break on rejoin
- Removed minimap
```


```md
# engine v0.1.1-prealpha [10/25/21]
--------------------------
+ Team assignment, nametags, spawning rewrite
+ Interactions: doors, flags, lights, seats, character editor
+ Day/night cycle, floodlight on the parade fields
+ Regions, ambient noise, footsteps, & region indicator in the top-left
+ Health/stamina, ragdoll
+ Black chat, & a popular request to increase viewing distance
+ Character saving and automatic refit of whatever was worn last when you rejoin or respawn
+ A few character items that aren't yet available in FJ
```
