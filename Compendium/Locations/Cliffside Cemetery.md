---
type: Location
faction: 
location:
  - Faerun
  - Sword Coast
  - Baldur's Gate
  - Outer city
world: Faerun
campaign: Crash of two kingdoms
description: Largest cemetery for the lower and outer city.
date: 2024-03-01
tags: 
aliases: 
Discord link: https://discord.com/channels/1171210574437298268/1178683320419233823
Discovered: true
Approved: true
---
# `=this.file.name`
```dataview
table without id description as Description
where file.name = "Cliffside Cemetery"
```
##### Details

The value of land and sheer population density in [[Baldur's Gate]]   means only the wealthiest patriars can afford to bury their dead within the city, interring them in catacombs beneath the city’s temples or in family crypts on their own grounds. For everyone else, there’s the ignoble Shrine of the Suffering or the scattering of cemeteries outside the city. The largest of the latter is Cliffside Cemetery, located in the Tumbledown  neighborhood ([[Outer city]]) and employing many local residents as gravediggers, stonemasons, morticians, and professional mourners. Long ago, the graveyard was an empty estate owned by the mercantile [[Szarr family]], with only a few family crypts near the cliffs. When a business rival murdered the entire family in their beds, no one was eager to move into their former manor, and the city decided to turn the estate into a single massive graveyard that acts as the primary repository for the city’s dead. The cemetery also deals with near constant problems from undead, ghouls, skeletons, ghosts and wraiths. Putting down such threats before they can prey on citizens is the Gravemakers’ primary job, and though rightfully proud of their prowess, their leader [[Leone Wen]] is always looking for fresh recruits or contractors to join them in their crusade.

![[Cliffside Cemetery-20240301112159093.webp]]

>[!info]+ Links(s) 
>>[!info]- NPC(s) 
>>>[!info]+ NPC(s) located in  `=this.file.name`
>>>```dataview
list 
where contains(type,"NPC") and  contains(location,"Cliffside Cemetery")
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
where contains(type,"Location") and  contains(location,"Cliffside Cemetery")
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
where contains(type,"Quest") and  contains(location," Cliffside Cemetery")
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
where contains(type,"LoreEvents") and  contains(location,"Cliffside Cemetery")
sort file.name asc
>>
>>>[!info]+ Lore Events(s) linked to `=this.file.name`
>>>```dataview
list from outgoing([[]]) or [[]]
where contains(type,"LoreEvents")
sort file.name asc