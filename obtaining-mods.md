## Obtaining mods
Now that you got your favorite modloader installed, it's time to look for mods!

Please do note that due to certain limitations in Minecraft's codebase at the time (block IDs limit, sprite IDs limit, etc..), playing with multiple large content mods can be extremely frustrating, especially when playing with poorly-coded mods (which were common at the time). Due to that, it's recommended to look for community-made patches that fix those problems for more compatibility.

### Mod sites

You can find most mods for legacy Minecraft here.

| Name | Definition |
| ---- | ---------- |
| [Modification Station Discord](https://discord.gg/8Qky5XY) | The largest community for everything legacy Minecraft related. You can find most mods, plugins, and compatibility/multiplayer patches for legacy Minecraft here. |
| [MCArchive](https://mcarchive.net/mods) | Archive lots of old mods, some of which cannot be found anywhere else. The go-to place for most old mods like The Aether, IC2, and so on. Check their Discord server (invite is in the site) too for even more mods. | 
| [Glass Repo](https://glass-repo.net/repo/mods) | A mod repostiory for legacy Minecraft. Newer mods for Babric and Station API can also be found here. Also contains lots of mod fixes and patches. |
| [Minecraft Beta 1.7.3 Mod Archive](https://archive.org/details/minecraftbeta1.7.3modarchive) | A comprehensive mod archive for Beta 1.7.3 with more than 1000 files.|
| [Minecraft 1.2.5 Mod Archive](https://archive.org/details/minecraft-1.2.5-mods-archive-20221007-t-205836-z-001) | A comprehensive mod archive for Release 1.2.5 with more than 600 files. |
| [Modrinth](https://modrinth.com/mods) | Mods mainly made for Babric/Legacy Fabric can be found here. |
| [Neyla's Archive](https://archive.naylahanegan.com/0:/) | Lot's of mods, for a wide range of versions. If there's something you couldn't find, chances are it's in here. |

### Installing mods
### For RML mods
For RML mods, it's important to note that some requires installing as a jarmod, and some requires installing to the `mods` folder. For jarmods, **order is important**. Most issues related to jarmods are usually due to incorrect order. For example, fixes for The Aether **must be** positioned after The Aether mod itself for it to take effect. Some mods will also requires extracting resources to the `.minecraft/resources` folder, so it's important to look at the mod .ZIP file to see if there's any installation guide.

Due to limited block IDs, you should only install mods that uses ID saving techniques such as metadata to save as much IDs as possible.
### For total conversion mods
Most total conversion mods can be installed the same way as jarmod; however, some will requires replacing the jar instead of adding to the jar (like AlphaVer.)

BetaCraft Launcher (refer to [Getting started](getting-started.md) for more info) is recommended for these types of mod.

It's also important to note that picking the correct base version is required (for example, Better than Adventure! is developed using Beta 1.7.3 as a base.)
### For Babric/Cursed Legacy/Legacy Fabric mods
Install them the same way as you did on modern Minecraft: add mods to the `mods` folder and you're all set.

**DO NOT add anything to Minecraft jar as it will cause compatibility issues.**

If you use Apron, drop all of your RML mods into the `mods` folder and Apron will handle the rest. Please do note however that compatibility is not perfect and mods that makes heavy base class edits may not work properly.