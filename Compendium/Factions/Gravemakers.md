---
type: Faction
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
date: 2024-03-01
description: Watching over the [[Cliffside Cemetery]] is the powerful [[Gravemakers]] crew. Far more than simply caretakers and laborers, the Gravemakers guard the dead — and Tumbledown — from threats.
aliases: 
influence:
---
# `=this.file.name`
```dataview
table without id description as Description
where file.name = "Gravemakers"
```

Watching over the [[Cliffside Cemetery]] is the powerful [[Gravemakers]] crew. Far more than simply caretakers and laborers, the Gravemakers guard the dead — and Tumbledown — from threats. With so much death concentrated in one spot, undead are a constant problem. Skeletons and revenants regularly claw spontaneously out of their graves, while ghouls and ghasts burrow into crypts and catacombs, drawn by the scent of decaying flesh. Wights hide in their tombs by day, while ghosts and wraiths terrorize unsuspecting mortals. Putting down such threats before they can prey on citizens is the Gravemakers’ primary job, and though rightfully proud of their prowess.


>[!info]+ Links(s) 
>>[!info]- NPC(s) 
>>>[!info]+ NPC(s) member of  `=this.file.name`
>>>```dataview
list 
where contains(type,"NPC") and  contains(faction,"Gravemakers")
sort file.name asc
>>
>>>[!info]+ NPC(s) linked to `=this.file.name`
>>>```dataview
list from outgoing([[]]) or [[]]
where contains(type,"NPC")
sort file.name asc
>
>>[!info]- Quest(s) 
>>>[!info]+ Quest(s) involving  `=this.file.name` 
>>>```dataview
list 
where contains(type,"Quest") and  contains(faction, "Gravemakers")
sort file.name asc
>>
>>>[!info]+ Quest(s) linked to `=this.file.name`
>>>```dataview
list from outgoing([[]]) or [[]]
where contains(type,"Quest")
sort file.name asc
>
>>[!info]- Lore Events(s) 
>>>[!info]+ Lore Events(s) involving `=this.file.name`
>>>```dataview
list 
where contains(type,"LoreEvents") and  contains(faction,"Gravemakers")
sort file.name asc
>>
>>>[!info]+ Lore Events(s) linked to `=this.file.name`
>>>```dataview
list from outgoing([[]]) or [[]]
where contains(type,"LoreEvents")
sort file.name asc

	