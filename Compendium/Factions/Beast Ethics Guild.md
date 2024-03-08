---
type: Faction
faction:
  - Beast Ethics Guild
location: 
world: Faerun
campaign: Crash of two kingdoms
date: 2024-02-29
description: The BEG advocates for the protection of magical creatures.
aliases:
  - BEG
influence: 
Approved:
---
# `=this.file.name`
```dataview
table without id description as Description
where file.name = "Beast Ethics Guild"
```

## Overview
The faction advocates for the protection of magical creatures, including griffons, manticores, basilisks, etc. Diverse group with varying perspectives on conservation tactics and approaches. Members aim to differentiate between creatures with self-awareness and those without.

## Moral Justification
Concerned with the ecological impact of harming or capturing magical creatures. General rule to save creatures not actively harming the ecosystem, but internal conflicts arise over the extent of conservation.
  
## Leadership twist
Hidden leadership reveals allegiance to a cult with hidden motives. Some leaders or influential members may be unaware, while others knowingly align with the cult. 
 
## Internal conflicts
Arguments and infighting over the extent of conservation efforts. Ignorant members pushing for the protection of all magical creatures, causing tension within the faction. 
 
## Extreme Measures
Faction's perspective on forced captivity evolves to align with the cult's purposes. The group becomes more extreme, influenced by the cult's agenda.
  
## Public Relations
Satirical PETA vibes, with the faction running misleading campaigns for fundraising. Ads in Baldur's Mouth depict adventurers as monsters, redirecting funds to the hidden cult.

>[!info]+ Links(s) 
>>[!info]- NPC(s) 
>>>[!info]+ NPC(s) member of  `=this.file.name`
>>>```dataview
list 
where contains(type,"NPC") and  contains(faction,"Beast Ethics Guild")
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
where contains(type,"Quest") and  contains(faction, "Beast Ethics Guild")
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
where contains(type,"LoreEvents") and  contains(faction,"Beast Ethics Guild")
sort file.name asc
>>
>>>[!info]+ Lore Events(s) linked to `=this.file.name`
>>>```dataview
list from outgoing([[]]) or [[]]
where contains(type,"LoreEvents")
sort file.name asc

	