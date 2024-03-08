---
type: Location
faction: 
location:
  - Faerun
  - Sword Coast
  - Baldur's Gate
  - Gray Harbor
world: Faerun
campaign: Crash of two kingdoms
description: The entirety of the [[Lower City]] is wrapped around this harbor, which is the deepest and one of the busiest ports in all of Faerûn
date: 2024-03-01
tags: 
aliases: 
Discord link: https://discord.com/channels/1171210574437298268/1171210575859159158
Discovered: true
Approved:
---
# `=this.file.name`
```dataview
table without id description as Description
where file.name = "Gray Harbor"
```
##### Details

The entirety of the [[Lower City]] is wrapped around this harbor, which is the deepest and one of the busiest ports in all of Faerûn. Just about any kind of goods—legal and otherwise—can be found flowing through this port, if you have the gold and know where to look, that is.


![[Gray Harbor-20240301145940239.webp]]


>[!info]+ Links(s) 
>>[!info]- NPC(s) 
>>>[!info]+ NPC(s) located in  `=this.file.name`
>>>```dataview
list 
where contains(type,"NPC") and  contains(location,"Gray Harbor")
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
where contains(type,"Location") and  contains(location,"Gray Harbor")
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
where contains(type,"Quest") and  contains(location," Gray Harbor")
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
where contains(type,"LoreEvents") and  contains(location,"Gray Harbor")
sort file.name asc
>>
>>>[!info]+ Lore Events(s) linked to `=this.file.name`
>>>```dataview
list from outgoing([[]]) or [[]]
where contains(type,"LoreEvents")
sort file.name asc