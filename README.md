# SWBFSpy
SWBFSpy Internet Master Server for Star Wars Battlefront

As of May 1st 2018, SWBFSpy is fully operational for SWBF1 on PC! 
-
- Additional features are currently being added, such as leaderboards, direct connection, server list, mod downloads manager, shell streaming support, console support, SWBF2 support, and more. We expect to have most of these functional before 2019. To play on SWBFSpy you must be whitelisted, contact Phobos if you have questions. Stay tuned for more news!

SWBFSpy is a project managed by the SWBFModders community to replace the GameSpy master server software used to host game servers for Star Wars Battlefront (2004) and Star Wars Battlefront II (2005) on the PC, PS2, and XBOX. We have officially restored full server browser functionality, and currently we're adding a leaderboards system for all players in our game servers.

SWBFSpy is based on OpenSpy source codes. All the original GameSpy features such as Leaderboards are being added, in addition to several brand new features. The administrators and developers of SWBFSpy include [FC]Phobos and [FC]Wolf, who both founded the SWBFSpy project in September 2013 after many discussions. [FC]Wolf created the initial prototype files, but went inactive during 2014. Since then, [FC]Phobos has been the sole admin of SWBFSpy, and brought the SWBF PC internet servers back online in May 2018.

What resources we are able to share here, others should find useful for adapting OpenSpy source to support multiplayer master servers for games other than Star Wars Battlefront 1 and 2, although SWBFSpy currently has no plans to support other games at this time. Let us know if you would like to help us add support for any other games!

Some of our source code can't be shared on GitHub due to hostility from jealous trolls who were never involved in the creation or administration of SWBFSpy. Don't be fooled by their lies and fake websites. Shortly after they saw the SWBFSpy shell .TGA files that Phobos posted in 2016, they unsucessfully tried to publicly plagiarize SWBFSpy from him and lock him out of his own creations, so eventually (after refusing more diplomatic solutions) they were banned from the community as a result. We've since had to implement a Whitelist Firewall to keep out those trolls and other server crashers. See the community page on our info website for more history.

Phobos is the Administrator, Founder, Operations Manager, Technical Director, and Chief Executive Officer of our SWBFSpy Organization. You can learn more at the official SWBFSpy info website here: http://info.SWBFSpy.org

Also check out the official SWBF community forums at http://www.SWBFModders.com

If you want to host a SWBFSpy dedicated server:
- Download dedicated server files from http://www.swbfmodders.com
- Download multiplayer server binaries from http://info.swbfspy.org/
- Replace the server executable with the one downloaded from swbfspy

Instructions for manually hex editing SWBFSpy support:
- Download HxD or any other free hex editor
- Open Battlefront.exe with HxD and go to Search -> Replace
- Replace all instances of "gamespy.com" with "swbfspy.org" (without the quotes)
- Save the .exe and launch SWBF, using the SWBFSpyAdmin Launcher by Phobos if you have it
- Click SWBFSpy Server Lobby ingame, it will connect you to SWBFSpy.org if your IP is Whitelisted
- Repeat the hex edit for any server executables you have if hosting dedicated servers
- Join a game server, or contact Phobos if you have issues connecting to SWBFSpy
