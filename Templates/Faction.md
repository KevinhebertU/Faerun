---
type: Faction
faction: 
location: 
world: Faerun
campaign: Crash of two kingdoms
date: <% tp.date.now() %>
description: 
aliases: 
influence:
---
# `=this.file.name`
```dataview
table without id description as Description
where file.name = "<% tp.file.title %>"
```



>[!info]+ Links(s) 
>>[!info]- NPC(s) 
>>>[!info]+ NPC(s) member of  `=this.file.name`
>>>```dataview
list 
where contains(type,"NPC") and  contains(faction,"<% tp.file.title %>")
sort file.name asc
>>
>>>[!info]+ NPC(s) linked to `=this.file.name`
>>>```dataview
list from outgoing([[]]) or [[]]
where contains(type,"NPC")
sort file.name asc
>
>>[!info]- Quest(s) 
>>>[!info]+ Quest(s) involving  `=this.file.name` 
>>>```dataview
list 
where contains(type,"Quest") and  contains(faction, "<% tp.file.title %>")
sort file.name asc
>>
>>>[!info]+ Quest(s) linked to `=this.file.name`
>>>```dataview
list from outgoing([[]]) or [[]]
where contains(type,"Quest")
sort file.name asc
>
>>[!info]- Lore Events(s) 
>>>[!info]+ Lore Events(s) involving `=this.file.name`
>>>```dataview
list 
where contains(type,"LoreEvents") and  contains(faction,"<% tp.file.title %>")
sort file.name asc
>>
>>>[!info]+ Lore Events(s) linked to `=this.file.name`
>>>```dataview
list from outgoing([[]]) or [[]]
where contains(type,"LoreEvents")
sort file.name asc

	<% tp.file.move("Compendium/Factions/"+tp.file.title) %>