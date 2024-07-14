---
aliases: Home
tags: 
---
# Home

Welcome ♥️ *your name* to your Second Brain.
For a beginners entry I recommend to [[🌱 Start Here]]. Your can also directly jump to the [[Getting Started Guide overview| Getting started guide]]

## Spaces
These are your main entry points called spaces. In Spaces you organize the structure [[The Folder Structure explained |this way]]
``` dataview
List FROM "" where startswith(file.name,"S0")  
SORT file.name ASC
```
## What would you like to to do

| I want to...      | ...play with ideas                                                                                                        |
|:----------------- |:------------------------------------------------------------------------------------------------------------------------- |
| Manage a new book | [[Literature Inbox \|📚 Literature Inbox]]                                                                                |
| Capture an idea   | Add to [[List Fleeting Notes Query#All fleeting notes \|a fleeting note]] and link in the daily note |
| Work in a project | Jump right away to [[List Fleeting Notes Query#All projects\|a project]] or Copy project folder (as fast action in folder menue)                                                 |                  |                                                                                                                           |

## Tasks
``` dataview
task FROM -"S01 Personal/060-069 Utilities/64 Templates"
where !completed
group by file.folder
```
