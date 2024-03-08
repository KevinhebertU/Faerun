---
type: Quest
faction:
  - Bannerless Legion
location:
  - Faerun
  - Sword Coast
  - Rockfell
world: Faerun
campaign: Crash of two kingdoms
description: Get someone who is brainwashed  from [[Rockfell]] Village
date: 2024-02-27
tags: 
aliases: 
Discord link: 
QuestType: 
Act: 
bracket: Bracket 1
---
```dataview
table without id description as Description
where file.name = "Get someone out who is brainwashed"
```
##### Details

	
Get someone who is brainwashed  from [[Rockfell]]

	
### Involved Location(s)

```dataview
list from outgoing([[Get someone out who is brainwashed]])
where contains(type,"Location")
``` 
### Involved NPC(s)
```dataview
list from outgoing([[Get someone out who is brainwashed]])
where contains(type,"NPC")
``` 
### Rewards
Max reward by tier
```dataview
table without id
Level,XP,Gold,Items
where file.name = this.bracket
```
