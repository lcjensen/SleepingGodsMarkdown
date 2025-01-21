Claire Location: 
## Locations
### Pages 2-3

```dataview
TABLE choice(crossed-out , "✘", "") as Afkrydset, choice(Besøgt, Keywords, "") AS Keywords, choice(Besøgt, "✅", "") as Besøgt
FROM "Sleeping Gods - Distant Skies/Default/Locations"
WHERE (atlas-page = "2" OR atlas-page = "3") and crossed-out != true
SORT file.name
```

## Pages 4-5

```dataview
TABLE choice(crossed-out , "✘", "") as Afkrydset, choice(Besøgt, Keywords, "") AS Keywords, choice(Besøgt, "✅", "") as Besøgt
FROM "Sleeping Gods - Distant Skies/Default/Locations"
WHERE atlas-page = "4" OR atlas-page = "5" and crossed-out != true
SORT Side asc
```

### Pages 6-7

```dataview
TABLE choice(crossed-out , "✘", "") as Afkrydset, choice(Besøgt, Keywords, "") AS Keywords, choice(Besøgt, "✅", "") as Besøgt
FROM "Sleeping Gods - Distant Skies/Default/Locations"
WHERE atlas-page = "6" OR atlas-page = "7" and crossed-out != true
SORT Side asc
```

### Pages 8-9

```dataview
TABLE choice(crossed-out , "✘", "") as Afkrydset, choice(Besøgt, Keywords, "") AS Keywords,  choice(Besøgt, "✅", "") as Besøgt
FROM "Sleeping Gods - Distant Skies/Default/Locations"
WHERE atlas-page = "8" OR atlas-page = "9" and crossed-out != true
SORT Side asc
```


### Pages 10-11

```dataview
TABLE choice(crossed-out , "✘", "") as Afkrydset, choice(Besøgt, Keywords, "") AS Keywords, choice(Besøgt, "✅", "") as Besøgt
FROM "Sleeping Gods - Distant Skies/Default/Locations"
WHERE atlas-page = "10" OR atlas-page = "11" and crossed-out != true
SORT Side asc
```


### Pages 12-13

```dataview
TABLE choice(crossed-out , "✘", "") as Afkrydset, choice(Besøgt, Keywords, "") AS Keywords, choice(Besøgt, "✅", "") as Besøgt
FROM "Sleeping Gods - Distant Skies/Default/Locations"
WHERE atlas-page = "12" OR atlas-page = "13" and crossed-out != true
SORT Side asc
```

### Pages 14-15

```dataview
TABLE choice(crossed-out , "✘", "") as Afkrydset, choice(Besøgt, Keywords, "") AS Keywords, choice(Besøgt, "✅", "") as Besøgt
FROM "Sleeping Gods - Distant Skies/Default/Locations"
WHERE atlas-page = "14" OR atlas-page = "15" and crossed-out != true
SORT Side asc
```

### Pages 16-17

```dataview
TABLE choice(crossed-out , "✘", "") as Afkrydset, choice(Besøgt, Keywords, "") AS Keywords, choice(Besøgt, "✅", "") as Besøgt
FROM "Sleeping Gods - Distant Skies/Default/Locations"
WHERE atlas-page = "16" OR atlas-page = "17" and crossed-out != true
SORT Side asc
```


### Pages 18-19

```dataview
TABLE choice(crossed-out , "✘", "") as Afkrydset, choice(Besøgt, Keywords, "") AS Keywords, choice(Besøgt, "✅", "") as Besøgt
FROM "Sleeping Gods - Distant Skies/Default/Locations"
WHERE atlas-page = "18" OR atlas-page = "19" and crossed-out != true
SORT Side asc
```


### Riddle Rocks

![[Sleeping Gods - Distant Skies/Default/Quests/Riddle Rocks]]




```dataview
TABLE 
FROM "Sleeping Gods - Distant Skies/Default/Keywords"
Sort file.name asc
WHERE Unlocked = true and Completed != true
```
