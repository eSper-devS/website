---
icon: lucide/book-check
---

# Server Setup

There are two different main versions of open source servers, one compatible with S1 and other compatible with S8.

### There are leaks of versions from private servers that are based on the S8 server, but most of those are not safe, very likely containing malicious code in them, it is not recommended to use these.

Both versions were made by wtfblub, with enginelesscc helping on the S8 server.

S1: https://github.com/wtfblub/NetspherePirates
S8: https://gitlab.com/NetspherePirates/NetspherePirates/

There is a fork of S1 that implements some of the missing features:
https://github.com/shanzenos/NetSphere-Pirates-Season-1-Extended

And our fork of S8, focused only on custom content creation:
https://github.com/eSper-devS/NetspherePirateShip

### Do not use this version for hosting, it has specific features for ease of use when creating content that will either make your server unsafe or simply not work.


## Preparing your environment

If you do want to host one of the servers that is not our version Shanz made a guide on how to:
https://gamebanana.com/tuts/13079

### For simplicity, we made a server that is self-hosted and uses a client with exposed resources.
This is useful in case you only care about adding content to the client and need a working environment to test.
[MEGA](https://mega.nz/folder/z0RVQBYA#cPt_zIyHQc4az75CVRyg2A) [Archive](https://archive.org/download/s4lgameclientarchives/S4%20League%20Game%20Client%20Archive/Season%208(EU%20v1267)/Standalone%20Server%2BClient%20%20Season%208%20(EU%20v1267).zip)

These are the differences from a vanilla client and the original server code from S8:

* Resources are exposed, and the server uses those exact same resources if the client is placed in the "Game" folder
* Can modify most resources on the fly, so no need to restart the client that frequently, only for weapons .lua files 
* No mission pop up on login

* No need to install anything aside from .NET and download Redis.
* DB created on startup if it doesn't exist
* DB checks if channels, shop prices, and shop items tables are empty, if anything is missing it adds everything automatically from the game files
* This means the in-game shop is ready to go from the start, and it can be refreshed by deleting game.db
* Server creates account if it doesn't  exist, if it does it just overrides the password
* On first login a character is created automatically and equipped with default items defined in start_items (dagger and wings by default)
* Max level on account creation with all chars created
* Can enter any type of gamemode alone
* No AFK kick


For this version you only need to install:

* [.Net Core 2.1](https://www.microsoft.com/net/download/dotnet-core/2.1)
* Windows only: [.Net Framework 4.7.2](https://www.microsoft.com/net/download/thank-you/net472)


For more info refer to the repository: 

https://github.com/eSper-devS/NetspherePirateShip