---
type: Location
faction:
  - Jagged Edge Bandits
location:
  - Faerun
  - Sword Coast
  - High Road
  - Jagged Edge Hideaway
world: Faerun
campaign: Crash of two kingdoms
description: The [[Jagged Edge Bandits]]  dug a sprawling network of tunnels in the soft earth beneath the [[High Road]].
date: 2024-03-01
tags: 
aliases: 
Discord link: 
Discovered: false
Approved: true
---
# `=this.file.name`
```dataview
table without id description as Description
where file.name = "Jagged Edge Hideaway"
```
##### Details

The [[Jagged Edge Bandits]]  dug a sprawling network of tunnels in the soft earth beneath the [[High Road]]. Secret entrances allow the goblins to make coordinated strikes and disappear before their victims can organize against them. It contains the bandits’ living quarters, pets, prisoners, and ill-gotten gains.


>[!info]+ Links(s) 
>>[!info]- NPC(s) 
>>>[!info]+ NPC(s) located in  `=this.file.name`
>>>```dataview
list 
where contains(type,"NPC") and  contains(location,"Jagged Edge Hideaway")
sort file.name asc
>>
>>>[!info]+ NPC(s) linked to `=this.file.name`
>>>```dataview
list from outgoing([[]]) or [[]]
where contains(type,"NPC")
sort file.name asc
>
>>[!info]- Location(s) 
>>>[!info]+ Location(s) located in `=this.file.name`
>>>```dataview
list 
where contains(type,"Location") and  contains(location,"Jagged Edge Hideaway")
sort file.name asc
>>
>>>[!info]+ Location(s) linked to `=this.file.name`
>>>```dataview
list from outgoing([[]]) or [[]]
where contains(type,"Location")
sort file.name asc
>
>>[!info]- Quest(s) 
>>>[!info]+ Quest(s) located in `=this.file.name`
>>>```dataview
list 
where contains(type,"Quest") and  contains(location," Jagged Edge Hideaway")
sort file.name asc
>>
>>>[!info]+ Quest(s) linked to `=this.file.name`
>>>```dataview
list from outgoing([[]]) or [[]]
where contains(type,"Quest")
sort file.name asc
>
>>[!info]- Lore Events(s) 
>>>[!info]+ Lore Events(s) located in `=this.file.name`
>>>```dataview
list 
where contains(type,"LoreEvents") and  contains(location,"Jagged Edge Hideaway")
sort file.name asc
>>
>>>[!info]+ Lore Events(s) linked to `=this.file.name`
>>>```dataview
list from outgoing([[]]) or [[]]
where contains(type,"LoreEvents")
sort file.name asc