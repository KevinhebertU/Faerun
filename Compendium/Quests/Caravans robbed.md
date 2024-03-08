---
type: Quest
faction:
  - Jagged Edge Bandits
location: 
world: Faerun
campaign: Crash of two kingdoms
description: "[[Goblin Queen Bargnot]]  , Scourge of the High Road, leads the Jagged Edge Bandits in pillaging caravans"
date: 2024-03-01
tags: 
aliases: 
Discord link: https://discord.com/channels/1171210574437298268/1208285925101015051
bplan cmd: 
QuestType: Secondary
Act: 1
bracket: Bracket 1
bonusinfluence: 
DM:
  - Balgur
Approved: true
---
# `=this.file.name`
```dataview
table without id description as Description
where file.name = "Caravans robbed"
```
### Details
[[Goblin Queen Bargnot]]  , Scourge of the High Road, leads the Jagged Edge Bandits in pillaging caravans. The party will h

**BOUNTY! Queen Bargnot** The merchants have put out a bounty on Queen Bargnot offering 500 gp to any band of adventurers who can capture or kill the bandit queen. She has been leading a group of goblins raiding caravans along the high road. Those interested can seek out [[Entharl Danthelon ]]of [[Danthelon's Dancing Axe]] in the [[Outer City]] for more information.

### Outcome 

### Rewards
Max reward by bracket
```dataview
table without id
Level,XP,Gold,Items
where file.name = this.bracket
```

- 500 gp bounty on [[Goblin Queen Bargnot]] 
- 135 gp
- Trade goods worth 155 gp (can be sold for half, or full if they killed the Queen)
- 5 [[silvered-ammunition|Silvered Arrow]] 
- 1 [[potion-of-healing|Potion of Healing]] 
- Glow in dark dice worth 3 gp
- [[bag-of-holding|Bag of Holding]] 
- [[potion-of-climbing|Potion of Climbing]] 
- [[cure-wounds|Cure Wounds]] spell scroll
- [[lesser-restoration|Lesser Restoration]]  spell scroll
- [[Glowing poison recipe]]
- [[Monacle of Secrets]]

XP : 855 per char


>[!info]+ Links(s) 
>>[!info]- NPC(s) 
>>>[!info]+ NPC(s) linked to `=this.file.name`
>>>```dataview
list from outgoing([[]]) or [[]]
where contains(type,"NPC")
sort file.name asc
>
>>[!info]- Location(s) 
>>>[!info]+ Location(s) of `=this.file.name`
>>>```dataview
list 
where contains(type,"Location") and  contains(location,"Caravans robbed")
sort file.name asc
>>
>>>[!info]+ Location(s) linked to `=this.file.name`
>>>```dataview
list from outgoing([[]]) or [[]]
where contains(type,"Location")
sort file.name asc
>
>>[!info]- Quest(s) 
>>>[!info]+ Quest(s) linked to `=this.file.name`
>>>```dataview
list from outgoing([[]]) or [[]]
where contains(type,"Quest")
sort file.name asc
>
>>[!info]- Lore Events(s) 
>>>[!info]+ Lore Events(s) linked to `=this.file.name`
>>>```dataview
list from outgoing([[]]) or [[]]
where contains(type,"LoreEvents")
sort file.name asc
>

