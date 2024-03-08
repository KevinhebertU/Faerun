<% tp.file.move("Compendium/Items/"+tp.file.title) %>
# Item Name

_Melee Weapon, uncommon (requires attunement by a druid or ranger)_

- **Damage**: 1d4 slashing
- **Properties** Light , Requires Attunement
- **Cost**: ⏤
- **Weight**: 2.0 lbs.

Description

_Source: SourceName_


>[!info]+ ¨Links(s) 
>>[!info]+ Involved NPC(s) 
>>```dataview
list from outgoing([[<% tp.file.title %>]]) or [[]]
where contains(type,"NPC")
>
>>[!info]+  Involved lore event(s)
>>```dataview
list from outgoing([[<% tp.file.title %>]]) or [[]]
where contains(type,"LoreEvents")
>
>>[!info]+  Involved quest(s)
>>```dataview
list from outgoing([[<% tp.file.title %>]]) or [[]]
where contains(type,"Quest")