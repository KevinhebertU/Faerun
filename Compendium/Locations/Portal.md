---
type: Location
faction: 
location:
  - Faerun
  - Sword Coast
  - Baldur's Gate
world: Faerun
campaign: Crash of two kingdoms
description: A damaged and abandoned portal sits in an empty clearing just outside of the Stonyeyes district of the [[Outer city]]. Lying dormant for decades now, the only activity is the occasional flicker. Although it's mostly forgotten, it does receive the occasional visitor.
date: 2024-02-27
tags: 
aliases: 
Discord link: https://discord.com/channels/1171210574437298268/1171210575859159152
---
```dataview
table without id description as Description
where file.name = "Portal"
```
##### Details

A damaged and abandoned portal sits in an empty clearing just outside of the Stonyeyes district of the [[Outer city]]. Lying dormant for decades now, the only activity is the occasional flicker. Although it's mostly forgotten, it does receive the occasional visitor.
### Known place

```dataview 
list where contains(type,"Location") and contains(location,"Portal")
```
### Known NPC

```dataview
list  
where contains(type,"NPC") and contains(location,"Portal")
```