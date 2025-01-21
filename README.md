# Sleeping Gods - Distant Skies
Markdown files to support the board game Sleeping Gods - Distant Skies using Obsidian

The game throws quests and keywords at which can be very tiresome to track. It drew my wife crazy so I added all locations and keywords to my Obsidian vault and use dataview to display locations and keyword discovered. Everything is managed via the metadata properties. The vault has been designed to be used from a phone, so most actions can be managed by ticking a box. 


## Locations
For each location you can tick out whether its visited, crossed out, and what location actions have been done. Each location also has a list of keywords relevant for that location and on which atlas page it can be found:

![image](https://github.com/user-attachments/assets/9f661594-d7c7-4bdd-993b-fce76f43757d)

## Keywords
Each keyword is represented as a separate file with just two properties; Unlocked, and Completed:

![image](https://github.com/user-attachments/assets/689130b1-f4d2-45b8-9f3c-3abe7d8670ed)

## Riddle Rocks
Riddle rocks is a simple static page with tick boxes for each of the riddles. 

## Overview
The file overview brings all the files together for a hopefylly easy overview over locations, what keywords are relevant, which locations have been visited and which ones are crossed out. I use dataview to query the markdown files described above. It is a fairly simple DQL query that is repeated for every 2-page spread of the atlas. The query removes locations from the list that have been crossed out. Keywords are also only shown for locations that have been visited. 

![image](https://github.com/user-attachments/assets/2d268d27-c1c6-49e5-ae2b-8f7442b89d5b)


### How to use
The overview assumes the content of this repo are located in Sleeping Gods - Distant Skies/Default. I make a copy whenever I start a new campaign and change the paths accordingly. It could probably be done more effeciently with Templater or some JavaScript. If that's you jam, have at it! The files are published here in the vain hope that other people will find it useful. You are more than welcome to improve upon it. 

### Shit, it's in Danish
Some of the language is in Danish, I apologize.
