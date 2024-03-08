---
type: NPC
faction:
  - Bannerless Legion
location:
  - Faerun
  - Sword Coast
  - Baldur's Gate
  - Lower city
  - Garmult's House of Mastery
world: Faerun
campaign: Crash of two kingdoms
description: Proprietor of  [[Garmult's House of Mastery]] and leader of the [[Bannerless Legion]]
race: Human
sex: Male
gender: Agender
pronouns:
  - She
  - He
  - They
class: Gladiator
date: 2024-02-26
aliases:
  - Garmult
command: "!npc darbrand"
Personality: Welcoming
Role: Leader of Bannerless legion
CultInfluence:
---

> [!infobox]
> # `=this.file.name`
> ![[Darbrand Garmult-20240226235728127.webp|cover hsmall]]
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

```dataview
table without id description as Description
where file.name = "Darbrand Garmult"
```
# `=this.file.name`
## Profile

Proprietor of  [[Garmult's House of Mastery]] 

Run by an old, agender martial artist, the [[Garmult's House of Mastery]]  offers both martial training of all sorts for the city’s would-be warriors and a central hangout for the [[Bannerless Legion]] crew. Garmult assists crew leader [[Dezri “Guts” Lamouer]] in matching clients with mercenaries. They also hire members to teach classes in the building’s open-air atrium while other members lounge on the overlooking balconies. At any given time, there’s usually multiple veteran mercenaries here swapping stories and waiting for contracts.


> [!info] Statblock
> ```statblock
> name: Darbrand Garmult 
> monster: Gladiator
> columns: 2
> ```


>[!info]+ Links
>>[!info]+ Involved Location(s)
>>```dataview
list from outgoing([[Darbrand Garmult]]) or [[]]
where contains(type,"Location")
>
>>[!info]+ Involved NPC(s) 
>>```dataview
list from outgoing([[Darbrand Garmult]]) or [[]]
where contains(type,"NPC")
>
>>[!info]+  Involved lore event(s)
>>```dataview
list from outgoing([[Darbrand Garmult]]) or [[]]
where contains(type,"LoreEvents")
>
>>[!info]+  Involved quest(s)
>>```dataview
list from outgoing([[Darbrand Garmult]]) or [[]]
where contains(type,"Quest")
