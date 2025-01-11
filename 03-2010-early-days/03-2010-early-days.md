# 2010 - The Early Days

## Survival Multiplayer Releases

Minecraft Alpha 1.0.15 was the first post-Classic version of what is now known as Minecraft Java Edition to have support for multiplayer. While 1.0.15 released on the 3rd of August 2010, it wasn’t until one day later on the [4th of August](https://minecraft.wiki/w/Java_Edition_Alpha_v1.0.15) that the server software was released. As Minecraft Classic lacked survival multiplayer, crafting, and many other aspects of what people consider integral to Minecraft, this was considered by many to be the first true version of the game with multiplayer. This release was the start of Minecraft multiplayer as we know it today.

## MinecraftOnline

On the same day as the survival multiplayer release, a group of people created a server by the name of [MinecraftOnline](https://minecraftonline.com/). After two days of private testing, the server released on the [6th of August 2010](https://minecraftonline.com/wiki/Timeline#2010). While not technically the oldest server still running, due to NerdNu existing during the Minecraft Classic era, MinecraftOnline launched on modern Minecraft before NerdNu did. Due to this, it is the longest-running server for what we now know as Minecraft Java Edition. As of writing, MinecraftOnline is running CanaryMod on Minecraft 1.7.10.

## LlamaGrief, the first Anti-Grief mod

Two days after multiplayer launched, on the [6th of August 2010](https://www.minecraftforum.net/forums/support/server-support-and/1891859-llamacraft-finally-compatible-with-1-2_01), a mod by the name of LlamaGrief was released by SuperLlama. This mod was the first anti-grief mod. It allowed server administrators to prevent common grief tactics such as starting fires, spamming lava, or spamming bedrock (commonly referred to as adminium at the time). Unlike today, this was not a plugin that could be installed simply to the server. LlamaGrief was a jar mod, installed by copying the modified game files into the `minecraft_server.jar` file and deleting the Java metadata folder (`META-INF`).

## Server Wrappers

Before plugins were around to handle kits and broadcast the server rules, a few projects popped up that wrapped the Minecraft server and listened for various lines of text in the chat. The wrappers would then send console commands based on what it saw, such as giving the player a few items for kits or sending the player a message outlining the rules. The earliest wrapper to our knowledge was Czahrien’s wrapper from [early August 2010](https://www.minecraftforum.net/forums/archive/alpha/alpha-survival-multiplayer/821874-czahrien-wrapper-continued-6-0). Afterwards, many others started continuation or spiritual successor projects. Server wrappers in this form did not last too long, as they were quickly made redundant by the existence of plugins. Another noteworthy wrapper that had existed from the [11th of August 2010](https://www.minecraftforum.net/forums/support/server-support-and/1891879-mcadmin-revision-109) was MCAdmin by Doridian.

## Lightstone

On the [17th of August 2010](https://github.com/grahamedgecombe/lightstone/commit/40ea853af917928188f1431e2a4b8d2c2f9f078d), Graham Edgecombe started the Lightstone project. Named after what glowstone was commonly known as at the time, this project aimed to create a customisable Minecraft server without using any of Mojang’s code. Due to its highly ambitious nature, it did not last very long. However, many future projects used Lightstone as a base, some of which still exist to this day.

## hMod

On the [3rd of September 2010](https://github.com/traitor/Minecraft-Server-Mod/commit/6315f5aa834a9f0dac9a99d45e4e65af56d1d227), hey0 started work on a project known as Minecraft-Server-Mod, later rebranded as hMod. While hey0 only worked on this for a few months, this project was a significant leap forward in terms of what a Minecraft server could do. hMod was the first project that allowed “plugins” to be loaded onto the Minecraft server, with an API that wouldn’t require substantial changes on each Minecraft version. hMod also provided a small set of inbuilt features to help run a server, such as admin commands, extra configuration options to control how the game behaves, and a permissions system to manage what players can do.

## The hMod Plugins

On the [28th of September 2010](https://github.com/EngineHub/WorldEdit/commit/83fea4d00ce1b7a0f456f207a3d5d453fc5f8dd4), sk89q started work on the [WorldEdit](https://enginehub.org/worldedit) project. The goal of WorldEdit was to allow the player to quickly set large numbers of blocks to speed up the building process. While initially very different from what it is now, the project soon took shape and started to resemble what it is today.

Due to an initial lack of interest in WorldEdit, sk89q started work on a plugin to make survival servers more fun for players. On the [22nd of October 2010](https://github.com/EngineHub/CraftBook/commit/83cdfc151c2c0a589506e3c88c8f266c5a9ebcd8), he began work on the [CraftBook](https://enginehub.org/craftbook) project. CraftBook introduced a number of gameplay mechanics, such as bridges and gates that could be opened and closed, elevators that could transport the player, and advanced redstone components (referred to as Integrated Circuits). In a successful attempt to bring more users to WorldEdit, he made CraftBook depend upon WorldEdit. Interestingly, sk89q intended to move the Integrated Circuits feature out to a separate plugin called ReIC. However, this never happened, and instead, CraftBook absorbed the improvements made for ReIC. CraftBook was one of the most popular, if not the most popular, Minecraft plugin in the hMod era of Minecraft.

Shadeness started the Towny project on the [25th of October 2010](https://sites.google.com/site/townymod/hmod/downloads). This plugin allowed the creation of towns, with a full resident and war system. Towny also integrated world protection, preventing players from destroying a town they did not belong to. This plugin fundamentally introduced a new style of server gameplay that’s still seen to this day.

On the [30th of October 2010](https://github.com/bootswithdefer/LogBlock/commit/1d7092ab83cb0ed5d1e0c07dc3c7675684738eee), bootswithdefer started the [LogBlock](https://dev.bukkit.org/projects/logblock) project. LogBlock logged who broke or placed each block, and allowed an admin to look up the information. Block logging was significant for the server admin community, as before this point, it was impossible to accurately determine who griefed an area without a reliable witness. LogBlock also later gained a rollback command, which has made its way into every major block logging plugin created since.

To protect his server, sk89q started work on a project called [WorldGuard](https://enginehub.org/worldguard) on the [14th of November 2010.](https://github.com/EngineHub/WorldGuard/commit/3aa265b55355813ab18ba5c1ed742c614894fc72) WorldGuard allowed server admins to protect certain regions of the world, such as the spawn or a town. The plugin also allowed preventing various forms of damage to the environment from both players and monsters. There were initially plans to split out the region functionality to a separate plugin called RegionBook, and only have WorldGuard handle the protection of the regions, but this idea was scrapped.

On the [24th of November 2010](https://github.com/alecgorge/jsonapi/commit/048b567b69844256bc579ab83425c259117d3552), Alec Gorge created a plugin called JSONAPI. JSONAPI was the first plugin to provide a way for external services to control a server fully. With JSONAPI, websites or other applications could change just about anything, from giving a player armour to setting trees on fire. One notable application that made use of JSONAPI was the Adminium mobile app, named after an early term for the bedrock block, which allowed full management of a Minecraft server from a mobile phone.

On the [2nd of December 2010](https://github.com/Hidendra/LWC/tree/bc76dbb7279d22091f03948951df228540d49db1), Hidendra started work on the LWC plugin. LWC provided lightweight protection for chests, allowing players to protect each of their chests individually. At this stage, LWC provided the most granular form of block protection for players by providing private chests.

Started on the [4th of December 2010](https://github.com/webbukkit/dynmap/commit/af18b7390848e3486fb636f3577e0e6826b4c515) by FrozenCow, Dynmap created Google Maps-like websites for Minecraft servers. Before Dynmap was created, there was no easy way for a Minecraft server to show off their world without someone joining the server.

On the [15th of December 2010](https://github.com/nijikokun/iConomy/commit/2e17e51cd6ce86399924bf9b0bf37bd10a44dc69), Nijikokun started work on the iConomy plugin. iConomy was the first major plugin to allow players to own in-game fiat currency, providing an alternative to trading with physical items. This was the catalyst that allowed the popular Economy server gamemode to flourish.

At an unknown point during 2010, SuperLlama of LlamaGrief fame also started the hMod plugin Runecraft. This was the first magic plugin for Minecraft, consisting of placing physical “runes” on the ground in the form of specific patterns of Minecraft blocks, akin to a physical crafting table grid. These runes could trigger a tonne of different effects on the game world such as types of protection enchantments to protect the player or moving and replacing blocks to unveil hidden passageways.

## ModloaderMP

At the time, Risugami’s Modloader was the go-to method of making or installing mods for Minecraft. If you wanted to use those mods with friends, however, things were significantly more complicated. To combat this, ScottyDoesKnow (also known as SDK), released a mod called ModloaderMP on the [24th of November 2010](https://www.minecraftforum.net/forums/mapping-and-modding-java-edition/minecraft-mods/1272343-1-3-2-sdks-mods-v1-aug-18th-modloadermp-updated). The goal of ModloaderMP was to provide a Modloader-like environment on the server, making it much easier to both make and install server versions of mods made for Modloader. This was the first project that brought mods that add content such as blocks, items, or mobs to multiplayer in a simple way. While this project brought content mods to multiplayer, mod developers still had to put in significantly extra work to maintain the multiplayer version alongside the singleplayer version of their mod. Most mods were still only available in singleplayer.

## 2b2t

The infamous anarchy server 2b2t (short for 2builders2tools) launched on the [17th of December 2010](https://en.wikipedia.org/wiki/2b2t). 2b2t is the oldest running anarchy server, a multiplayer game mode with little to no rules that allows players to do almost whatever they want to do. This server has a very in-depth history of its own and has been covered in multiple media outlets. For an extensive timeline of 2b2t, see [here](https://2b2t.miraheze.org/wiki/Timeline). The server is still running to this day and remains the most well-known anarchy server.

## Minecraft Beta

Towards the end of 2010, Mojang published the first beta release of Minecraft. Minecraft Beta 1.0 launched on the [20th of December 2010](https://minecraft.wiki/w/Java_Edition_Beta_1.0). This update was a significant improvement for server admins, significantly improving security and making survival gameplay vastly more stable. This update moved the player’s inventory from being controlled by the client to the server, removing the ability to cheat in items with a cheat client. Before this change, enforcing survival gameplay was pretty much impossible.

## The Death of hMod and the Rise of Bukkit

Only a few months after the release of hMod, hey0 stopped working on it, and a new team comprised of many prolific hMod plugin developers took his place. After a short time, the team that took over hMod decided that starting a new project based on the learnings from hMod would be a better idea. On the [21st of December 2010](https://github.com/Bukkit/Bukkit/commit/4e8311a6551e8d7794cff73c57a481251b47459c), work on the Bukkit project officially commenced with a development team made up of EvilSeph, Dinnerbone, Grum, Tahg, and sk89q.

Initial reactions to the news were generally positive, with most of the hMod community having trust in the developers of Bukkit after having seen their work on hMod and hMod plugins. A small segment of the community disagreed that hMod wasn’t worth continuing and continued to update it themselves as a fork. This was the first split in the server community, albeit a minor one. Most servers and developers followed the Bukkit project into 2011.
