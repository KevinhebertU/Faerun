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
date: 2024-02-26
description: Part school and part alehouse, this wide three-story building leans precariously over the street in Eastway. Run by an old, agender martial artist named [[Darbrand Garmult]].While anyone can pay Garmult to study in the House of Mastery, only those who’ve earned membership in the [[Bannerless Legion]] are welcome to socialize and find work here.
tags: 
aliases: 
Discord link: https://discord.com/channels/1171210574437298268/1180235884407300136
Discovered: true
---
# `=this.file.name`
```dataview
table without id description as Description
where file.name = "Garmult's House of Mastery"
```

##### Details

Part school and part alehouse, this wide three-story building leans precariously over the street in Eastway. Run by an old, agender martial artist named [[Darbrand Garmult]].

While anyone can pay Garmult to study in the House of Mastery, only those who’ve earned membership in the [[Bannerless Legion]] are welcome to socialize and find work here. Those who come around looking for such things are challenged to a friendly sparring match in the atrium, usually with Garmult. If they impress Garmult, they’re welcomed with a laugh and a firm handshake, at which point Garmult is happy to hook the new members up with bodyguarding contracts and other work, taking only a nominal finder’s fee. Though not everyone in the Legion is as welcoming of new members, Garmult allows only consensual, nonlethal sparring within their establishment. Few members challenge Garmult’s authority for risk of missing out on future contracts.

Located in the [[Lower city]]

![[Garmult's House of Mastery-20240226235540578.webp]]


>[!info]+ Links(s) 
>>[!info]- NPC(s) 
>>>[!info]+ NPC(s) located in  `=this.file.name`
>>>```dataview
list 
where contains(type,"NPC") and  contains(location,"Garmult's House of Mastery")
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
where contains(type,"Location") and  contains(location,"Garmult's House of Mastery")
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
where contains(type,"Quest") and  contains(location," Garmult's House of Mastery")
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
where contains(type,"LoreEvents") and  contains(location,"Garmult's House of Mastery")
sort file.name asc
>>
>>>[!info]+ Lore Events(s) linked to `=this.file.name`
>>>```dataview
list from outgoing([[]]) or [[]]
where contains(type,"LoreEvents")
sort file.name asc