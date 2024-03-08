---
type: NPC
faction:
  - Gravemakers
location:
  - Faerun
  - Sword Coast
  - Baldur's Gate
  - Outer city
  - Cliffside Cemetery
world: Faerun
campaign: Crash of two kingdoms
description: Gravemakers leader Leone Wen, a lawful good female human knight and servant of Torm, is always looking for fresh recruits or contractors to join them in their crusade. The crew operates out of the  [[Cliffside Cemetery]]
race: Human
gender: Female
sex: Female
pronouns:
  - She
  - Her
class: 
date: 2024-03-01
aliases:
  - Leone
command: "!npc leone"
Personality: No nonsense
Role: Gravemaker leade
CultInfluence: 
Discovered:
---


> [!infobox]
> # `=this.file.name`
> ![[Leone Wen-20240301112537277.webp|cover hsmall]]
> ###### Basic Information
> Type |  Stat |
> ---|---|
> Home | `=reverse(this.location)[0]` |
> Faction(s) | `=this.faction` |
> Sex | `=this.sex` |
> Gender | `=this.gender` |
> Pronouns | `=this.pronouns` |
> Race | `=this.race` |
> Age | `=this.age` |
> Condition | Healthy |
> ###### Rules Info
> Type |  Stat |
> ---|---|
> Class | `=this.class` |
> Role | `=this.role` |
> Personality | `=this.Personality` |
> Avrae command | `=this.command` |

# `=this.file.name`
## Profile

[[Gravemakers]] leader Leone Wen, a lawful good female human knight and servant of Torm, is always looking for fresh recruits or contractors to join them in their crusade. The crew operates out of the  [[Cliffside Cemetery]] 


> [!info] Statblock
> ```statblock
> name: Individual
> monster: Commoner
> columns: 1
> ```

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