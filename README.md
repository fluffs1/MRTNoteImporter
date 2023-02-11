# MRTNoteImporter
Simple WoW Addon for importing [Method Raid Tools](https://www.curseforge.com/wow/addons/method-raid-tools) notes into the game.

# Just using it.

Get it from all good wow addon providers !

- [Curseforge Link](https://www.curseforge.com/wow/addons/mrtnoteimporter)
- [WoWInterface Link](https://www.wowinterface.com/downloads/info26398-MRTNoteImporter.html)
- [Wago Link](https://addons.wago.io/addons/mrtnoteimporter)

Or directly from the releases here on github.


# Usage
In game, run `/mrtni`, and paste JSON into the window. The JSON should be formatted like

```
{ 
   "NoteName1": "This is the first note",
   "NoteName2": "This is the second note",
   "NoteName3": "This is the third note\nWith a linebreak\nAnd another one"}
}
```

For example
```
{
    "1 - Anub": "Kill big undead thing\nAnother line about the undead thing.",
    "2 - Grand Widow": "Kill woman and worshipers",
    "3 - Maexxna": "Kill big spider thing"
}
```

You can also click the "Fetch Notes" button to export the notes you currently have in MRT in the same format.
