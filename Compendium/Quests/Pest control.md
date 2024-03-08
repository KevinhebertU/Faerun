---
type: Quest
faction: 
location:
  - Faerun
  - Sword Coast
  - Baldur's Gate
  - Forests
  - Garynmore Stables and Menagerie
world: Faerun
campaign: Crash of two kingdoms
description: "[[Pest control#^test]]"
date: 2024-02-27
tags: 
aliases:
  - Stable sidequest
Discord link: https://discord.com/channels/1171210574437298268/1206254091890589697
QuestType: Errands
Act: 1
bracket: Bracket 1
bonusinfluence:
---

```dataview
table without id description as Description
where file.name = "Pest control 1"
```
### Details

Word of the aggressive animals in the [[Forests]] outside Baldurs gate has spread and the authorities have asked [[Darbrand Garmult|Garmult]]   to send a team to deal with them.

Adventurers wanted to deal with large aggressive animals in the forests! Reward for each animal taken care of. Larger reward for finding and dealing with the source of the problem! 

If an animal is rescued it can be taken to [[Garynmore Stables and Menagerie]] to [[Ubis Garynmor]]


### Outcome 

### Rewards
Max reward by bracket
```dataview
table without id
Level,XP,Gold,Items
where file.name = this.bracket
```
### Additional info
>[!info]+ Involved Location(s)
>```dataview
list from outgoing([[Pest control 1]])
where contains(type,"Location")

>[!info]+ Involved NPC(s) 
>```dataview
list from outgoing([[Pest control 1]])
where contains(type,"NPC")

>[!info]+  Involved lore event(s)
>```dataview
list from outgoing([[Pest control 1]])
where contains(type,"LoreEvents")
