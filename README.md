# How to use ?
[![Français](https://cdn3.iconfinder.com/data/icons/142-mini-country-flags-16x16px/32/flag-france2x.png)](https://github.com/Team13fr/IgnisMulti/wiki/Français)
[![Español](https://cdn3.iconfinder.com/data/icons/142-mini-country-flags-16x16px/32/flag-spain2x.png)](https://github.com/Team13fr/IgnisMulti/wiki/Español)

## [![English](https://cdn3.iconfinder.com/data/icons/142-mini-country-flags-16x16px/32/flag-usa2x.png)](https://github.com/Team13fr/IgnisMulti#-english-) English :
### Ygopro Multi
The translations tool is available directly on Pipas APP, a multiplatform application which brings together all the services of our team. Ygopro Multi is just simpler to install and will be updated more often.
- Download Pipas APP here : [https://team13.fr/pipas/#télécharger](https://team13.fr/pipas/#télécharger)
- Install the application.
- Choose your language at the top right.
- Go to the **Ygopro Multi** menu.
- With the button **Browse** select the  EDOPro.exe in its installation folder.
- You just have to start the game with the button **Launch Ygopro**!
### Manual installation
- Edit the file **configs.json** with a program like Notepad++ in directory **config**
- Add on line 31
```json
{
      "url": "https://github.com/Team13fr/IgnisMulti",
      "repo_name": "Team13.fr Multilanguage updates",
      "repo_path": "./config/languages",
      "has_core": false,
      "data_path": "",
      "should_update": true,
      "should_read": true
    }
```
exemple :
```json
{
  "repos": [
    {
      "url": "https://github.com/ProjectIgnis/DeltaHopeHarbinger",
      "repo_name": "Project Ignis updates",
      "repo_path": "./repositories/delta",
      "has_core": true,
      "core_path": "bin",
      "data_path": "",
      "script_path": "script",
      "should_update": true,
      "should_read": true
    },
    {
      "url": "https://github.com/ProjectIgnis/LFLists",
      "repo_name": "Forbidden & Limited Card Lists",
      "repo_path": "./repositories/lflists",
      "has_core": false,
      "should_update": true,
      "should_read": true,
      "lflist_path": "."
    },
    {
      "url": "https://github.com/ProjectIgnis/Puzzles",
      "repo_name": "Project Ignis puzzles",
      "repo_path": "./puzzles/Canon collection",
      "has_core": false,
      "should_update": true,
      "should_read": true
    },
    {
      "url": "https://github.com/Team13fr/IgnisMulti",
      "repo_name": "Team13.fr Multilanguage updates",
      "repo_path": "./config/languages",
      "has_core": false,
      "data_path": "",
      "should_update": true,
      "should_read": true
    }
  ],
  "urls": [
    {
      "url": "default",
      "type": "pic"
    },
    {
      "url": "default",
      "type": "field"
    },
    {
      "url": "default",
      "type": "cover"
    }
  ],
  "servers": [
    {
      "name": "EU Central (Competitive)",
      "address": "185.227.110.90",
      "duelport": 7911,
      "roomaddress": "185.227.110.90",
      "roomlistport": 7922
    },
    {
      "name": "NA Pacific (Casual)",
      "address": "73.240.71.103",
      "duelport": 7911,
      "roomaddress": "73.240.71.103",
      "roomlistport": 7922
    }
  ],
  "posixPathExtension": "/usr/local/bin:/Library/Frameworks/Mono.framework/Versions/Current/Commands"
}
```

