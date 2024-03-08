---
type: Location
faction: 
location:
  - Faerun
  - Sword Coast
  - Baldur's Gate
  - Lower city
world: Faerun
campaign: Crash of two kingdoms
description: Shaped like a crescent that surrounded the city's Gray Harbor, The Lower City is a chaotic tangle of conjoined, slate-roofed buildings.
date: 2024-02-27
tags: 
aliases: 
Discord link: https://discord.com/channels/1171210574437298268/1171210575859159155
Discovered: true
---
# `=this.file.name`
```dataview
table without id description as Description
where file.name = "Lower city"
```
##### Details

Shaped like a crescent that surrounded the city's [[Gray Harbor]], The Lower City is a chaotic tangle of conjoined, slate-roofed buildings. Built atop sloping bluffs, the narrow cobblestone streets of the Lower City twisted around one another to form the regions city-blocks.

Though lit by street lamps and traversed by hired lantern bearers, the darkened streets are far from safe, and those citizens not running taverns or other late-night establishments tend to lock their doors and bar their colorful window shutters as the river’s dense fog rolls in. Nearly everyone in the Lower City is engaged in some sort of trade. Crime of all sorts is rampant, from petty smuggling to outright robbery and murder. Though the city government tries to curtail this by paying the [[Flaming Fist]] to patrol the streets, the mercenaries sometimes seem more like an occupying army than a true police force, better suited to indiscriminate head-cracking than delicate investigation. As such, while most residents are happy to shout for the [[Flaming Fist|Fist]]  when beset by obvious criminals, they also band together into local crews to better watch each other’s backs and settle more subtle scores. In such an environment, laws are often treated as suggestions, and while most residents are just ordinary folks trying to get by, there’s truth to the old adage that everyone in Baldur’s Gate has a secret to keep.

![[Lower city-20240229140919920.webp]]

>[!info]+ Links(s) 
>>[!info]- NPC(s) 
>>>[!info]+ NPC(s) located in  `=this.file.name`
>>>```dataview
list 
where contains(type,"NPC") and  contains(location,"Lower city")
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
where contains(type,"Location") and  contains(location,"Lower city")
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
where contains(type,"Quest") and  contains(location," Lower city")
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
where contains(type,"LoreEvents") and  contains(location,"Lower city")
sort file.name asc
>>
>>>[!info]+ Lore Events(s) linked to `=this.file.name`
>>>```dataview
list from outgoing([[]]) or [[]]
where contains(type,"LoreEvents")
sort file.name asc