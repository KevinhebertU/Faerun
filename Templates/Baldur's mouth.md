---
type: Baldur'sMouth
world: Faerun
campaign: Crash of two kingdoms
date: <% tp.date.now() %>
tags: 
aliases: 
Discord link: 
Act: 
tier: 
IssueNum: 
ReleaseDate:
---
<% tp.file.move("Compendium/Baldur's Mouth/"+tp.file.title) %>

### Story beats 

>[!Warning]+ Headline
>**==Title==** : 
>**==Text== : 
>**==Image==** :
>**==Explanation==**  (put links to other stuff in here, can be a copy of the text with links): 


>[!Example]+ Article 1
>**==Title==** : 
>**==Text== : 
>**==Image==** :
>**==Explanation==**  (put links to other stuff in here, can be a copy of the text with links): 


>[!Example]+ Article 2 
>**==Title==** : 
>**==Text== : 
>**==Image==** :
>**==Explanation==**  (put links to other stuff in here, can be a copy of the text with links): 

>[!Example]+ Article 3 
>**==Title==** : 
>**==Text== : 
>**==Image==** :
>**==Explanation==**  (put links to other stuff in here, can be a copy of the text with links): 

>[!Example]+ Article 4
>**==Title==** : 
>**==Text== : 
>**==Image==** :
>**==Explanation==**  (put links to other stuff in here, can be a copy of the text with links): 

>[!Example]+ Article 5
>**==Title==** : 
>**==Text== : 
>**==Image==** :
>**==Explanation==**  (put links to other stuff in here, can be a copy of the text with links): 

>[!info]+ Links
>>[!info]+ Involved Location(s)
>>```dataview
list from outgoing([[<% tp.file.title %>]]) or [[]]
where contains(type,"Location")
>
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