---
type: NPC
faction:
  - Jagged Edge Bandits
location:
  - Faerun
  - Sword Coast
  - High Road
  - Jagged Edge Hideaway
world: Faerun
campaign: Crash of two kingdoms
description: Queen Bargnot, Scourge of the High Road, leads the [[Jagged Edge Bandits]] in pillaging caravans.
race: Goblin
gender: Female
sex: Female
pronouns: 
class: 
date: 2024-02-29
aliases:
  - Goblin Queen
  - Scourge of the  High Road
command: "!npc"
Personality: 
Role: 
CultInfluence:
---




> [!infobox]
> # `=this.file.name`
> ![[Goblin Queen Bargnot-20240301110822150.webp|cover hsmall]]
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

Queen Bargnot, Scourge of the High Road, leads the [[Jagged Edge Bandits]] in pillaging caravans. Before her rise, the goblins struggled, attacking only the weakest travelers in unorganized strikes. When she killed her boss and became the band’s self-proclaimed queen, everything changed. 


> [!info] Statblock
> ```statblock
> monster: Queen Bargnot
> columns: 2
> ```

>[!info]+ Links
>>[!info]+ Involved Location(s)
>>```dataview
list from outgoing([[Goblin Queen]]) or [[]]
where contains(type,"Location")
>
>>[!info]+ Involved NPC(s) 
>>```dataview
list from outgoing([[Goblin Queen]]) or [[]]
where contains(type,"NPC")
>
>>[!info]+  Involved lore event(s)
>>```dataview
list from outgoing([[Goblin Queen]]) or [[]]
where contains(type,"LoreEvents")
>
>>[!info]+  Involved quest(s)
>>```dataview
list from outgoing([[Goblin Queen]]) or [[]]
where contains(type,"Quest")
