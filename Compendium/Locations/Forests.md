---
type: Location
faction: 
location:
  - Faerun
  - Sword Coast
  - Baldur's Gate
world: Faerun
campaign: Crash of two kingdoms
description: The forest outside of [[Baldur's Gate]]  is the perfect place to hunt, forage and fish. Be wary of going too deep in, there are unseen dangers lurking in the shadows.
date: 2024-02-27
tags: 
aliases: 
Discord link: 
Discovered: true
---

# `=this.file.name`
```dataview
table without id description as Description
where file.name = "Forests"
```
##### Details

The forest outside of [[Baldur's Gate]]  is the perfect place to hunt, forage and fish. Be wary of going too deep in, there are unseen dangers lurking in the shadows.

![[Forests-20240227090151832.webp]]

>[!info]+ Links(s) 
>>[!info]- NPC(s) 
>>>[!info]+ NPC(s) located in  `=this.file.name`
>>>```dataview
list 
where contains(type,"NPC") and  contains(location,"Forests")
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
where contains(type,"Location") and  contains(location,"Forests")
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
where contains(type,"Quest") and  contains(location," Forests")
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
where contains(type,"LoreEvents") and  contains(location,"Forests")
sort file.name asc
>>
>>>[!info]+ Lore Events(s) linked to `=this.file.name`
>>>```dataview
list from outgoing([[]]) or [[]]
where contains(type,"LoreEvents")
sort file.name asc