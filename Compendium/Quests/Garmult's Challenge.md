---
type: Quest
faction: 
location:
  - Garmult's House of Mastery
world: Faerun
campaign: Crash of two kingdoms
date: 2024-02-27
description: Entrance trial to join the [[Bannerless Legion]] agaisnt [[Darbrand Garmult|Garmult]]
tags: 
aliases: 
Discord link: https://discord.com/channels/1171210574437298268/1192899095078109395
bplan cmd: "!bplan begin garmult"
QuestType: Errands
Act: 1
bracket: Bracket 1
bonusinfluence:
---
```dataview
table without id description as Description
where file.name = "Garmult's Challenge"
```
### Details

To join the[[ Bannerless Legion]], characters must complete a challenge against [[Darbrand Garmult|Garmult]] . Realistically, characters at level 3 won't be able to defeat him. Instead, they must impress Garmult to complete the challenge. On paper, characters must get 3 points (1 point for each hit on Garmult) or survive  rounds of combat, but they must do something creative to impress Garmult. This is to encourage players to use other abilities in combats and think outside the box. Garmults stat block is a Gladiator, though in the fight he will use a wooden training weapon so no damage is done


### Outcome 

### Rewards
Max reward by bracket
```dataview
table without id
Level,XP,Gold,Items
where file.name = this.bracket
```
XP - 250 
DTD - 5
Renown - 1 Baldurs Gate 
Other - Access to members only areas of the bannerless legion and additional quests

### links
>[!info]+ Involved Location(s)
>```dataview
list from outgoing([[Garmult's Challenge]])
where contains(type,"Location")

>[!info]+ Involved NPC(s) 
>```dataview
list from outgoing([[Garmult's Challenge]])
where contains(type,"NPC")

>[!info]+  Involved lore event(s)
>```dataview
list from outgoing([[Garmult's Challenge]])
where contains(type,"LoreEvents")