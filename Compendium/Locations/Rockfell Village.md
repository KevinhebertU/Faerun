---
type: Location
faction: 
location:
  - Faerun
  - Sword Coast
  - Rockfell Village
world: Faerun
campaign: Crash of two kingdoms
description: Insert Description here
date: 2024-02-27
tags: 
aliases: 
Discord link:
---
```dataview
table without id description as Description
where file.name = "Rockfell Village"
```
##### Details

	
### Known place

```dataview 
list where contains(type,"Location") and contains(location,"Rockfell Village")
```
### Known NPC

```dataview
list  
where contains(type,"NPC") and contains(location,"Rockfell Village")
```