---
icon: lucide/badge-question-mark
---

# Guide






# Guides and tools for development of content for S4 League

First you are gonna need access to the resources, it is recommended to use a Season 8 client, there are clients newer than this one (S10) but the current open source server is only compatible with season 8 clients, that is why it is recommended to use that version, S10 only has a bunch of feature most people don't care about, aside from new skins so it isn't 100% necessary unless you want those.

## Checking the files or getting the resources out:
You have 3 options for this:

- Extract or modify the resources with the old tools that everyone has been using since ever: 
https://gamebanana.com/tools/6544

- Use the new tool by @eloscar233 
This one has a few quirks but if you want to play around with other seasons or stock clients its the best option right now, aside from having a nice viewer
https://github.com/oscarsantanaarias/s4league_itemManager

- Use a client that works with all the resources extracted
https://archive.org/download/s4lgameclientarchives/S4%20League%20Game%20Client%20Archive/Season%208(EU%20v1267)/ExternalResourceFumbiClient_1267_S8.7z
(this one is very neat since thanks to the mod a lot of the times you can change stuff on the fly, without needing to restart) (Thanks a lot @deviyacc )


In case you are not using the custom client the best vanilla one is this:
https://ia601007.us.archive.org/0/items/s4lgameclientarchives/S4%20League%20Game%20Client%20Archive/Season%208(EU%20v1267)/

You can check the other versions on the following link:
https://archive.org/download/s4lgameclientarchives/S4%20League%20Game%20Client%20Archive/




























## 3D MODEL FILES / SCNs:
S4 League uses a proprietary format for all the 3d models, any file that has the .scn format either contains a straight up model or stuff(animations) for the armature of the characters.

For this your best bet right now is @aeven.dev 's tool:
https://github.com/Aeven-Dev/UnityScnTool
It does allow importing .scn files and exporting models as non-proprietary formats, it does allow you to export stuff as .scn for making custom content
It does need unity, install instructions are in the github page:
https://github.com/Aeven-Dev/UnityScnTool/wiki/Instalation!-:D
How to use instructions:
https://github.com/Aeven-Dev/UnityScnTool/wiki/How-to-use!--%E2%9D%A4%EF%B8%8F

### There are other users making different tools for map viewing and other stuff, will update if these end up releasing





## OK, HOW DO ADD MY CUSTOM CONTENT:
@shanzenos  (thanks a lot btw) did a bunch of video tutorials explaining what stuff you can add and what files need to be modified:
https://www.youtube.com/playlist?list=PLZNZEiGC9J3plPl8EX22MaWzh3s2RTYOL

It contains tutorials about how to add:
Music
Custom Maps
Weapons
Weapon Skins
Costumes\Items

Shanz wrote tutorials too:
https://gamebanana.com/tuts/cats/2582

This one explains the different folders and files that you can find inside the game, since you can mod beyond what the previous tutorials explain, but it is more complex:
https://gamebanana.com/tuts/19512





## HOW TO TEST STUFF INGAME:
You will need to host your own server, this tutorial explains pretty much everything you need to know:
https://gamebanana.com/tuts/13079

The server that is recommended for the S8 client is:
https://gitlab.com/NetspherePirates/NetspherePirates/
(credits to wtfblub)
Install .Net Core 2.1:
https://dotnet.microsoft.com/es-es/download/dotnet/thank-you/runtime-2.1.30-windows-x64-installer?cid=getdotnetcore

To have the items show up in the game they do need to be in the db, you can use this script to fill with every item inside your files:
https://github.com/eSper-devS/item_parser






If you have any questions or problems feel free to ask in eSper devS
