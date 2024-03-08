---
type: Faction
faction:
  - Jagged Edge Bandits
location:
  - Faerun
  - Sword Coast
  - Jagged Edge Hideaway
  - High Road
world: Faerun
campaign: Crash of two kingdoms
date: 2024-02-29
description: Group of bandits that are pillaging caravans, under the command of [[Goblin Queen Bargnot]]
aliases: 
influence:
---
```dataview
table without id description as Description
where file.name = "Jagged Edge Bandits"
```

Group of bandits that are pillaging caravans, under the command of [[Goblin Queen Bargnot]]
>[!info]+ ¨Links(s) 
>>[!info]+ Involved NPC(s) 
>>```dataview
list from outgoing([[Jagged Edge Bandits]]) or [[]]
where contains(type,"NPC")
>
>>[!info]+ Involved Location(s) 
>>```dataview
list from outgoing([[Jagged Edge Bandits]]) or [[]]
where contains(type,"Location")
>
>>[!info]+  Involved lore event(s)
>>```dataview
list from outgoing([[Jagged Edge Bandits]]) or [[]]
where contains(type,"LoreEvents")
>
>>[!info]+  Involved quest(s)
>>```dataview
list from outgoing([[Jagged Edge Bandits]]) or [[]]
where contains(type,"Quest")


	