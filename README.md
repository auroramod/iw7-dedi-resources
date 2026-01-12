# IW7 Dedicated Server Resources

This repository contains the IW7 Dedicated Server config files and scripts to easily start a server. [To setup a IW7 Dedicated Server, check out the official guide here.](https://docs.auroramod.dev/iw7-server-guide)

If you are looking to modify the server config to your liking:
1. Go to **iw7-mod** folder, and open the **server.cfg** *(if zombies, do server_zm.cfg)* in a text editor of your choice, like Notepad.
2. Scroll through the list of dvars, and change your values out. This includes hostname, password if you want, a rcon_password, the map rotation, and more!

If you are looking to modify the server starter .bat script:
1. Go to the .bat, right click, and click "Edit".
2. There, you can change your config name, port, or mod folder of choice.

### iw7-mod/custom_scripts/

Inside this directory contains 3 folders for Zombies, Multiplayer, or both. Each folder has a blank GSC script that will load if the conditions are met and if code exists.

### Questions

If you have any questions or concerns, feel free to [join the Discord server](https://auroramod.dev/discord) and talk in #iw7-server-support.
