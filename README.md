## Hello World! (and a little about me)

I am a developing developer that lives in Washington State in the US!  I originally got into computer science as a way to experiment more with my passion for math, which is still my absolute favorite thing to do!  I also love piano, and love composing music for my family and friends :D

## Portfolio
*For many of these the code is still private but the results are public.  I am also working on some other cool projects that can't be here quite yet ):*

**Lord of the Rings Experience** (With DotWavPresents, for Twitch)

One perspective: https://www.twitch.tv/videos/1609508098?filter=archives&sort=time

I had a fairly central role in this project.  I created the PVE Games and systems.  This involved multiple custom mob AI which included custom pathfinding for one. I also made the serverwide NPC system, which was used by all minigames in the event.  Making the NPC system taught me a lot more about NMS development, and was super fun. I also created the raycasting system for the platform and chains games.

**Twitch Rivals Event** (With DotWavPresents - https://twitter.com/dotwavpresents?ref_src=twsrc%5Egoogle%7Ctwcamp%5Eserp%7Ctwgr%5Eauthor)

I created the system for the parkour minigames in the RingCraft event.  For this project I also worked a lot on my time management because we had only 3 weeks to create the event.

**RoverLink** (https://github.com/Yoursole1/RoverLink)

I made this as a passion project that schools with low budgets could use as a way to learn about robotics.  It includes a custom server that runs on the rover and reads packets that control the movement, as well as an API that is run on the controlling computer.  This is still a work in progress but is functional at the moment. 

## My Small Projects (Not all chronological)

**Capture the Flag** (https://github.com/Yoursole1/CTF)

*Little note that this is not the original repository because it was remade when the plugin was rewritten in Kotlin)

I started this project as my first real minecraft minigame.  It was also my first real kotlin project.  Mechanically, it is quite similar to UHC, but also includes teamwork aspects as players try to hunt each other down.  The game starts with a 15-30 minute grace period, where everyone gathers gear, crafts custom items, and learns the mechanics.  The flag then drops from a random location inside the generated game region.  Whoever picks up the flag first becomes the "hunted", and everyone else is a "hunter".  The longer the hunted holds the flag, the more points they get.  Whoever kills them gets the flag and becomes the hunted!  While this game sounds simple, this was my first time working with **patching ballancing issues**.  There were many ways the hunted could break the game, including but not limited to:
- Towering and camping in the sky
- Getting in a boat and going in circles forever
- Digging underground and mining while placing cobblestone behind themselves (which takes longer to mine so they always got away)
- Simply hiding somewhere

All of these were fixed in ways that integrated well into the game.  
The towering issue was fixed by adding a build limit.  The boat was fixed by giving the hunters dolphins grace when the hunted was in a boat.  The digging was fixed by adding a pickaxe that when held by a hunter, broke 5 blocks in a line, but when held by the hunted, only broke 3.  This allowed people to catch up to the hunted.  The hiding issue was fixed by just adding an arrow in the action bar that pointed to the hunted, and by giving the hunted a glowing effect.  

This was also my first partener programming project, since Lily (https://github.com/My-Name-Is-Jeff) joined in on it.  They added lots of cool features, and helped significantly with my learning of kotlin since they are very strong with kotlin.  This was their first Minecraft plugin (if I remember correctly), so we played off each other's skills and weaknesses well and learned a lot!

**KitPVP** (https://github.com/Yoursole1/KitPvP)

This was my first project where I was commissioned.  It was made for the Youtuber Voxil (https://www.youtube.com/c/Voxil).  This project was when I started learning how to meet deadlines for projects.  I also expanded my NMS (net.minecraft.server) knowledge significantly for this project.  This project included making a custom economy system, many custom GUIs, custom mobs, player abilities, and lots of ballancing.  This was also the first project where config files were super important and had to be organized.  I just learned a lot about good game design and making open-ended games!

**Turtle SMP** (https://github.com/Yoursole1/TurtleSMP)

This was a simple plugin asked for by tert (https://www.youtube.com/c/Turtilz) for an SMP to stream on.  It wasn't a payed project because it was super easy and fun to make.  It included a lives system where you would get a life every 3 hours of playtime, and a few QOL adjustments.  

**Guild SMP Plugin** (https://github.com/Yoursole1/QuackingSMPPlugin)

This was a plugin that was lots of QOL changes for my guild's SMP, as well as a chat linked between the discord and the server.  My favorite features from this project were a graph you could view in discord that shows the top ten blocks broken on the server.  It also included an account verification system that allows server OPs to access there permissions from the discord to moderate.  This plugin is actually still in use on the server and hasn't needed a bug fix or update for months.  I think this might be the longest running project without restarting I have ever made. 

**Other Projects!**

If they aren't here, they are either too small or already pinned on my profile.  Thanks for reading!
