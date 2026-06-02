---
icon: lucide/book-check
---

# Preparing your environement

For simplicity we made a server that is self-hosted and uses a client with exposed resources.
This is useful in case you only care about adding content to the client and need a working environement to test.
[MEGA](https://mega.nz/folder/z0RVQBYA#cPt_zIyHQc4az75CVRyg2A) [Archive](https://archive.org/download/s4lgameclientarchives/S4%20League%20Game%20Client%20Archive/Season%208(EU%20v1267)/Standalone%20Server%2BClient%20%20Season%208%20(EU%20v1267).zip)

These are the differences with a vanilla client and the original server code from S8:

* Resources exposed, and the server uses those exact same resources if the client is placed in the "Game" folder
* Can modify most resources on the fly, so no need to restart the client that frequently, only for weapons .lua files 
* No mission pop up on log in

* No need to install anything aside from .NET and download Redis.
* DB created on startup if it doesnt exist
* DB checks if channels, shop prices, and shop items tables are empty, if anything is missing it adds everything automatically from the game files
* This means the in-game shop is ready to go from the start, and it can be refreshed by deleting game.db
* Server makes account if it doesnt exist, if it does it just overrides the password
* On first log in character is created automatically and equipped with default stuff defined in start_items (dagger and wings by default)
* Max level on account creation with all chars created
* Can enter any type of gamemode alone
* No AFK kick



For more info refer to the repository: 

https://github.com/eSper-devS/NetspherePirateShip