---
type: Faction
faction:
  - Sisters of Compassion
location: 
world: Faerun
campaign: Crash of two kingdoms
date:
  - 2024-02-26
description: 
aliases:
  - Hags
---
```dataview
table without id description as Description
where file.name = "Sisters of Compassion"
```
### Known member(s)

```dataview
list CultInfluence 
where contains(type,"PC") and contains(faction,"Sisters of Compassion")
```
```dataview
TABLE WITHOUT ID sum(map(rows, (r) => default(r.CultInfluence, 0))) AS "Cult influence" 
where contains(type,"PC") and contains(faction,"Sisters of Compassion") 
GROUP BY true
```
## Backstory of the hags

Previously, they were a group of three. [[Zaleria Thornheart]]  , skilled with charisma and manipulation, [[Leylenna Shadowsoul]], who focuses her magic on healing and necromancy, and [[Primrose Drach]], who was highly skilled with nature magic. They met in their childhood and were very close, learning and growing their powers in secret together as magic wasnt understood where they grew up. When they were almost old enough to leave and set off together into the world, [[Leylenna Shadowsoul|Leylenna]] and [[Primrose Drach|Primrose]] were getting closer and were beginning to have feelings for each other, causing [[Zaleria Thornheart|Zaleria]]  to become paranoid and jealous. She used her magic to manipulate one of the local village boys into following her, leading her to where [[Leylenna Shadowsoul|Leylenna]] was practicing her magic. The boy attacked her, and [[Primrose Drach|Primrose]] got in the way, sacrificing herself so the other two could escape. [[Leylenna Shadowsoul|Leylenna]] and [[Zaleria Thornheart|Zaleria]]  got away and travelled far to find somewhere safe to live. Both moured their loss, [[Leylenna Shadowsoul|Leylenna]]  for her lover and [[Zaleria Thornheart|Zaleria]] for her friend, though she never revealed her part in [[Primrose Drach|Primrose]] death. 

## Summonning of the spirit

After years they grew apart, each focusing on their own goals. Eventually, [[Leylenna Shadowsoul|Leylenna]]  returned to the village and summoned Primroses spirit to speak to her one last time. She revealed that [[Zaleria Thornheart|Zaleria]]  had been the one to lead the boy to Leylenna, and had betrayed them both by revealing their magic and getting [[Primrose Drach|Primrose]] killed. Distraught, [[Leylenna Shadowsoul|Leylenna]]  turned away from her healing magic and focused more on her growing skills in necromancy, her goal to amass an army to get revenge on [[Zaleria Thornheart|Zaleria]] . 

  
## 
Meanwhile, [[Zaleria Thornheart|Zaleria]]  had her own goals. She had spent her years gathering followers to her cause, convincing them that with worship, she would be able to grant them powers. She used her magic to convince people, and the draw in other powerful mages to then drain their magic, keeping it mostly for herself and sharing small amounts with her loyal followers. She began searching for more ways to drain magic, and has visited various magical sites to drain the magic from those places too. She cannot do it alone though, so she’s seeking out her old friend  [[Leylenna Shadowsoul|Leylenna]] , unaware of what she’s discovered, to help her with her most ambitious plan yet. She plans to complete a ritual that will bring the continent of [[Eldrathia]] to [[Faerun]]. Bringing the continent here will drain all her magic, but it will bring with it [[Gwendolyn Grimsbane]], a witch with power skills in controlling dragons. The continent itself is a magic rich place, with plenty of locations of highly concentrated magic that [[Zaleria Thornheart|Zaleria]]  plans to drain for her own purposes. [[Gwendolyn Grimsbane|Gwendolyn]] has been trapped on the continent for a long time, after she used her control over the dragons to wreak havoc across the rest of the world.

---
type: Faction
faction: 
location: 
world: Faerun
campaign: Crash of two kingdoms
date: 2024-02-29
description: 
aliases: 
influence:
---
```dataview
table without id description as Description
where file.name = "Sisters of Compassion"
```



>[!info]+ Links(s) 
>>[!info]- NPC(s) 
>>>[!info]+ NPC(s) member of  `=this.file.name`
>>>```dataview
list 
where contains(type,"NPC") and  contains(faction,"Sisters of Compassion")
sort file.name asc
>>
>>>[!info]+ NPC(s) linked to `=this.file.name`
>>>```dataview
list from outgoing([[]]) or [[]]
where contains(type,"NPC")
sort title asc
>
>>[!info]- Quest(s) 
>>>[!info]+ Quest(s) involving  `=this.file.name` 
>>>```dataview
list 
where contains(type,"Quest") and  contains(faction, Sisters of Compassion")
sort title asc
>>
>>>[!info]+ Quest(s) linked to `=this.file.name`
>>>```dataview
list from outgoing([[]]) or [[]]
where contains(type,"Quest")
sort title asc
>
>>[!info]- Lore Events(s) 
>>>[!info]+ Lore Events(s) involving `=this.file.name`
>>>```dataview
list 
where contains(type,"LoreEvents") and  contains(faction,"Sisters of Compassion")
sort title asc
>>
>>>[!info]+ Lore Events(s) linked to `=this.file.name`
>>>```dataview
list from outgoing([[]]) or [[]]
where contains(type,"LoreEvents")
sort title asc

	