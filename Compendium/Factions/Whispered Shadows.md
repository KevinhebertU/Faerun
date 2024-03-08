---
type: Faction
faction:
  - Whispered Shadows
location:
  - Faerun
  - Sword Coast
  - Baldur's Gate
  - Lower city
  - Umbral Den
world: Faerun
campaign: Crash of two kingdoms
date: 2024-03-05
description: "[[Baldur's Gate]] thieves guild"
aliases:
  - Thieves guild
influence:
---
# `=this.file.name`
```dataview
table without id description as Description
where file.name = "Whispered Shadows"
```

[[Baldur's Gate]] thieves guild

**Leader:** [[Nine fingers Keene]]

Primary Base: **The Umbral Den:** Tucked away in the labyrinthine alleyways of the Lower City, the Umbral Den serves as the primary hideout for the Whispered Shadows. Concealed by magical wards and illusions, this secret lair is the epicenter of their clandestine operations

**Guild Motto**: "In Shadows We Trust."

### Code of Conduct
:
- Members are sworn to secrecy, with loyalty to the guild above all else.
- Stealth and subtlety are prioritized over brute force.
- Guild members are expected to contribute a portion of their gains to the collective wealth of the organization.
- Betrayal or compromise of guild secrets is met with severe consequences, often ending in exile or worse.

### Guild Operations:

- Information Brokering: The guild gathers and sells valuable information to various factions, maintaining a vast network of spies and informants throughout the city.
 - Heists and Robberies: The Whispered Shadows specialize in high-stakes heists, targeting wealthy nobles, influential figures, and even rival guilds. They use their stolen treasures to exert influence over the city's power dynamics.
- Blackmail and Extortion: Leveraging their gathered intel, the guild engages in discreet blackmail and extortion, ensuring their influence extends beyond the physical realm.
- Smuggling and Contraband: The Whispered Shadows control secret smuggling routes, trafficking illegal goods throughout Baldur's Gate. They maintain alliances with other criminal organizations to maximize their reach.

### Hierarchy: 

- The Umbra Council: Comprising the most trusted and skilled members, this select group aids Keene in decision-making and strategizing. 
- The Shadebound: In charge of intelligence gathering and espionage, these members operate in the city's key areas, ensuring the guild stays informed.
- The Nightshade Envoys:: Skilled thieves responsible for executing high-profile heists and ensuring the Whispered Shadows maintain dominance in the criminal underworld. 
- The Veiled Initiates: Entry-level members and initiates, undergoing rigorous training in stealth, thievery, and the guild's code of conduct. 
- The Whispering Shadows: Street Operatives and Lookouts: The eyes and ears of the guild, operating in various districts of Baldur's Gate. They are responsible for relaying information, securing hideouts, and ensuring the safety of the guild's members. Some eventually ascend to higher ranks based on their skills and loyalty.

### Current State: 

The guild is in a delicate balance, avoiding direct confrontations with authorities and rival factions. Silvan Blackthorn seeks to expand the guild's influence while dealing with internal power struggles and external threats. Arden's unwitting involvement becomes a critical factor in the guild's unfolding schemes. (edited)

>[!info]+ Links(s) 
>>[!info]- NPC(s) 
>>>[!info]+ NPC(s) member of  `=this.file.name`
>>>```dataview
list 
where contains(type,"NPC") and  contains(faction,"Whispered Shadows")
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
where contains(type,"Quest") and  contains(faction, "Whispered Shadows")
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
where contains(type,"LoreEvents") and  contains(faction,"Whispered Shadows")
sort file.name asc
>>
>>>[!info]+ Lore Events(s) linked to `=this.file.name`
>>>```dataview
list from outgoing([[]]) or [[]]
where contains(type,"LoreEvents")
sort file.name asc

	