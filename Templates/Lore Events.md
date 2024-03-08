---
type: LoreEvents
faction: 
location: 
world: Faerun
campaign: Crash of two kingdoms
description: 
date: <% tp.date.now() %>
tags: 
aliases: 
Discord link: 
Act: 
tier:
---
# `=this.file.name`
## Overview 

Placeholder
<% tp.file.move("Compendium/Lore Events/"+tp.file.title) %>

## Storyline Elements

Placeholder

## Background

Placeholder


## Additional Details


>[!info]+ Links(s) 
>>[!info]- NPC(s) 
>>>[!info]+ NPC(s) linked to `=this.file.name`
>>>```dataview
list from outgoing([[]]) or [[]]
where contains(type,"NPC")
sort file.name asc
>
>>[!info]- Location(s) 
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