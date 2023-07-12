# PeoplePlayground-Modding-Tutorial
A modding tutorial for youtube! Subscribe to it! https://www.youtube.com/@guestgamez/videos

//Paste this into your "main.cs"
using UnityEngine;
using System;
using System.Collections.Generic;
using System.Collections;
using System.IO;
using UnityEngine.UI;
using System.Linq;
using TMPro;
using UnityEngine.Events;


//BASE SCRIPT
namespace Mod
{
    public class Mod
    {
        public static void Main()
        {
            
        }
    }
}

Then paste this into your "mod.json"

{
  "Name": "MyGreatMod",
  "Author": "EythenMakes",
  "Description": "Youtube tutorial",
  "ModVersion": "1.0",
  "GameVersion": "1.14+",
  "ThumbnailPath": ".png",
  "EntryPoint": "Mod.Mod",
  "Tags": [],
  "Scripts": [
    "main.cs"
  ],
  "Active": true,
  "UGCIdentity": null,
  "CreatorUGCIdentity": "2622291045"
}
    "main.cs"
  ],
  "Active": true,
  "UGCIdentity": null,
  "CreatorUGCIdentity": "2622291045"
}
