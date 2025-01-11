## 2014 - Bukkit is dead, long live Sponge...Spigot?

### Paid Plugins and Monetisation

On the [16th of April 2014](https://www.spigotmc.org/threads/did-you-know-google-authenticator-premium-resources.16306/), Spigot launched a section of their resources site that allowed developers to charge for plugins. This decision was highly divisive within the Minecraft community, with many being firmly either for or against it. Shortly after, [MCMarket.org](https://www.mc-market.org/) launched on the 30th of July. Unlike Spigot Resources, MCMarket was home to all kinds of transactions. It became common to see people trading worlds, plugins, or even entire servers. MCMarket also allowed players to trade Minecraft accounts, contrary to the terms of use for the game, and therefore developed a negative reputation in some areas of the community.

Prior to these marketplaces, the most common forms of making money in the server scene for anyone other than server owners were to create custom plugins or builds for servers in exchange for money. This system opened the ability to publicly sell plugins, for better or for worse. This development also led to the creation of a few Minecraft piracy websites, that have been riddled with controversy and malware outbreaks. There have also been many controversial implementations of DRM by plugin developers.

### PaperSpigot

The PaperSpigot project was started by gsand and Z750 on the [23rd of June 2014](https://github.com/PaperMC/Paper/commit/b9179a0a04ab1fa4e95e88aa59cdebc9c73dc433). While initially created for fun, the project became more serious after Spigot became reluctant to accept many community contributions. To separate themselves from Spigot, they later rebranded to Paper, stripping the Spigot part of their name. Paper worked on including significant performance improvements into the Minecraft server, going far beyond that of Spigot. They also strived to be much more community oriented, and more open to contributions.

### EngineHub

On the 5th of July 2014, sk89q created an organisation known as [EngineHub](https://enginehub.org/). All of his plugins and libraries were transferred to EngineHub to reflect what had been a slow transition to a more community-led development style. This included WorldEdit, WorldGuard, CraftBook, CommandBook, and more. As sk89q had not been the only one working on these plugins for most of their existence, this allowed sk89q to step back from the projects. EngineHub’s software is now mainly developed by [Me4502](https://madelinemiller.dev/contact/), octylFractal, and wizjany.

### The Death of Bukkit

On the 21st of August 2014, EvilSeph announced that the Bukkit project was shutting down. He cited reasons such as the legal grey area that the project was in, and that the API was old and incompatible with the future of Minecraft. [Shortly after](http://web.archive.org/web/20140909045841/https://storify.com/lukegb/the-tale-of-bukkit-for-minecraft-1-8), Mojang announced that they had owned the Bukkit project since the original Bukkit team was hired in 2012. This was a shock to the community, leaving many long-time Bukkit contributors feeling betrayed as this was never made public. It was a widespread belief that they were contributing to a community project, not a project owned by a major company. Dinnerbone and Grum announced that they would be updating the Bukkit project while reiterating that Bukkit would not be the official modding API.

On the [5th of September 2014](https://github.com/github/dmca/blob/master/2014/2014-09-05-CraftBukkit.md), GitHub received a DMCA (Digital Millenium Copyright Act) claim over his contributions to the CraftBukkit project and all forks that contained changes beyond the 25th of January 2012. Due to this, CraftBukkit, Spigot, and all related projects were taken down from GitHub. Consequently Dinnerbone and Grum were unable to update Bukkit, as there were legal implications of doing so. At this point, the Bukkit project was officially dead.

### From the Ashes, #nextstep rises

Amid the panic, many key members of the Minecraft community banded together to discuss what should happen now that Bukkit is gone. A plan and time were set for the meeting, and a document distributed to the community. The discussions took place between the 5th and 7th of September and eventually led to a new project forming under the name Sponge. The project leads for the Sponge project were Blood, Zidane, and sk89q.

Initial goals for the Sponge API were to build a modern API that was more in line with the way Minecraft worked at the time compared to Bukkit, which was very much showing its age. Sponge was to be implemented on top of Forge and would allow plugins to work natively alongside mods. On the [7th of September 2014](https://github.com/SpongePowered/SpongeAPI/commit/5a96c646c017fb853ee0260ca2c213445e7acdd6), the first commit to the Sponge API was made. Sponge’s API, while similar to Bukkit in some ways and very different in others, very quickly became more powerful than Bukkit. Borrowing heavily from Spout, WorldEdit, and WorldGuard, the Sponge API was a real community project. While the API came quickly, the actual server software was not ready for some time.

Alongside development on the Sponge API, another group started work on the MythicAPI on the [8th of September 2014](https://github.com/jamierocks/Granite/commit/47d23d16545e7975f14dc5fc32ca9e7015dad0e1). The API did not last long and eventually the project became an implementation of the Sponge API on a vanilla server, like what CraftBukkit was for Bukkit. This project then became known as Granite.

On the [28th of November 2014](https://www.spigotmc.org/threads/bukkit-craftbukkit-spigot-1-8.36598/), Spigot released a 1.8 version of CraftBukkit and Spigot. This release was the first time that the Spigot team had updated CraftBukkit themselves and marked a shift that led to Spigot gaining market dominance as the de facto implementation of Bukkit.
