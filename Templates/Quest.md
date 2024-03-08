---
type: Quest
faction: 
location: 
world: Faerun
campaign: Crash of two kingdoms
description: 
date: <% tp.date.now() %>
tags: 
aliases: 
Discord link: 
bplan cmd: 
QuestType: 
Act: 
bracket: 
bonusinfluence: 
DM: 
Approved:
---
# `=this.file.name`
```dataview
table without id description as Description
where file.name = "<% tp.file.title %>"
```
### Details

<% tp.file.move("Compendium/Quests/"+tp.file.title) %>

### Outcome 

### Rewards
Max reward by bracket
```dataview
table without id
Level,XP,Gold,Items
where file.name = this.bracket
```

>[!info]+ Links(s) 
>>[!info]- NPC(s) 
>>>[!info]+ NPC(s) linked to `=this.file.name`
>>>```dataview
list from outgoing([[]]) or [[]]
where contains(type,"NPC")
sort file.name asc
>
>>[!info]- Location(s) 
>>>[!info]+ Location(s) of `=this.file.name`
>>>```dataview
list 
where contains(type,"Location") and  contains(location,"<% tp.file.title %>")
sort file.name asc
>>
>>>[!info]+ Location(s) linked to `=this.file.name`
>>>```dataview
list from outgoing([[]]) or [[]]
where contains(type,"Location")
sort file.name asc
>
>>[!info]- Quest(s) 
>>>[!info]+ Quest(s) linked to `=this.file.name`
>>>```dataview
list from outgoing([[]]) or [[]]
where contains(type,"Quest")
sort file.name asc
>
>>[!info]- Lore Events(s) 
>>>[!info]+ Lore Events(s) linked to `=this.file.name`
>>>```dataview
list from outgoing([[]]) or [[]]
where contains(type,"LoreEvents")
sort file.name asc
>

