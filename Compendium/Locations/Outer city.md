---
type: Location
faction: 
location:
  - Faerun
  - Sword Coast
  - Baldur's Gate
world: Faerun
campaign: Crash of two kingdoms
description: 
date: 2024-02-27
tags: 
aliases: 
Discord link: https://discord.com/channels/1171210574437298268/1171210575859159154
---
```dataview
table without id description as Description
where file.name = "Outer city"
```
##### Details

Dirty and uncouth, the Outer City holds everything the elite of Baldur’s Gate resist allowing within their walls: the poor, refugees, tanneries and stockyards, and other industries that offend highborn sensibilities. Stretching forth from each of the city’s external gates, the Outer City sprawls in a chaotic tangle of shanties and shops, carts and tents lining the roads in hopes of bleeding off enough city trade for their owners to survive. And indeed, much of the commerce in [[Baldur's Gate]] happens in these unregulated markets, with even patriars shopping from inside perfumed litters. 

While smaller neighborhoods such as Tumbledown and Blackgate squat outside their respective gates, the majority of the Outer City runs along the Coast Way as it curves around the foot of Duskhawk Hill, between Wyrm’s Crossing and the city proper. Residents of these neighborhoods are not technically citizens and receive no representation in the government, nor do they receive the benefit of the city’s police forces. The Flaming Fist rarely patrols the Outer City, usually emerging only to pursue Outer City residents for crimes committed within the walls. 

The Outer City’s challenges lead to small, tightly knit communities, where a person’s honor and social connections are the only things standing between them and a quick death.

![[Outer city-20240227092522352.webp]]
### Known place

```dataview 
list where contains(type,"Location") and contains(location,"Outer city")
```
### Known NPC

```dataview
list  
where contains(type,"NPC") and contains(location,"Outer city")
```