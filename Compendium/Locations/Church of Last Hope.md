---
type: Location
faction: 
location:
  - Faerun
  - Sword Coast
  - Baldur's Gate
  - Outer city
  - Church of Last Hope
world: Faerun
campaign: Crash of two kingdoms
description: This combined chapel and asylum in the [[Outer city]]
date: 2024-03-01
tags: 
aliases: 
Discord link: https://discord.com/channels/1171210574437298268/1201971148947198042
Discovered: true
Approved:
---
# `=this.file.name`
```dataview
table without id description as Description
where file.name = "Church of Last Hope"
```
##### Details

This combined chapel and asylum in the Twin Songs neighborhood ([[Outer city]] ) has long offered sanctuary for the depressed and mentally ill. The few attendants ascribe to the faith of no particular god, but extol the virtues of meditation and whatever calm faiths visitors might bring with them.
Under the supervision of [[Mother Aramina]].



>[!info]+ Links(s) 
>>[!info]- NPC(s) 
>>>[!info]+ NPC(s) located in  `=this.file.name`
>>>```dataview
list 
where contains(type,"NPC") and  contains(location,"Church of Last Hope")
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
where contains(type,"Location") and  contains(location,"Church of Last Hope")
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
where contains(type,"Quest") and  contains(location," Church of Last Hope")
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
where contains(type,"LoreEvents") and  contains(location,"Church of Last Hope")
sort file.name asc
>>
>>>[!info]+ Lore Events(s) linked to `=this.file.name`
>>>```dataview
list from outgoing([[]]) or [[]]
where contains(type,"LoreEvents")
sort file.name asc