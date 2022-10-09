## Hello World! (and a little about me)

I am a developing developer that lives in Washington State in the US!  I originally got into computer science as a way to experiment more with my passion for math, which is still my absolute favorite thing to do!  I also love piano, and love composing music for my family and friends :D

## My Projects

*For many of these the code is still private but the results are public.  I am also working on some other cool projects that can't be here quite yet ):*

**Capture the Flag** (https://github.com/Yoursole1/CTF)

I started this project as my first real minecraft minigame.  It was also my first real kotlin project.  Mechanically, it is quite similar to UHC, but also includes teamwork aspects as players try to hunt each other down.  The game starts with a 15-30 minute grace period, where everyone gathers gear, crafts custom items, and learns the mechanics.  The flag then drops from a random location inside the generated game region.  Whoever picks up the flag first becomes the "hunted", and everyone else is a "hunter".  The longer the hunted holds the flag, the more points they get.  Whoever kills them gets the flag and becomes the hunted!  While this game sounds simple, this was my first time working with **patching ballancing issues**.  There were many ways the hunted could break the game, including but not limited to:
- Towering and camping in the sky
- Getting in a boat and going in circles forever
- Digging underground and mining while placing cobblestone behind themselves (which takes longer to mine so they always got away)
- Simply hiding somewhere
All of these were fixed in ways that integrated well into the game.  
The towering issue was fixed by adding a build limit.  The boat was fixed by giving the hunters dolphins grace when the hunted was in a boat.  The digging was fixed by adding a pickaxe that when held by a hunter, broke 5 blocks in a line, but when held by the hunted, only broke 3.  This allowed people to catch up to the hunted.  The hiding issue was fixed by just adding an arrow in the action bar that pointed to the hunted, and by giving the hunted a glowing effect.  

This was also my first partener programming project, since Lily (https://github.com/My-Name-Is-Jeff) joined in on it.  They added lots of cool features, and helped significantly with my learning of kotlin since they are very strong with kotlin.  This was their first Minecraft plugin (if I remember correctly), so we played off each other's skills and weaknesses well and learned a lot!
