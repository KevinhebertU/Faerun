---
type: Quest
faction: 
location: 
world: Faerun
campaign: Crash of two kingdoms
description: 
date: 2024-02-27
tags: 
aliases: 
Discord link: 
QuestType: 
Act:
---
```dataview
table without id description as Description
where file.name = "Sea creature quest"
```
##### Details

	
### Known place

```dataview 
list where contains(type,"Location") and contains(location,"Sea creature quest")
```
### Involved NPC

### Involved NPC
```dataviewlist from outgoing([[Sea creature quest]])
where contains(type,"NPC")
``` 