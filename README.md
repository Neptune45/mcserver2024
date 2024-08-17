# Overview
Follow the below steps to configure your Minecraft to work with the Borderbands server

# Prerequisites
- [Minecraft](https://www.minecraft.net/en-us/download)
- [JDK 21](https://www.oracle.com/java/technologies/downloads/#java21)
- [CurseForge (Standalone)](https://www.curseforge.com/download/app#download-options)
    - Can go with [Forge](https://files.minecraftforge.net/net/minecraftforge/forge/index_1.20.1.html) as well. Setting that up is similar but will not be outlined in this doc.

# Setting Up the ModPack
1. Minecraft should already populate in the left navigation bar. If not click: \
"+" > Scan Computer for games > Select Drive Minecraft is on > Scan
2. Click into Minecraft, then click "+ Create". Minecraft version is 1.20.1, Game Type is Forge, and leave the modloader version at default
3. While in your new modpack, hit the hotdog menu next to the "Play" button, then select "Open Folder". A File Explorer window should then show up. Take note of the "mods" folder and its location on your computer
4. [Download the mods folder in the repo.](https://download-directory.github.io/?url=https%3A%2F%2Fgithub.com%2FNeptune45%2Fmcserver2024%2Ftree%2Fmain%2Fmods) This website takes everything from the "mods" folder on the repo, compresses, and downloads it
5. Extract all the contents of the .zip file into the "mods" folder that should have shown in Step 3. There should be 260 mods shown in CurseForge once this is done
6. Go to the Hotdog menu, then uncheck "Use System Memory Settings": \
    > <b><p style="text-align:center">Memory Requirements</p></b>
    > <br>
    > <b>Minimum: 4GB (4096MB)</b> <br>
    > &nbsp;&nbsp;&nbsp;&nbsp;This is a good starting point and usually the default setting in CurseForge. If you're noticing slow performance, it's recommended to take note of your memory usage while playing Minecraft using Task Manager/Activity Monitor and slowly raise your memory usage until the performance is playable for you. \
    > \
    > **Recommended: 8GB+ (8192MB)** \
    > &nbsp;&nbsp;&nbsp;&nbsp;For a guaranteed smooth experience, it's generally recommended to allocate at least 8GB of RAM to your Minecraft client. \
    > \
    > **WARNING**: \
    > &nbsp;&nbsp;&nbsp;&nbsp;Make sure to leave at least 1GB of memory free for your OS to avoid instability in your computer while playing Minecraft. To find the amount of RAM you have, first take note of your computer's memory usage at startup + any apps you know you're going to have running like Discord, web browser, Spotify, etc. We'll call this BASE. The amount of memory you can use for Minecraft is as follows: **Usable Memory = Total Memory - BASE - 1GB**
7. Hit Play and a Forge version of Minecraft should open up. It's expected for your client to stop responding multiple times while loading, so don't worry if it looks like it's crashing.
8. Ask the server host for the IP to connect to
