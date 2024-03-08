---
cssclass: purpleRed, wideTable, fixedFc 
---
# Index

<span class="nav">[Locations](##Locations)   [NPCS](##NPCS)   [Factions](##Factions)</span>

# test

## Locations
```dataview 
table without ID file.link as Name, description as Description
from "" where type = "Location" sort file.name asc 
where file.name !="Location"
```

## NPCS

```dataview
table without id 
file.link as Name, description as Description, command as DiscordCmd from "" where type = "NPC" sort file.name asc

where file.name !="NPCv2"
```

## Factions
```dataview
list from "" where type = "Faction" sort file.name asc 
where file.name !="Faction"
```
## Quest

```dataview
table without id 
file.link as Name, description as Description, location as Locations from "" where type = "Quest" sort file.name asc

where file.name !="Quest"
```

```dataview
table
file.link as Name, fil, location as Locations from "" where type = "Quest" sort file.name asc

where file.name !="Quest"
```