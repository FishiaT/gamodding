## Obtaining mods
Now that you got your favorite modloader installed, it's time to look for mods!

Please do note that due to certain limitations in Minecraft's codebase at the time (block IDs limit, sprite IDs limit, etc..), playing with multiple large content mods can be extremely frustrating, especially when playing with poorly-coded mods (which were common at the time). Due to that, it's recommended to look for community-made patches that fix those problems for more compatibility.

### Mod sites

You can find most mods for legacy Minecraft here.

| Name | Definition |
| ---- | ---------- |
| [Modification Station Discord](https://discord.gg/8Qky5XY) | The largest community for everything legacy Minecraft related. You can find most mods, plugins, and compatibility/multiplayer patches for legacy Minecraft here. |
| [MCArchive](https://mcarchive.net/mods) | Archive lots of old mods, some of which cannot be found anywhere else. The go-to place for most old mods like The Aether, IC2, and so on. | 
| [Glass Repo](https://glass-repo.net/repo/mods) | A mod repostiory for legacy Minecraft. Newer mods for Babric and Station API can also be found here. Also contains lots of mod fixes and patches. |
| [Minecraft Beta 1.7.3 Mod Archive](https://archive.org/details/minecraftbeta1.7.3modarchive) | A comprehensive mod archive for Beta 1.7.3 with more than 1000 files; however, it can be hard to troubleshoot as there are no descriptions whatsoever. |
| [Modrinth](https://modrinth.com/mods) | Mods mainly made for Babric/Legacy Fabric can be found here. |

### Installing mods
### For RML mods
For RML mods, it's important to note that some requires installing as a jarmod, and some requires installing to the `mods` folder. For jarmods, **order is important**. Most issues related to jarmods are usually due to incorrect order. For example, fixes for The Aether **must be** positioned after The Aether mod itself. Some mods will also requires extracting resources to the `.minecraft/resources` folder, so it's important to look at the mod .ZIP file to see if there's any installation guide.
### For total conversion mods
Most total conversion mods can be installed the same way as jarmod; however, some will requires replacing the jar instead of adding to the jar (like AlphaVer.)

It's also important to note that picking the correct base version is required (for example, Better than Adventure! is developed using Beta 1.7.3 as a base.)
### For Babric/Cursed Fabric/Legacy Fabric mods
Install them the same way as you did on modern Minecraft: add mods to the `mods` folder and you're all set.

**DO NOT add anything to Minecraft jar as it will cause compatibility issues.**