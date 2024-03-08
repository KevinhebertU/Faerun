---
NoteIcon: 
statAC: 
statHP: 
monstertype:
---
<% tp.file.move("Compendium/Creatures/"+tp.file.title) %>
>[!info]
Edit the statblock below with the creature name (You can import creature in Options -> Fantasy Statblock -> Import Hombrew Creature)

```statblock
creature: 
```


>[!info]+  Involved quest(s)
>```dataview
list from ([[<% tp.file.title %>]])
where contains(type,"Quest")