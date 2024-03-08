# The world

##### PC
```dataview
list from "PC"
```

[[Index]]
## Open loop

- [[Quests and Questions]]
- [[Agenda]]

## Sessions
```dataview
list from "Sessions"
```

```dataview
table without id description as Description
where file.name = "The world"
```
##### Details


### Known place

```dataview 
list where contains(type,"Location") and contains(location,"The world")
```
### Known NPC

```dataview
list  
where contains(type,"NPC") and contains(location,"The world")
```