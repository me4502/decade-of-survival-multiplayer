# Foreword

Minecraft is a game that has thrived in part due to its community. I've
been a part of the Minecraft server community for well over a decade as
of publishing, and I've seen the community grow and change many times
over. In 2020, for the tenth anniversary of the launch of multiplayer, I
decided to write a comprehensive history of the Minecraft server
community. With help from many community members, many of whom have had
a large part in shaping the events that I've written about in this book,
I've compiled this comprehensive history of the Minecraft server
community's first decade.

This book was [originally published as a blog
article](https://madelinemiller.dev/blog/decade-of-minecraft-multiplayer/)
on the 4th of August 2020, the tenth anniversary of survival multiplayer
in Minecraft. I've chosen to publish this as an eBook due to numerous
requests over the years for an offline-readable version of the article.
While the following chapters have been edited and expanded to include
more information and improve the flow, care was taken to ensure that the
book remains true to the time it was originally posted.

In saying that, if there is anything we have missed that you feel
substantially impacted the survival multiplayer ecosystem, please
[contact me.](https://madelinemiller.dev/contact/) Also, while we've
tried our hardest to make sure these dates are accurate and cited. As
with anything historical, it is not always possible to be entirely
accurate due to conflicting or lost sources. If you find something that
you can verify is incorrect, please [let me
know](https://madelinemiller.dev/contact/) and I'll make sure to get it
fixed.

# 2009 - Prehistory

## Minecraft Classic

Minecraft wouldn't be where it is today without the version that came
beforehand. Minecraft Classic, which was known at the time as Minecraft
Alpha, underwent a series of releases referred to as [multiplayer
tests](https://minecraft.wiki/w/Java_Edition_Multiplayer_Test). The
first of these multiplayer tests that included standalone multiplayer
server software was released all the way back in 2009, on the [7th of
June](https://minecraft.wiki/w/Java_Edition_Classic_0.0.16a). Minecraft
was very different at this time, being a small in-browser game with a
small following. Two of Minecraft's most well-known features, crafting
and survival mode, were absent at this time with gameplay vaguely like a
heavily simplified modern creative mode.

## NerdNu

Out of everything that happened during the Minecraft Classic era, one
notable server launched that is still online to this day.
[NerdNu](https://nerd.nu/) originally launched as the Minecraft
subreddit's public Minecraft server with `c.nerd.nu`, and later
`s.nerd.nu`. This server first launched on the 10th of June 2009.
Therefore, this is the oldest Minecraft server to be still running.

## WikiVG and #mcdevs

With a growing interest in Minecraft server modding, a few community
members started a project to document the technical aspects of the game.
Thus, [wiki.vg](https://wiki.vg) and the #mcdevs IRC channel were born.
Initially launched at an [unknown time in
2009](https://paste.gg/p/zml/d029ee160daf45a78898319a8bfad5f2) at the
URL `wiki.tkte.ch`, with an effort to document the game's protocol
started shortly after. The wiki migrated to the domain where it then
resided on the [24th of October
2010](https://wiki.vg/index.php?title=Main_Page&offset=&limit=500&action=history).
The IRC channel also underwent a migration to
[Freenode](https://freenode.net/) at a similar time. To this day, the
WikiVG project is the go-to place for technical information about
Minecraft.

# 2010 - The Early Days

## Survival Multiplayer Releases

Minecraft Alpha 1.0.15 was the first post-Classic version of what is now
known as Minecraft Java Edition to have support for multiplayer. While
1.0.15 released on the 3rd of August 2010, it wasn't until one day later
on the [4th of
August](https://minecraft.wiki/w/Java_Edition_Alpha_v1.0.15) that the
server software was released. As Minecraft Classic lacked survival
multiplayer, crafting, and many other aspects of what people consider
integral to Minecraft, this was considered by many to be the first true
version of the game with multiplayer. This release was the start of
Minecraft multiplayer as we know it today.

## MinecraftOnline

On the same day as the survival multiplayer release, a group of people
created a server by the name of
[MinecraftOnline](https://minecraftonline.com/). After two days of
private testing, the server released on the [6th of August
2010](https://minecraftonline.com/wiki/Timeline#2010). While not
technically the oldest server still running, due to NerdNu existing
during the Minecraft Classic era, MinecraftOnline launched on modern
Minecraft before NerdNu did. Due to this, it is the longest-running
server for what we now know as Minecraft Java Edition. As of writing,
MinecraftOnline is running CanaryMod on Minecraft 1.7.10.

## LlamaGrief, the first Anti-Grief mod

Two days after multiplayer launched, on the [6th of August
2010](https://www.minecraftforum.net/forums/support/server-support-and/1891859-llamacraft-finally-compatible-with-1-2_01),
a mod by the name of LlamaGrief was released by SuperLlama. This mod was
the first anti-grief mod. It allowed server administrators to prevent
common grief tactics such as starting fires, spamming lava, or spamming
bedrock (commonly referred to as adminium at the time). Unlike today,
this was not a plugin that could be installed simply to the server.
LlamaGrief was a jar mod, installed by copying the modified game files
into the `minecraft_server.jar` file and deleting the Java metadata
folder (`META-INF`).

## Server Wrappers

Before plugins were around to handle kits and broadcast the server
rules, a few projects popped up that wrapped the Minecraft server and
listened for various lines of text in the chat. The wrappers would then
send console commands based on what it saw, such as giving the player a
few items for kits or sending the player a message outlining the rules.
The earliest wrapper to our knowledge was Czahrien's wrapper from [early
August
2010](https://www.minecraftforum.net/forums/archive/alpha/alpha-survival-multiplayer/821874-czahrien-wrapper-continued-6-0).
Afterwards, many others started continuation or spiritual successor
projects. Server wrappers in this form did not last too long, as they
were quickly made redundant by the existence of plugins. Another
noteworthy wrapper that had existed from the [11th of August
2010](https://www.minecraftforum.net/forums/support/server-support-and/1891879-mcadmin-revision-109)
was MCAdmin by Doridian.

## Lightstone

On the [17th of August
2010](https://github.com/grahamedgecombe/lightstone/commit/40ea853af917928188f1431e2a4b8d2c2f9f078d),
Graham Edgecombe started the Lightstone project. Named after what
glowstone was commonly known as at the time, this project aimed to
create a customisable Minecraft server without using any of Mojang's
code. Due to its highly ambitious nature, it did not last very long.
However, many future projects used Lightstone as a base, some of which
still exist to this day.

## hMod

On the [3rd of September
2010](https://github.com/traitor/Minecraft-Server-Mod/commit/6315f5aa834a9f0dac9a99d45e4e65af56d1d227),
hey0 started work on a project known as Minecraft-Server-Mod, later
rebranded as hMod. While hey0 only worked on this for a few months, this
project was a significant leap forward in terms of what a Minecraft
server could do. hMod was the first project that allowed "plugins" to be
loaded onto the Minecraft server, with an API that wouldn't require
substantial changes on each Minecraft version. hMod also provided a
small set of inbuilt features to help run a server, such as admin
commands, extra configuration options to control how the game behaves,
and a permissions system to manage what players can do.

## The hMod Plugins

On the [28th of September
2010](https://github.com/EngineHub/WorldEdit/commit/83fea4d00ce1b7a0f456f207a3d5d453fc5f8dd4),
sk89q started work on the [WorldEdit](https://enginehub.org/worldedit)
project. The goal of WorldEdit was to allow the player to quickly set
large numbers of blocks to speed up the building process. While
initially very different from what it is now, the project soon took
shape and started to resemble what it is today.

Due to an initial lack of interest in WorldEdit, sk89q started work on a
plugin to make survival servers more fun for players. On the [22nd of
October
2010](https://github.com/EngineHub/CraftBook/commit/83cdfc151c2c0a589506e3c88c8f266c5a9ebcd8),
he began work on the [CraftBook](https://enginehub.org/craftbook)
project. CraftBook introduced a number of gameplay mechanics, such as
bridges and gates that could be opened and closed, elevators that could
transport the player, and advanced redstone components (referred to as
Integrated Circuits). In a successful attempt to bring more users to
WorldEdit, he made CraftBook depend upon WorldEdit. Interestingly, sk89q
intended to move the Integrated Circuits feature out to a separate
plugin called ReIC. However, this never happened, and instead, CraftBook
absorbed the improvements made for ReIC. CraftBook was one of the most
popular, if not the most popular, Minecraft plugin in the hMod era of
Minecraft.

Shadeness started the Towny project on the [25th of October
2010](https://sites.google.com/site/townymod/hmod/downloads). This
plugin allowed the creation of towns, with a full resident and war
system. Towny also integrated world protection, preventing players from
destroying a town they did not belong to. This plugin fundamentally
introduced a new style of server gameplay that's still seen to this day.

On the [30th of October
2010](https://github.com/bootswithdefer/LogBlock/commit/1d7092ab83cb0ed5d1e0c07dc3c7675684738eee),
bootswithdefer started the
[LogBlock](https://dev.bukkit.org/projects/logblock) project. LogBlock
logged who broke or placed each block, and allowed an admin to look up
the information. Block logging was significant for the server admin
community, as before this point, it was impossible to accurately
determine who griefed an area without a reliable witness. LogBlock also
later gained a rollback command, which has made its way into every major
block logging plugin created since.

To protect his server, sk89q started work on a project called
[WorldGuard](https://enginehub.org/worldguard) on the [14th of November
2010.](https://github.com/EngineHub/WorldGuard/commit/3aa265b55355813ab18ba5c1ed742c614894fc72)
WorldGuard allowed server admins to protect certain regions of the
world, such as the spawn or a town. The plugin also allowed preventing
various forms of damage to the environment from both players and
monsters. There were initially plans to split out the region
functionality to a separate plugin called RegionBook, and only have
WorldGuard handle the protection of the regions, but this idea was
scrapped.

On the [24th of November
2010](https://github.com/alecgorge/jsonapi/commit/048b567b69844256bc579ab83425c259117d3552),
Alec Gorge created a plugin called JSONAPI. JSONAPI was the first plugin
to provide a way for external services to control a server fully. With
JSONAPI, websites or other applications could change just about
anything, from giving a player armour to setting trees on fire. One
notable application that made use of JSONAPI was the Adminium mobile
app, named after an early term for the bedrock block, which allowed full
management of a Minecraft server from a mobile phone.

On the [2nd of December
2010](https://github.com/Hidendra/LWC/tree/bc76dbb7279d22091f03948951df228540d49db1),
Hidendra started work on the LWC plugin. LWC provided lightweight
protection for chests, allowing players to protect each of their chests
individually. At this stage, LWC provided the most granular form of
block protection for players by providing private chests.

Started on the [4th of December
2010](https://github.com/webbukkit/dynmap/commit/af18b7390848e3486fb636f3577e0e6826b4c515)
by FrozenCow, Dynmap created Google Maps-like websites for Minecraft
servers. Before Dynmap was created, there was no easy way for a
Minecraft server to show off their world without someone joining the
server.

On the [15th of December
2010](https://github.com/nijikokun/iConomy/commit/2e17e51cd6ce86399924bf9b0bf37bd10a44dc69),
Nijikokun started work on the iConomy plugin. iConomy was the first
major plugin to allow players to own in-game fiat currency, providing an
alternative to trading with physical items. This was the catalyst that
allowed the popular Economy server gamemode to flourish.

At an unknown point during 2010, SuperLlama of LlamaGrief fame also
started the hMod plugin Runecraft. This was the first magic plugin for
Minecraft, consisting of placing physical "runes" on the ground in the
form of specific patterns of Minecraft blocks, akin to a physical
crafting table grid. These runes could trigger a tonne of different
effects on the game world such as types of protection enchantments to
protect the player or moving and replacing blocks to unveil hidden
passageways.

## ModloaderMP

At the time, Risugami's Modloader was the go-to method of making or
installing mods for Minecraft. If you wanted to use those mods with
friends, however, things were significantly more complicated. To combat
this, ScottyDoesKnow (also known as SDK), released a mod called
ModloaderMP on the [24th of November
2010](https://www.minecraftforum.net/forums/mapping-and-modding-java-edition/minecraft-mods/1272343-1-3-2-sdks-mods-v1-aug-18th-modloadermp-updated).
The goal of ModloaderMP was to provide a Modloader-like environment on
the server, making it much easier to both make and install server
versions of mods made for Modloader. This was the first project that
brought mods that add content such as blocks, items, or mobs to
multiplayer in a simple way. While this project brought content mods to
multiplayer, mod developers still had to put in significantly extra work
to maintain the multiplayer version alongside the singleplayer version
of their mod. Most mods were still only available in singleplayer.

## 2b2t

The infamous anarchy server 2b2t (short for 2builders2tools) launched on
the [17th of December 2010](https://en.wikipedia.org/wiki/2b2t). 2b2t is
the oldest running anarchy server, a multiplayer game mode with little
to no rules that allows players to do almost whatever they want to do.
This server has a very in-depth history of its own and has been covered
in multiple media outlets. For an extensive timeline of 2b2t, see
[here](https://2b2t.miraheze.org/wiki/Timeline). The server is still
running to this day and remains the most well-known anarchy server.

## Minecraft Beta

Towards the end of 2010, Mojang published the first beta release of
Minecraft. Minecraft Beta 1.0 launched on the [20th of December
2010](https://minecraft.wiki/w/Java_Edition_Beta_1.0). This update was a
significant improvement for server admins, significantly improving
security and making survival gameplay vastly more stable. This update
moved the player's inventory from being controlled by the client to the
server, removing the ability to cheat in items with a cheat client.
Before this change, enforcing survival gameplay was pretty much
impossible.

## The Death of hMod and the Rise of Bukkit

Only a few months after the release of hMod, hey0 stopped working on it,
and a new team comprised of many prolific hMod plugin developers took
his place. After a short time, the team that took over hMod decided that
starting a new project based on the learnings from hMod would be a
better idea. On the [21st of December
2010](https://github.com/Bukkit/Bukkit/commit/4e8311a6551e8d7794cff73c57a481251b47459c),
work on the Bukkit project officially commenced with a development team
made up of EvilSeph, Dinnerbone, Grum, Tahg, and sk89q.

Initial reactions to the news were generally positive, with most of the
hMod community having trust in the developers of Bukkit after having
seen their work on hMod and hMod plugins. A small segment of the
community disagreed that hMod wasn't worth continuing and continued to
update it themselves as a fork. This was the first split in the server
community, albeit a minor one. Most servers and developers followed the
Bukkit project into 2011.

# 2011 - The Golden Era of Bukkit

## The launch of Bukkit

As 2011 kicked off, the Bukkit project was officially released with an
announcement thread on the [Minecraft Forums on the 1st of
January](https://www.minecraftforum.net/forums/mapping-and-modding-java-edition/minecraft-tools/1260642-introducing-bukkit-a-new-minecraft-server-mod).
Bukkit was designed from the ground up to address many of the issues
that plagued hMod users and plugin developers. It was intended to be
significantly easier to develop plugins for, as well as to run much
faster. There were a few features that were not brought over from hMod
however, such as inbuilt admin commands and a permissions system.
Overall the community reaction to the announcement was highly positive,
with most respondents mostly wanting to know when their favourite
plugins such as CraftBook or Runecraft were moving over.

To make up for the lack of hMod's inbuilt features, the Bukkit project
created a set of plugins to add basic admin commands, a home system, and
a chat system. The plugins were named
[ScrapBukkit](https://github.com/Bukkit/ScrapBukkit),
[HomeBukkit](https://github.com/Bukkit/HomeBukkit), and
[ChatBukkit](https://github.com/Bukkit/ChatBukkit), respectively. Rather
than being "official", these were released just like any other plugin.
These weren't intended for long term use, but more to act as both a
stopgap solution for the hMod users who expected these features to come
with Bukkit, and as a suite of example plugins for developers to look at
while developing their own plugins.

One of the planned key features of Bukkit that was announced was the
Fill plugin repository. This repository was designed to go alongside
commands within the Bukkit software that would allow server admins to
install, update, and uninstall plugins all from within their server. Not
much progress was made on this, however, and the project never saw the
light of day. The Bukkit forums were used instead for plugin releases.

The Bukkit team also expanded at this point, to include others such as
lukegb, GoMySQL, and more. Their primary role on the Bukkit project was
managing infrastructure.

While highly active early on, sk89q did not stay with the Bukkit team
for long. Many major decisions that have stuck with the Bukkit project
and community since were led by him, however, such as the usage of YAML
for configuration and the service loader system. He also made many
changes to make plugins like CraftBook and WorldGuard more capable, such
as the inclusion of `BlockPhysicsEvent`/`BlockRedstoneEvent`, the
vehicle system, and partial cause tracking to many events. As of
writing, sk89q is still the 4th biggest committer to the original Bukkit
project despite leaving the team before the end of 2011.

In the early days, community members were involved in many meaningful
discussions around how the project should run. One such debate was
around which software licenses Bukkit and CraftBukkit would use. Bukkit
was licensed under GPL and CraftBukkit under LGPL. While the license was
noted to not be valid due to the [intent of usage with proprietary
code](https://bukkit.org/threads/what-license-is-the-bukkit-project-under.154/page-2#post-2824),
this did have the implication that all plugins built using the Bukkit
API were required to be GPL. EvilSeph did state that the Bukkit team
would never enforce the license. However, this does not prevent other
Bukkit contributors from requiring enforcement. To this day, the theory
that all Bukkit plugins must be licensed under the GPL has never been
tested in court.

## CanaryMod

While most of the community switched to Bukkit, there was still a core
group that remained faithful to the hMod platform. On the [3rd of March
2011](https://github.com/shadow386/CanaryMod/commit/38e01aee716ab6c513313eb8ad24905fa99217a5),
shadow386 rebranded their hMod continuation fork to CanaryMod. CanaryMod
improved on the API of hMod in many ways, rather than entirely starting
over like the Bukkit project. CanaryMod also borrowed parts of the
Bukkit API, leading it to partially resemble both hMod and Bukkit. The
team also kept up a small number of plugins, generally forks of all of
the original plugins but updated by different authors. The primary user
of CanaryMod was the MinecraftOnline server, due to having started
during the hMod era.

## Dawn of the Proxies

On the [9th of
January](https://github.com/Raphfrk/CraftProxy/commit/a36c2a552efd299044f2af28a7a4fa9a946d914a),
Raphfrk made the first of their three proxies. And thus, CraftProxy, the
first ever Minecraft server proxy was born. However, it functioned
somewhat differently from what came after it. Its purpose was not to
allow a player to switch between servers in-game like is typical of
modern proxies, but instead to host multiple Minecraft servers on the
same machine while still using the default port. For example, you could
host both a creative.server.com, and survival.server.com from the same
device, and it'd forward the user to the correct server based on what
URL they use to connect. These still functioned as independent servers
from the player's perspective.

Later, Raphfrk rewrote CraftProxy twice. First under the name
CraftProxyLite and later CraftProxyLiter. These rewrites both improved
performance and added new features, such as protocol compression. Both
of these proxies still behaved in a similar manner to CraftProxy
however, having a different purpose to modern proxies.

## Griefer YouTube

As with any multiplayer video game, Minecraft servers were vulnerable to
griefing, where someone enjoys intentionally annoying or disrupting
other players rather than playing the game. In Minecraft, this primarily
took the form of destroying terrain, builds, or targeting and killing
players. Perhaps the most infamous of the griefers were Team Avolition,
who uploaded their first Minecraft griefing video onto YouTube on the
9th of January 2011. They were most well-known for finding servers from
Reddit, and griefing or trolling with a custom-made cheat client. Team
Avolition quickly gained a cult following amongst a section of the
community and inspired a wave of griefing YouTube channels and cheat
client developers. They also sparked a feud with Reddit and became
infamous for repeatedly griefing the NerdNu series of servers.

## The Early Bukkit Plugins

Right after Bukkit's launch, plugin developers were hard at work on
creating new Bukkit plugins. Most of the large hMod plugins were quickly
ported, including all the ones listed in this post. There was also a
flood of new plugins, especially with many beginner developers feeling
empowered by Bukkit's simpler developer experience.

On the [3rd of January
2011](https://github.com/taylorkelly/BigBrother/commit/a34cb8d6718d3ba1c4299da38d92707a2ba1a0ee),
the BigBrother project was started by Taylor Kelly. BigBrother, like
LogBlock, was a plugin that logged block changes by players. BigBrother
was the first block logging plugin to be available for Bukkit, with a
port of the LogBlock plugin from hMod following shortly after.

Nijikokun, the developer of iConomy, started work on a plugin to fill
the void that the lack of general admin commands in Bukkit left in the
community. On the [5th of January
2011](https://github.com/nijikokun/General/commit/c9796e3abfa7fd5797f5cd0c9ccd07b3825766cd)
he unveiled his solution to the problem, with a plugin named General. On
the [19th of January
2011](https://bukkit.org/threads/gen-essentials-v2-1.1262/), Zenexer
started another similar project under the name of GeneReal, a spoof on
the name General. This then sparked a public argument between Nijikokun
and Zenexer on the GeneReal forum thread. Shortly after, the General
plugin was abandoned, and GeneReal was renamed to Essentials.

The MinecartMania plugin started development on the [13th of January
2011](https://github.com/Mattie/MinecartMania/commit/9702d9f9a72489db4a46788b2e11981c4d95b6af),
led by Afforess. MinecartMania aimed to expand upon what Minecarts could
do within Minecraft. While MinecartMania itself only added a few
features, it relied heavily upon extensions to the base plugin that
added anything from automated Minecart spawners to automatic farming
with Minecarts. It gained quick popularity, as the highly popular
minecart features of CraftBook would not be available on Bukkit for a
short while after MinecartMania was released.

Shadeness ported Towny from hMod to Bukkit as early as [February 4th
2011](https://www.bukkit.org/threads/sec-fun-info-towny-v0-59-resident-town-nation-hierarchy-grid-based-protection-531.3358/).
After taking a leave of absence, ElgarL took over the project on [July
18th
2011](https://github.com/TownyAdvanced/Towny/commit/6072ffe9a0a5f9110905ba8ef4a83fa52cb8cf76).
ElgarL later left the community alongside the release of Minecraft 1.8,
and Towny has been developed by LlmDl since.

On the [12th of February
2011](https://bukkit.org/threads/econ-chestshop-3-7-18-iconomychestshop-chest-sign-shop-for-economy-plugins-1-8.4150/),
Acrobat released the iConomyChestShop plugin. While initially only
supporting iConomy, this plugin allowed players to sell and buy items
using in-game currency by clicking a sign on a chest. This concept,
while ubiquitous on servers now, was novel at the time and significantly
improved the gameplay experience of Economy Minecraft servers. The
plugin was later renamed to ChestShop once it gained support for other
economy plugins after the release of Vault.

On the [14th of February
2011](https://bukkit.org/threads/sec-lockette-simple-chest-and-door-lock-no-databases-moved-to-bukkitdev.4336/),
Acru released the Lockette plugin. Lockette was similar to LWC in
functionality but had a crucial difference in that it used signs for
protecting blocks, rather than commands and a database. This difference
was a big deal to many server owners, due to the simplicity of not
having to setup their server with a database.

The DynamicMarket project was started on the [21st of February
2011](https://github.com/HaloInverse/DynamicMarket/commit/0bfedee6b910cb3b78eca64d67af545adbf1b8b3)
by HaloInverse and was the first shop plugin that adjusted the price of
items based on supply and demand. This plugin has a very different
concept to most of the shop plugins at the time and helped start a few
of the first economy servers. While this was an interesting concept and
very novel, it didn't catch on too well overall.

The first permissions plugin for Bukkit started development on the [22nd
of February
2011](https://github.com/nijikokun/Permissions/commit/f4be0bceb7688df661a92d35c8c17a5e7489707f);
created by Nijikokun and aptly called Permissions. This plugin aimed to
bring a re-imagined version of hMod's permission system to Bukkit.
Permissions was a dominant player in the permission plugin space for a
large portion of the early days of Bukkit, and helped shape the way
permissions in Minecraft servers work today.

Also on the [22nd of
February](https://github.com/Multiverse/Multiverse-Core/commit/68107d9df8eee267bb3ff245a439f9ac5ce8ec6c),
Simon Rigby started work on the MultiVerse project. MultiVerse allowed
servers to have multiple worlds that players could travel between using
commands. This project sparked a trend in the server community where
servers would have secondary worlds, usually for mining or events.
MultiVerse eventually had add-on plugins released, such as
MultiVerse-Portals that allowed construction of physical portals that
the player could walk through, similar to nether portals.

Unhappy with the current state of command plugins, sk89q started work on
his own. On the [1st of March
2011](https://github.com/EngineHub/CommandBook/commit/8dbdefe99f05c352f69e1ecca6bf00c46d8c8c8e),
the [CommandBook](https://enginehub.org/commandbook) project started
development. CommandBook had a focus on usability and strayed away from
many of the less command-based systems that Essentials had. CommandBook
was the first plugin ever to allow selectors such as `#near` to refer to
nearby players or natural language such as `3am` to refer to a Minecraft
time. Like his other plugins, he also made CommandBook depend on
WorldEdit, which had started to take on the form of a small API library.

On the [18th of April
2011](https://github.com/PEXPlugins/PermissionsEx/commit/23319e20dc0d44e07c48f24e00586dc41edc4b5c),
t3hk0d3 started work on another permissions plugin known as
[PermissionsEx](https://dev.bukkit.org/projects/permissionsex). The
introduction of a second permissions plugin caused turbulence in the
Bukkit community, as most plugins only supported Nijikokun's Permissions
plugin. sk89q created a system known as
[WEPIF](http://web.archive.org/web/20120904175159/http://wiki.sk89q.com/wiki/WEPIF)
(WorldEdit Permissions Interoperability Framework) to handle the
existence of multiple permissions plugins, but it never gained
widespread usage outside of his plugins. The original PermissionsEx
would continue to be maintained until 2017, and later zml2008 would
begin a rewrite of PermissionsEx.

On the [1st of
June](https://github.com/MCBans/MCBans/commit/1f5c89e843cacb43142705aacc42b17835e96248),
work on the MCBans service was started by firestar. MCBans was a
game-changer for server admins, allowing a global ban list to be created
for repeatedly problematic players. MCBans allowed servers to prevent
any player who had received a certain number of bans from joining their
server, and let admins look up whether individual players had been
banned in the past. MCBans was not the only service to offer this; the
MCAdmin server wrapper had this feature as well. However, MCAdmin was
surrounded by controversy. Griefing teams, such as [Team
Avolition](https://www.youtube.com/watch?v=QtiL_pA2kDY), were exploiting
the MCAdmin bans system to ban admins before going on to grief servers,
and Doridian made himself unbannable after a similar issue. MCAdmin was
not well trusted, but MCBans alleviated most of these concerns by being
open source and having a system that was less prone to abuse.

Due to the rapidly growing number of economy, permissions, and chat
plugins, cerealcable started work on a plugin that made it significantly
easier for other plugins to support multiple of them at once. From this,
the Vault project formed on the [28th of
June](https://github.com/MilkBowl/Vault/commit/875e5f980c3c0e6b567afcfc2692cfc1dfdf1146).
Prior to Vault, plugins had to separately provide support for every
individual permission, economy, or chat plugin, leading to ecosystem
clusters and conflicts that wouldn't have existed otherwise. Vault is
still widely used to this day and supports almost every major plugin.

On the 14th of August 2011, the Buycraft service launched. Buycraft made
it easy for server admins to charge real money for in-game content.
Frequent use cases were access to plugins, chat perks, or in-game
currency. The introduction of monetisation on Minecraft servers
massively shifted the server landscape, making it now possible for
server admins to profit off the servers they ran, or at least try to
offset hosting costs. Since then, the Buycraft service has been renamed
to Tebex. The Bukkit plugin itself was rewritten by Tux and is now known
as BuycraftX, paying homage to the historical roots of the service as
well as marking a new era of the plugin.

## Server Lists

Due to the growing surge in the number of Minecraft servers coming into
2011, several sites started to pop up to make it easier for players to
find servers and for servers to advertise to players. Prior to this,
servers were generally listed on Reddit or the Minecraft Forums. In
early January of 2011, a server list known as
[MineStatus.net](https://minestatus.net/) launched, making it the oldest
Minecraft server list that is still running today. Other server lists
such as [minecraft-server-list.com](https://minecraft-server-list.com/)
and [MinecraftServers.org](https://minecraftservers.org/) followed
shortly after.

Initially, the list order was obtained by players voting for their
favourite server once per day, but over time other methods to increase
server visibility were added. The ability to pay for sponsored ad slots
at the top of the server list were initially released on minestatus.net
on the [10th of July
2011](https://twitter.com/minestatus/status/79037064150134784). For the
longest time, server lists were the most common place to find a
Minecraft server.

Minestatus.net would go on to create two plugins that would set an
example for how server lists would operate. One of these, Votifier, was
launched on the [19th of June
2011](https://github.com/vexsoftware/votifier/commit/8f766281d0287cf7ff847d1faa5c927b8567e2e9).
This sparked a massive shift in the way servers would entice new
players. Votifier allowed servers to incentivise votes from players on
voting sites, which became common practice throughout the entire
community for years to come. Sites that implemented Votifier support
would notify the server when they received a vote, allowing them to
automatically reward the player. While the rewards players received from
voting have changed significantly over time, rewarding votes is still
seen across most servers today. The plugin was maintained by the
original authors until 2015. Today most servers use NuVotifier, a fork
of the original Votifier started by Ichbinjoe and Tux that adds vote
forwarding, support for Sponge, BungeeCord, and Velocity, and an
improved protocol.

Minestatus.net also created another piece of foundational software for
the server space,
[MineQuery](http://web.archive.org/web/20110119001648/http://minestatus.net/minequery).
MineQuery allowed external services such as websites to get information
about a Minecraft server, such as whether it was online as well as
current player counts and names. MineQuery later became redundant with
the introduction of the query protocol to Minecraft 1.0, and the server
list ping packet to Minecraft 1.3, integrating this functionality
directly into Minecraft itself.

## Economy Servers

Due to the capabilities provided by the wide selection of economy
plugins and those that allowed charging in-game currency, servers were
popping up that took the current "Survival+" game style but with an
added economy and trading system. Generally, these servers would be
survival servers with plugins such as CraftBook or MinecartMania to add
more complex and varied gameplay, with an added dash of capitalism. Many
of these servers also had a town system, such as with the plugin Towny.
Players would earn enough money to build a town by working in other
towns, or selling things they gathered and then employ newer players to
do various tasks.

The largest and longest-running Economy server was EcoCityCraft, which
was launched on the 4th of April 2011 and is still running to this day.
This server heavily influenced the economy game style.

### Prison Servers

The Economy server style also had numerous off-shoots, with the Prison
style being one of the largest. Prison servers were styled around a
prison with players roleplaying as a prisoner, with artificial
constructed mines and other various ways to earn money to level up
through different tiers of cell block. Further evolutions of the Prison
game mode involved players eventually being able to buy their freedom
and gain access to a normal Minecraft world, the ability for players to
apply to be guards and confiscate contraband items, and the ability for
players to buy a space they could build in from a prison cell to a large
plot of land.

## BukkitContrib

Afforess started the BukkitContrib project on the [1st of May
2011](https://github.com/Nightgunner5/BukkitContrib/commit/eb22175c782c4dcae59908b59f12fe432d83d594).
BukkitContrib was an extension to Bukkit that was installed as a plugin,
which allowed plugin developers to create things beyond the limits of
Bukkit. BukkitContrib also published a client mod, that when used would
let plugins do things that generally would require mods. Plugins written
with BukkitContrib could add new sounds, GUIs, and even give the
impression of extra items and blocks using textures. None of these
required installing any client mods beyond BukkitContrib, which was sent
data from plugins by the servers that the player joined. A plugin that
shows off what BukkitContrib was capable of is
[Sprout](https://dev.bukkit.org/projects/sprout), which allows adding
infinitely more crops to Minecraft.

On the [1st of August
2011](https://bukkit.org/threads/dev-spoutplugin-unleash-the-flow-of-endless-possibilities-1-0-1-3-2.29259/),
BukkitContrib relaunched as Spoutcraft due to Bukkit cracking down on
the usage of the Bukkit name in other projects. Soon after, sk89q and
lahwran planned to make a competitor to Spoutcraft. Designs were made
for various systems, but the project never went anywhere. A few of the
designed systems ended up making their way into the WorldEdit API.

## Return of the Lightstone

SpaceManiac started work on continuing Lightstone on the [4th of June
2011](https://github.com/GlowstoneMC/Glowstone/commit/6fe0dfbea37e0f9478de89c3b91b554bf4358b17),
with plans to implement the Bukkit API and therefore allow Bukkit
plugins. The project was named Glowstone, due to it being the new name
for the Lightstone block which the original project was named after.
Glowstone continued the goal of achieving a server without any Mojang
code, and the project is still alive today.

### Spout

A few months after the Glowstone project started up again, the
Spoutcraft team abandoned Spoutcraft in favour of writing a custom
server based on Glowstone. The team then rebranded again as Spout and
forked Glowstone. Spout also had its own rewritten game client as well,
and a plugin for the Spout server called Vanilla that allowed Minecraft
clients to connect. Due to the extremely ambitious goals of the project,
it never gained feature parity with Spoutcraft nor Minecraft and was
eventually abandoned towards the end of 2013.

Later in the year, on the [4th of
October](https://github.com/cuberite/cuberite/commit/e0bae05ed4cea2095718b93e211eaae3d41e8dc4),
the Cuberite project was started. Like Glowstone, Cuberite is also still
around today. The goal of Cuberite was to offer a very high-performance
game server, using a custom-written server in C++. Cuberite servers are
mostly aimed at minigames that don't require full conformance with
Minecraft gameplay standards, and has its own API for making plugins.

## MinecraftForge

On [July 12th
2011](https://github.com/MinecraftForge/MinecraftForge/commit/999ef3817a7ddfd21043a69f8af5dcf2c028b945),
SpaceToad started the MinecraftForge project. Minecraft Forge was a
spiritual successor to Risugami's Modloader and SDK's ModloaderMP,
allowing mods to easily be written and loaded on both the server and
client. MinecraftForge became the go-to platform for running a server
that used mods that added content such as blocks, items, or mobs. Due to
how much easier it was to write mods that supported both the server and
client on MinecraftForge, it became significantly more common for mods
to support multiplayer. This led to a surge in Minecraft modpacks built
specifically to play with friends. While MinecraftForge did not support
Bukkit plugins, the modded Minecraft community had very different needs,
making this less of a problem. MinecraftForge is still around today, run
by LexManos and the rest of the MinecraftForge team.

## Bukkit Matures

As the Bukkit project grew throughout 2011, a few issues had started to
creep up. Permissions management in the Bukkit ecosystem was non-ideal,
and the forums were outgrowing their usefulness as a place to download
plugins.

### SuperPerms

Dinnerbone proposed a solution, a system in Bukkit for permissions that
was colloquially known as SuperPerms (or sometimes DinnerPerms,
referencing its creator). Not wanting to break the community-made
permission plugins, the Bukkit permission system behaved similarly to a
very cut down version of Vault, providing an official way for plugins to
ask the installed permission plugin whether a player had a permission or
not. This system, while widely used for permission checking now, was
imperfect compared to Vault. Dinnerbone did not believe that plugins
needed access to which groups a player was in, and instead suggested to
use a `group.GroupName` permission check to assess group membership. Due
to this decision being disagreed with by many permission plugin
designers, plugins that relied on group names had to continue using
Vault. Both Vault and WEPIF were updated to support the new system and
kept around for the following years.

As part of the SuperPerms launch, SpaceManiac also launched a new
permissions plugin that implemented SuperPerms as an example. The new
plugin, PermissionsBukkit, was started on the [2nd of July
2011](https://github.com/SpaceManiac/PermissionsBukkit/commit/27e82705b7fab75e76b7b7fb9b42e55b86992f40)
and launched on the [17th of
July](https://github.com/Bukkit/Bukkit/commit/914da8e887deaadb57be339aa2dbb78eca2742a4)
alongside SuperPerms inclusion in Bukkit.

### BukkitDev

The Bukkit team still had to fix the growing problem with the plugin
releases section of the forums, especially as their Fill plugin
repository was nowhere to be seen. After discussing a partnership with
Curse, the Bukkit team announced the launch of BukkitDev on the [25th of
August 2011](https://dev.bukkit.org/news/644-welcome-to-bukkitdev).
Initial reactions were mixed. Many were positive about the capabilities
of the new system, while others were reluctant to change and cautious
about Curse. A few fears were raised regarding how Curse has treated
other Minecraft community sites, as well as how the bukkit.org domain
name registration was transferred to Curse. Over time, all active
plugins migrated over from the Bukkit forums to BukkitDev, and the
plugin releases section of the forums was locked.

# 2012 - The introduction of Forks and Other Cutlery

## Admincraft

On the 12th of January 2012,
[/u/theheyway](https://www.reddit.com/user/theheyway) created a new
Minecraft community subreddit,
[/r/admincraft](https://www.reddit.com/r/admincraft). The subreddit
existed to discuss all things relating to Minecraft server
administration, from how to run a server, to the discussion of plugin
development. The admincraft community has since grown also to include a
Discord and is one of the most widely known server administrator
communities.

## Shotbow Network

The Shotbow Minecraft server network was formed during February 2012 and
is recognised as the oldest Minecraft server network. Not only did
Shotbow first introduce the concept of a centralised hub server that let
players join minigames, but they also created the popular MineZ
minigame. MineZ, based on the DayZ mod for Arma 2, quickly became one of
the most popular Minecraft game modes of all time, even getting
recognition outside of the Minecraft multiplayer community.

## Bukkit x Mojang

In [late 2011](https://bukkit.org/threads/bukkit-visits-mojang.51035/),
the Bukkit team was invited to Mojang for discussions around the future
of Minecraft modding. At the time, very little was publicly known about
what they discussed. On the [28th of February
2012](https://bukkit.org/threads/bukkit-the-next-chapter.62489/),
EvilSeph made a post to the Bukkit forums in which he explained that the
Bukkit team had been hired by Mojang to work on an official modding API
for Minecraft. Dinnerbone provided a [thorough
FAQ](https://bukkit.org/threads/bukkit-the-next-chapter.62489/page-9#post-990129)
where he reassured the community that Bukkit was not going anywhere and
that Bukkit plugins would be mostly compatible with the future Minecraft
modding API. While the modding API never materialised, the addition of
the Bukkit team to Mojang significantly influenced the direction of the
game. Contributions made by the team, especially some of the internal
technical changes by Grum, are part of the reason that the game is so
different now than it was in 2012.

Following the original Bukkit team's hire by Mojang, Bukkit brought on a
few new developers to keep the project alive. On the [31st of March
2012](https://bukkit.org/threads/the-status-of-bukkit.68104/),
fieldmaster and Wolverness were brought onto the team. A few weeks later
on the [24th of
April](https://bukkit.org/threads/bukkit-project-update-slow-development-addition-to-the-team.72397/)
Amaranth joined as well, with mbaxter and evilmidget38 to follow after
that.

## Increments and Decrements of CraftBukkit

In May of 2012, a new trend emerged where developers were publishing
modified versions of the CraftBukkit software, and the Bukkit team was
having trouble keeping them out of the forums.

### CraftBukkit++

Afforess, working on behalf of HeroCraft, started work on a modified
version of CraftBukkit that aimed to improve server performance
significantly. This fork, known as CraftBukkit++ and released on the
Spout forums, introduced some of the significant performance
improvements that are seen in both [Spigot and Paper
today](https://madelinemiller.dev/blog/paper-vs-spigot/). These features
were initially being trialled for inclusion within CraftBukkit itself,
in a private version of the Bukkit-Bleeding project. They were, however,
ultimately scrapped due to making slight changes to vanilla Minecraft
behaviour. After this point, the Bukkit team opted to remain faithful to
vanilla behaviour rather than implement performance improvements that
would require deviating from them.

### CraftBukkit--

Very shortly after CraftBukkit++ was released, the project was
abandoned. EcoCityCraft wanted to keep the project alive and had md_5
and a few of their other developers work on a continuation of
CraftBukkit++. A new project was then released under the name
CraftBukkit--, chosen as a parody of CraftBukkit++. Unlike
CraftBukkit++, this project had longevity.

An attempt was also made to turn [CraftBukkit-- into a Bukkit
plugin](https://github.com/BukkitDevTeam/Spigot-Plugin). While some
progress had been made on the plugin version, the project was ultimately
scrapped due to difficulties with making certain changes. md_5 has also
planned to create a custom server similar to Glowstone that implemented
the official Minecraft modding API, known as
[Fondue](https://github.com/BukkitDevTeam/Fondue). As the modding API
never materialised, neither did md_5's project.

## Plots

On the [2nd of June
2012](https://bukkit.org/threads/wgen-sec-plotme-v0-9-plot-generation-and-protection-1-3-r1-0.78840/),
ZachBora released PlotMe. PlotMe was the first significant plot world
generator plugin, inspiring what is now the basis of almost all creative
servers. Initially, plot worlds found their use as protected building
space in other game modes, such as prison.

### OP Prison

Alongside the ability to create plot worlds, Prison servers underwent
another evolution. Prison servers were generally viewed as very "grindy"
in terms of gameplay, usually requiring hours of mining to level up to a
slightly nicer cell block, only to then go through the same process
again. While this appealed to many people, alongside the inherent
roleplay aspect, many newer players found this boring. This led to the
creation of the "OP Prison" game mode, where high enchantments were
often applied to tools and currencies were highly inflated. It was also
common to earn or purchase multipliers and various buffs to speed up the
process further. These servers usually were more aimed at aspects such
as PvP, plot building, or economy, with the Prison theme and cell blocks
more acting as central hubs for players to mine and socialise.

## Proxy Time

md_5 and Codename_B set out to work on a new proxy software for the
Minecraft server. There was a growing demand for chaining multiple
servers together, which existing proxies like CraftProxy were not
directly capable of doing. In August 2012, the projects RubberBand and
RubberBukkit were released. RubberBand, [named by
Codename_B](https://paste.gg/p/zml/88b3f210f2e448a3a59ade0973996b2b) as
it flings you between servers, was a proxy with rudimentary support for
chaining multiple servers together. It had a fatal flaw; it required
using a modified version of CraftBukkit known as RubberBukkit to work.
This flaw led to the project failing to gain much adoption.

md_5 started work on building software around RubberBand and created a
suite of software known as the Elastic Portal Suite. At the same time,
he began work on a follow-up to the RubberBand proxy to address some of
the main issues in the software. On the [4th of October
2012](https://github.com/SpigotMC/BungeeCord/commit/b876fb2e1bd395c37f47b020c2f0e778812c0c61),
md_5 started the BungeeCord project. BungeeCord was a successor to
RubberBand and a part of the Elastic Portal Suite. BungeeCord was
faster, had a plugin API, and didn't require a modified version of
CraftBukkit to work. It was named BungeeCord in reference to the prior
RubberBand software, due to bungee cords being big and powerful rubber
bands. BungeeCord was the first significant public server proxy that
allowed combining individual servers into a single Minecraft network and
is still used to this day.

# 2013 - Rise of the Network

## Spigot

On the [15th of January
2013](https://github.com/PaperMC/Paper/commit/622229778428e822be7c97d9c5f08ddb6281d97f),
md_5 rebranded the CraftBukkit-- project to Spigot. The Spigot project,
while still partnered with EcoCityCraft, was no longer a project owned
and developed by EcoCityCraft but its own separate thing. As Spigot
started cementing themselves as a real Bukkit alternative, the community
began to split between the Bukkit and Spigot forums. Spigot also added a
resources subsection to their forums, to allow Spigot-only plugins to be
released due to new BukkitDev rules against plugins that couldn't run on
CraftBukkit. Since launch, Spigot has remained a major player in the
server software space.

## Super Networks

Mineplex was a server network that launched on the [24th of January
2013](https://en.wikipedia.org/wiki/Mineplex). It was the first
"super-network," hitting a record of over 34 thousand simultaneous
players with an average of over 10 thousand concurrent players. Gaining
initial popularity from videos made by CaptainSparklez, the server went
on to set a Guinness World Record for their player count. Mineplex's
popularity started to dwindle later and has now become a predominantly
Minecraft Bedrock Edition server network due to a partnership with
Mojang.

On the 13th of April 2013, the Hypixel server network launched. Hypixel
grew beyond the size of Mineplex, and is the definite champion of
Minecraft server networks, averaging over 100 thousand concurrent
players. Unlike Mineplex, however, Hypixel is only available on
Minecraft Java Edition. Hypixel has 4 Guinness World Records, including
the one for player count that was previously held by Mineplex.

## Proxy Developments

Keeping permissions synchronised across multiple servers in a network
started to become a more significant problem due to the growing size and
scope of networks, leading to the development of a plugin known as
BungeePerms on the [3rd of April
2013](https://github.com/weaondara/BungeePerms/commit/c37ffe2ca7044e58f76e07bc754ca75df9aa8aaa)
by weaondara. BungeePerms allowed multiple servers on a network to share
permission setups, a feature which has since been adopted into other
plugins such as LuckPerms.

On the 20th of April 2013, Coelho started the LilyPad project, providing
an alternate proxy to BungeeCord. LilyPad aimed to provide a more
straightforward plugin API while using significantly fewer resources
than BungeeCord, and was eventually also ported to the Go language to
further improve performance.

Led by a server network known as The Chunk, the RedisBungee project
started on the [29th of September
2013](https://github.com/minecrafter/RedisBungee/commit/d0f5a24f38ff5251dacb981a96de54ab68d0af38).
RedisBungee was the first public project that allowed combining multiple
Minecraft proxies, due to scaling issues that larger networks were
starting to face. Like Minecraft servers, proxies also have limitations
in the number of players they support. Due to this, scaling the number
of proxies in use became a common practice on larger networks.

# 2014 - Bukkit is dead, long live Sponge...Spigot?

## Paid Plugins and Monetisation

On the [16th of April
2014](https://www.spigotmc.org/threads/did-you-know-google-authenticator-premium-resources.16306/),
Spigot launched a section of their resources site that allowed
developers to charge for plugins. This decision was highly divisive
within the Minecraft community, with many being firmly either for or
against it. Shortly after, [MCMarket.org](https://www.mc-market.org/)
launched on the 30th of July. Unlike Spigot Resources, MCMarket was home
to all kinds of transactions. It became common to see people trading
worlds, plugins, or even entire servers. MCMarket also allowed players
to trade Minecraft accounts, contrary to the terms of use for the game,
and therefore developed a negative reputation in some areas of the
community.

Prior to these marketplaces, the most common forms of making money in
the server scene for anyone other than server owners were to create
custom plugins or builds for servers in exchange for money. This system
opened the ability to publicly sell plugins, for better or for worse.
This development also led to the creation of a few Minecraft piracy
websites, that have been riddled with controversy and malware outbreaks.
There have also been many controversial implementations of DRM by plugin
developers.

## PaperSpigot

The PaperSpigot project was started by gsand and Z750 on the [23rd of
June
2014](https://github.com/PaperMC/Paper/commit/b9179a0a04ab1fa4e95e88aa59cdebc9c73dc433).
While initially created for fun, the project became more serious after
Spigot became reluctant to accept many community contributions. To
separate themselves from Spigot, they later rebranded to Paper,
stripping the Spigot part of their name. Paper worked on including
significant performance improvements into the Minecraft server, going
far beyond that of Spigot. They also strived to be much more community
oriented, and more open to contributions.

## EngineHub

On the 5th of July 2014, sk89q created an organisation known as
[EngineHub](https://enginehub.org/). All of his plugins and libraries
were transferred to EngineHub to reflect what had been a slow transition
to a more community-led development style. This included WorldEdit,
WorldGuard, CraftBook, CommandBook, and more. As sk89q had not been the
only one working on these plugins for most of their existence, this
allowed sk89q to step back from the projects. EngineHub's software is
now mainly developed by [Me4502](https://madelinemiller.dev/contact/),
octylFractal, and wizjany.

## The Death of Bukkit

On the 21st of August 2014, EvilSeph announced that the Bukkit project
was shutting down. He cited reasons such as the legal grey area that the
project was in, and that the API was old and incompatible with the
future of Minecraft. [Shortly
after](http://web.archive.org/web/20140909045841/https://storify.com/lukegb/the-tale-of-bukkit-for-minecraft-1-8),
Mojang announced that they had owned the Bukkit project since the
original Bukkit team was hired in 2012. This was a shock to the
community, leaving many long-time Bukkit contributors feeling betrayed
as this was never made public. It was a widespread belief that they were
contributing to a community project, not a project owned by a major
company. Dinnerbone and Grum announced that they would be updating the
Bukkit project while reiterating that Bukkit would not be the official
modding API.

On the [5th of September
2014](https://github.com/github/dmca/blob/master/2014/2014-09-05-CraftBukkit.md),
GitHub received a DMCA (Digital Millenium Copyright Act) claim over his
contributions to the CraftBukkit project and all forks that contained
changes beyond the 25th of January 2012. Due to this, CraftBukkit,
Spigot, and all related projects were taken down from GitHub.
Consequently Dinnerbone and Grum were unable to update Bukkit, as there
were legal implications of doing so. At this point, the Bukkit project
was officially dead.

## From the Ashes, #nextstep rises

Amid the panic, many key members of the Minecraft community banded
together to discuss what should happen now that Bukkit is gone in an IRC
channel called `#nextstep`. A plan and time were set for the meeting,
and a document distributed to the community. The discussions took place
between the 5th and 7th of September and eventually led to a new project
forming under the name Sponge. The project leads for the Sponge project
were Blood, Zidane, and sk89q.

Initial goals for the Sponge API were to build a modern API that was
more in line with the way Minecraft worked at the time compared to
Bukkit, which was very much showing its age. Sponge was to be
implemented on top of Forge and would allow plugins to work natively
alongside mods. On the [7th of September
2014](https://github.com/SpongePowered/SpongeAPI/commit/5a96c646c017fb853ee0260ca2c213445e7acdd6),
the first commit to the Sponge API was made. Sponge's API, while similar
to Bukkit in some ways and very different in others, very quickly became
more powerful than Bukkit. Borrowing heavily from Spout, WorldEdit, and
WorldGuard, the Sponge API was a real community project. While the API
came quickly, the actual server software was not ready for some time.

Alongside development on the Sponge API, another group started work on
the MythicAPI on the [8th of September
2014](https://github.com/jamierocks/Granite/commit/47d23d16545e7975f14dc5fc32ca9e7015dad0e1).
The API did not last long and eventually the project became an
implementation of the Sponge API on a vanilla server, like what
CraftBukkit was for Bukkit. This project then became known as Granite.

On the [28th of November
2014](https://www.spigotmc.org/threads/bukkit-craftbukkit-spigot-1-8.36598/),
Spigot released a 1.8 version of CraftBukkit and Spigot. This release
was the first time that the Spigot team had updated CraftBukkit
themselves and marked a shift that led to Spigot gaining market
dominance as the de facto implementation of Bukkit.

# 2015 to 2017 - The Era of Stagnation

## Essentials reborn

During the DMCA debacle, the Essentials project had been abandoned for
Bukkit. There had been [plans for Me4502 to continue the Essentials
project for
Sponge](https://github.com/essentials/Essentials/commit/11b39b4ef68666ad72b7b57e02eda7049f323adb);
however, due to other projects taking priority and the release of other
command plugins for Sponge, this never happened. On the [15th of April
2015](https://github.com/EssentialsX/Essentials/commit/dde0b20775c3b9a82f62d381e0d827f49313f46d)
however, drtshock started the EssentialsX project as a continuation of
Essentials for Bukkit. EssentialsX quickly filled the void Essentials
left and became almost as widely used.

## SpongeVanilla

In early 2015 the Granite project continued to grow, and gained many
fans from within the Sponge staff. After many discussions between the
Sponge team and the Granite team, it was decided to bring Granite
officially into the Sponge ecosystem and rebrand it SpongeVanilla. On
the [21st of April
2015](https://github.com/SpongePowered/SpongeVanilla/commit/877044fbee4697ef189eaa3f17119f352eaeffdc),
Granite's codebase had officially become SpongeVanilla. To make
SpongeVanilla and SpongeForge more similar, they were set up to share a
majority codebase under the name SpongeCommon.

## DragonProxy

DragonProxy was an early attempt by DefinitelyEvil to allow players of
Minecraft Bedrock Edition to connect to Minecraft Java Edition
multiplayer servers. The project was officially started on the [11th of
December
2015](https://github.com/WeaveMN/DragonProxy/commit/b0510e930497c82d1ada422b84e41144b5194943).
While the project worked as a proof of concept, numerous issues
prevented it from being used on any serious server. Due to this, the
project was abandoned relatively quickly.

## Waterfall

Due to some disagreements and issues surrounding the BungeeCord project,
a fork under the name Waterfall was made by minecrafter on the [25th of
January
2016](https://github.com/WaterfallMC/Waterfall-Old/commit/a27f55af963bf9502dd5c69ca89c9ada6a65e0b6).
Waterfall aimed to improve stability, performance, compatibility with
non-Spigot servers, and be more open to community contributions.

## EULA Enforcement

Around the [24th of February
2016](https://www.reddit.com/r/Minecraft/comments/47bt3r/mojang_are_starting_to_crack_down_on_servers/),
Mojang started to enforce the game's End User License Agreement on
servers that allowed users to purchase anything that impacted gameplay.
Any server that did not comply with the EULA risked being blacklisted by
Mojang, preventing the Minecraft client from connecting. This was major
in the server community at the time, as almost all servers were breaking
the EULA. Most server owners slowly changed their stores to comply with
the EULA, while a few others used workarounds to prevent themselves from
being blacklisted. Overall, this majorly changed how profitable running
a Minecraft server could be.

## The Combat Update and Protocol Compatibility

Minecraft 1.9 was released on the [29th of February
2016](https://minecraft.wiki/w/wiki/Java_Edition_1.9). This release,
also known as "The Combat Update", was the first update to create a
significant divide in the community. While some versions prior had
remained popular within niche communities for various reasons, this was
the first time an update had significant sustained backlash. A vocal
minority of players rejected the changes to combat and preferred to stay
on Minecraft 1.8, never updating beyond that version.

[At the same
time](https://github.com/ViaVersion/ViaVersion/commit/67b31c50608937df1d21bba5239132dad50a2c82),
FormallyMyles began development on a plugin known as ViaVersion.
ViaVersion allowed newer versions of the Minecraft client to connect to
an older version of the server, mainly to allow servers more time to
update without risking significant loss of players. As server software
took time to release updates, and plugins took more time on top of that,
ViaVersion helped solve an issue that had plagued server owners for
years.

Due to the dislike of Minecraft 1.9, some servers decided that they
would continue using ViaVersion for the considerable future, rather than
ever updating. To this day, there are still some PvP-oriented servers
that have not updated past Minecraft 1.8.

## LuckPerms

On the [21st of May
2016](https://github.com/LuckPerms/LuckPerms/commit/dc1e06ebcef4886568af1378ffeff406a5408428),
lucko started the LuckPerms project. LuckPerms was a new permissions
plugin that developed on many of the learnings in the permissions space
over the years and supported multiple platforms. It could be installed
on Bukkit, Sponge, and even BungeeCord. LuckPerms also had a web
interface to set up permissions from the browser. To this day, LuckPerms
is used by a vast majority of servers due to its ease of use and
versatility.

# 2018 to 2020 - The Era of Change

## Minecraft 1.13, The Flattening

Minecraft 1.13 released on the [18th of July
2018](https://minecraft.wiki/w/Java_Edition_1.13). Like Minecraft 1.9,
this update was highly divisive. Core parts of the game were rewritten
and all block and item IDs changed, creating [significant obstacles when
updating
plugins](https://madelinemiller.dev/blog/updating-3-of-the-largest-minecraft-plugins-in-existence-to-113/)
and servers. On top of this, server performance had decreased
substantially. Unlike Minecraft 1.9, this divide in the community was
caused by server admins rather than players. To this day, some servers
are still on Minecraft 1.12.

## Velocity and Waterfall

Frustrated by how limited Waterfall was due to the need to retain
BungeeCord compatibility, Tux, the original creator of Waterfall,
decided to create a new proxy project. On the [24th of
July](https://github.com/PaperMC/Velocity/commit/666d07e2a8c26b35a68c7c711f83d2193b27c749),
development for Velocity started. Velocity aimed to avoid the pitfalls
that BungeeCord had and provide an improved API along with better
performance. After Velocity launched, Tux transferred the Waterfall
project to Paper on the [29th of
September](https://discordapp.com/channels/289587909051416579/492517675680006144/495706929306271764),
allowing them to maintain it.

## Fabric

Towards the end of 2018, the Fabric project officially started. Built to
fill the gap left by Forge's slow update, Fabric aimed to be a much
simpler mod loader akin to Risugami's Modloader from the early days of
modding. Due to its simplicity, Fabric has been used for many smaller
Minecraft servers that don't need software as complex as Spigot or
Paper, or for servers that want to support Minecraft snapshot releases.
Fabric is also a very community-orientated process, using community
tools like Sponge's Mixin framework.

## Bedrock Compatibility, Take Two

Due to the issues with the earlier attempt at a Bedrock compatibility
layer proxy, DragonProxy, another developer made an attempt to rewrite
it. The goal of the rewrite was to support the Bedrock protocol in a
more straightforward manner, making it easier to maintain and achieve
feature parity. This project started on the [10th of October
2018](https://github.com/DragonetMC/DragonProxy/commit/dab11e1e123b171bfe5f5dcf8748a646262427c7),
led by Luukey.

Almost a year later, another proxy project known as GeyserMC started on
the 9th of July 2019, led by RednedEpic. The project eventually went on
to absorb DragonProxy and became the community standard for Bedrock
compatibility proxies. While it works very well, there are still some
minor issues due to the way Bedrock and Java Edition behave differently.

## Official Obfuscation Mappings

To make modding easier, Mojang announced on the 4th of September 2019
that they would be releasing official obfuscation mappings alongside
Minecraft releases from now on. This release gave modders a better
understanding about what Mojang intended various parts of the code to
do. However, due to unclear legal terms surrounding the releases, this
is currently only useful for personal use or reference purposes.
Releasing a project that uses these mappings is in a legal grey area. In
theory, once all legal issues are resolved, projects such as Yarn
(Fabric) and MCP (Forge) would no longer need to create their own
mappings.

## Revised Commercial Usage Guidelines

On the 17th of April 2020, Mojang revised the commercial usage
guidelines of the game to allow servers to monetise more than just
cosmetic changes. This change partially reverts the restrictions added
when enforcement of the EULA commenced. The new restrictions allow
selling packages that impact gameplay, as long as they do not give the
player a "competitive gameplay advantage".

# The future, and afterword

Predicting the future is hard, but it can always be fun and interesting
to give it a go. I feel that the Paper project, which is already gaining
a majority user base, will soon become the de facto Bukkit
implementation and therefore have control over API additions. Once this
happens, I feel that there will be a strong push to modernise the API,
which wouldn't happen otherwise within Spigot.

I feel that Minecraft Bedrock Edition and Java Edition will continue to
gain feature parity, with a potential protocol merge, allowing players
to play on the servers of either platform natively. Bedrock Edition is
growing much faster than Java Edition, so if this does not happen Java
Edition servers will struggle to keep a player base.

Overall, I feel that Minecraft will live for another decade with a new
generation of players. I just hope Minecraft Java Edition stays along
for the ride.

## Contributors

I'd like to massively thank every single person who helped me with this
document. This project was a community effort, and I couldn't have
finished it without you all. Here is a list of key contributors other
than myself who have worked on this project:

*kashike, KennyTV, zml, Inscrutable, mdcfe, Aurora, Tux, Garanthor,
Myokan, Glare, stifflered, mbaxter, DemonWav, LlmDl*

Special thanks to kashike for letting me co-opt a channel in the Kyori
discord while writing this.

The Minecraft server community has been a large part of my life for the
past decade, and this was part of my way of giving back. Throughout this
project, I learnt so much more about the various people I've known and
who have made the community what it is today, and I've gone on a very
long nostalgia trip. I hope this article helps share their contributions
with the Minecraft community of the future and give a new generation of
players more perspective and context on what came before.
