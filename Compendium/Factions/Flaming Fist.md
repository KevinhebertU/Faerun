---
type: Faction
faction:
  - Flaming Fist
location:
  - Faerun
  - Sword Coast
  - Baldur's Gate
world: Faerun
campaign: Crash of two kingdoms
date: 2024-02-28
description: 
aliases:
  - Fist
influence:
---
```dataview
table without id description as Description
where file.name = "Flaming Fist"
```

The red and gold symbol of the Flaming Fist mercenary company has become emblematic of [[Baldur's Gate]]. The [[Council of Four]] funds the Flaming Fist, supporting it as the city’s army. [[Grand Duke Ulder Ravengard]] is now its undisputed leader. The Flaming Fist largely patrols the[[ Lower City]], though it holds nominal authority over the [[Outer City]] as well. The company has enough to do maintaining order within the city walls without straying too far from its gates, though the [[Flaming Fist|Fist]]  has been known to hire independent agents when its ranks are spread thin. Thousands of soldiers currently serve in the Flaming Fist: in Baldur’s Gate proper, at the fortress of Wyrm’s Rock on the Chionthar River, and at remote outposts such as Fort Beluarian in Chult. The Flaming Fist offers employment and a sense of belonging to any who can lift a sword and follow orders. Native Baldurians, immigrants, former criminals, and retired adventurers can all be found within the company’s ranks.

![[Flaming Fist-20240228163200278.webp]]![[Flaming Fist-20240228163212980.webp]]

>[!info]+ Links(s) 
>>[!info]+ Involved NPC(s) 
>>```dataview
list from outgoing([[Flaming Fist]])
where contains(type,"NPC")
>
>>[!info]+ Involved Location(s) 
>>```dataview
list from outgoing([[Flaming Fist]])
where contains(type,"Location")
>
>>[!info]+  Involved lore event(s)
>>```dataview
list from outgoing([[Flaming Fist]])
where contains(type,"LoreEvents")
>
>>[!info]+  Involved quest(s)
>>```dataview
list from outgoing([[Flaming Fist]])
where contains(type,"Quest")


	