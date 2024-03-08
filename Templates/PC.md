---
type: PC
world: Faerun
campaign: Crash of two kingdoms
description: 
race: 
gender: 
sex: 
pronouns: 
classes: 
date: <% tp.date.now() %>
aliases: 
ddblink: 
level: 
DiscordUser: 
DiscordUserID:
---
<% await tp.file.move("Compendium/PCs/" + tp.file.title) %>
# `=this.file.name`
## Backstory

**Add Backstory here**

## DMs note

**Add DM's note here**

## Character sheet

```meta-bind-button
label: Embed D&D Beyond Character sheet
hidden: false
class: ""
tooltip: " Click bellow the button first, also make sure that the ddblink property is filled before pressing the button"
id: ""
style: default
actions:
  - type: command
    command: templater-obsidian:Templates/DDB character sheet embed.md

```


