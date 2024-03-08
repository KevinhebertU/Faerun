---
type: Location
faction: 
location:
  - Faerun
  - Sword Coast
world: Faerun
campaign: Crash of two kingdoms
date:
  - 2024-02-26
  - "{ date }": 
description: Baldurs Gate is a large city, just inland from the sea of swords, with a busy harbour and a huge variety of people and shops within its walls. Separated into vastly different areas by these towering walls, there is clear lines between the social classes in the city. Those within the upper walls are mostly safe and protected, with the city guard watching keenly and keeping the peace. Outside the upper city, crime and poverty are rampant, especially in the outer city, where the poorest folk live, as well as those denied entry to the city proper.
tags: 
aliases: 
Discord link: 
Discovered: true
---
# `=this.file.name`
```dataview
table without id description as Description
where file.name = "Baldur's Gate"
```
##### Details




>[!info]+ Links(s) 
>>[!info]- NPC(s) 
>>>[!info]+ NPC(s) located in  `=this.file.name`
>>>```dataview
list 
where contains(type,"NPC") and  contains(location,"Baldur's Gate")
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
where contains(type,"Location") and  contains(location,"Baldur's Gate")
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
where contains(type,"Quest") and  contains(location, "Baldur's Gate")
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
where contains(type,"LoreEvents") and  contains(location,"Baldur's Gate")
sort file.name asc
>>
>>>[!info]+ Lore Events(s) linked to `=this.file.name`
>>>```dataview
list from outgoing([[]]) or [[]]
where contains(type,"LoreEvents")
sort file.name asc