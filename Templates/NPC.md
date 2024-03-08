---
type: NPC
faction: 
location: 
world: Faerun
campaign: Crash of two kingdoms
description: 
race: 
gender: 
sex: 
pronouns: 
class: 
date: <% tp.date.now() %>
aliases: 
command: "!npc"
Personality: 
Role: 
CultInfluence: 
Discovered:
---

<% await tp.file.move("Compendium/NPCs/" + tp.file.title) %>


> [!infobox]
> # `=this.file.name`
> ![[z_Assets/Misc/ImagePlaceholder.png|cover hsmall]]
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

**Add description here**



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