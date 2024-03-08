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
description: Adventuring shop
date: 2024-02-28
tags: 
aliases:
  - Dancing Axe
Discord link: https://discord.com/channels/1171210574437298268/1178691800790220880
Discovered: true
---
# `=this.file.name`
```dataview
table without id description as Description
where file.name = "Danthelon's Dancing Axe"
```
##### Details

This two-story shop sells everything an adventurer might need, from weapons and armour to rowboats and mobile monster cages. Presiding over the crammed shelves is [[Entharl Danthelon]], a male shield dwarf who claims to have been an adventurer once himself, as evidenced by the magical flying axe that guards his shop at night. Customers are inevitably treated to the story of the grateful elven princess who enchanted the axe for him as a reward for a daring adventure undertaken on her behalf.

![[Danthelon's Dancing Axe-20240228143329305.webp]]


>[!info]+ Links(s) 
>>[!info]- NPC(s) 
>>>[!info]+ NPC(s) located in  `=this.file.name`
>>>```dataview
list 
where contains(type,"NPC") and  contains(location,"Danthelon's Dancing Axe")
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
where contains(type,"Location") and  contains(location,"Danthelon's Dancing Axe")
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
where contains(type,"Quest") and  contains(location, "Danthelon's Dancing Axe")
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
where contains(type,"LoreEvents") and  contains(location,"Danthelon's Dancing Axe")
sort file.name asc
>>
>>>[!info]+ Lore Events(s) linked to `=this.file.name`
>>>```dataview
list from outgoing([[]]) or [[]]
where contains(type,"LoreEvents")
sort file.name asc