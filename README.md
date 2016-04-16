# BuildPortals
Bukkit/Spigot server plugin to allow players to build their own inter-world portals without the use of commands. These portals do not currently support teleporting players with horses or other vehicle-class objects they are riding; I'm trying to find a way to get around some issues there...

April 16, 2016:

Status:

This project is at a pre-release. It is being beta-tested on a small server before posting to the greater community. I have a couple of bugs to work out before an official release.

Use:

Once installed, any player can build a portal using a designated portal building material (Emerald Blocks by default) in a nether-portal-like rectangle, with at least large enough interior for a player to walk through and place an 'activator block' (any of Redstone blocks, Gold blocks or Diamond blocks by default) on each bottom block along the interior of the portal. They then build another portal where they would like to connect, placing matching 'activator block's in this portal. Once two complete and like-activated portals are built, the plugin converts the portal interior (including activator blocks) to air and links the portals! Each portal can be built by any player, in any world. Portals activated with each material can be started independently with no conflict issues.

The plugin does support in-game configuration changes now:

 * '/BP SetMaterial \<MaterialName\>' - You can change the portal frame material. This will convert all existing portals to the new material and also allow building new portals from the new named material.
 
 * '/BP AddActivator \<MaterialName\>' - You can add a new activator material. This allows activating portals with a new block.
 
 * '/BP RemoveActivator \<MaterialName\>' - You can remove an activator material. This will disallow activating portals with the named material.
 
 * '/BP ListActivators \<MaterialName\>' - This will list all currently configured activator materials. 

Planned updates:
 * Support for minecart / horse teleportation.

If someone happens across this project, feel free to critique. I welcome tips/criticism/suggestions!
