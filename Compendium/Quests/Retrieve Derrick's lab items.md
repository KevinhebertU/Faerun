---
type: Quest
faction: 
location:
  - Faerun
  - Sword Coast
  - Baldur's Gate
  - Portal
world: Faerun
campaign: Crash of two kingdoms
description: "[[Derrick]] will contract the players to retrieve his laboratory equipement"
date: 2024-02-27
tags: 
aliases: 
Discord link:
---
```dataview
table without id description as Description
where file.name = "Retrieve Derrick's lab items"
```
##### Details

[[Derrick]] will contract the players to retrieve his laboratory equipement 
### Known place

```dataview 
list where contains(type,"Location") and contains(location,"Retrieve Derrick's lab items")
```
### Known NPC

```dataview
list  
where contains(type,"NPC") and contains(location,"Retrieve Derrick's lab items")
```