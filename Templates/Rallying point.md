---
type: Rallying point
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
```dataview
table without id description as Description
where file.name = "<% tp.file.title %>"
```
## Description

Placeholder

## Location

Placeholder

## Causes and Effects

Placeholder

## Story

Placeholder

## Relationships

Placeholder

## Background

Placeholder

## Additional Details

Placeholder

<% tp.file.move("Compendium/Rallying Points/"+tp.file.title) %>

>[!info]+ Links(s) 
>>[!info]- NPC(s) 
>>>[!info]+ NPC(s) linked to `=this.file.name`
>>>```dataview
list from outgoing([[]]) or [[]]
where contains(type,"NPC")
sort file.name asc
>
>>[!info]- Location(s) 
>>>[!info]+ Location(s) listed in `=this.file.name`
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