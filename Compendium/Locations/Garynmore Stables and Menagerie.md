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
description: Stables and Menagarie owned by  [[Ubis Garynmor]]
date: 2024-02-27
tags: 
aliases:
  - Garynmor Stables
Discord link: 
Discovered: true
---
# `=this.file.name`
```dataview
table without id description as Description
where file.name = "Garynmore Stables and Menagerie"
```
##### Details

As horses and other beasts of burden aren’t allowed inside the city walls, the [[Outer City]] overflows with stables and hostlers, ranging from muddy pens to barns nicer than most inns. Of these, the largest is Garynmor Stables, which offers the unique benefit of operating locations in both Stonyeyes and Blackgate; those travelers passing through have the option of leaving their beasts on one side of the city and picking them up on the other, after grooms have ferried them around the outside of the walls. The stables are also unusual in their willingness to rent mounts to city residents in need of transportation, cutting down on the need of city dwellers to own their own horses. Yet the true gem setting Garynmor Stables apart is its menagerie.

A former world traveler, [[Ubis Garynmor]] has long had a fascination with exotic beasts, and having already developed the infrastructure to take care of large numbers of ordinary animals, he found it easy enough to expand the scope of his establishment. His menagerie in Stonyeyes contains a variety of rare creatures both mundane and magical, from an aged cockatrice and two wing-clipped hippogriffs to an owlbear.

![[Garynmore Stables and Menagerie-20240229113503305.webp]]
>[!info]+ Links(s) 
>>[!info]- NPC(s) 
>>>[!info]+ NPC(s) located in  `=this.file.name`
>>>```dataview
list 
where contains(type,"NPC") and  contains(location,"Garynmore Stables and Menagerie")
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
where contains(type,"Location") and  contains(location,"Garynmore Stables and Menagerie")
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
where contains(type,"Quest") and  contains(location," Garynmore Stables and Menagerie")
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
where contains(type,"LoreEvents") and  contains(location,"Garynmore Stables and Menagerie")
sort file.name asc
>>
>>>[!info]+ Lore Events(s) linked to `=this.file.name`
>>>```dataview
list from outgoing([[]]) or [[]]
where contains(type,"LoreEvents")
sort file.name asc